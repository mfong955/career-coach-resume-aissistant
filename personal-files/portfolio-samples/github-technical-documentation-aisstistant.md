# GitHub Repository: Career Coach Resume Assistant

**Repository URL** (private): https://github.com/mfong955/professional-doc-aissistant

---

## Instructions
Copy and paste information from your GitHub repository below. Include:
- Repository description
- README content
- Project architecture and structure
- Technologies used
- Key features and capabilities
- Your role and contributions

The Profile Analyzer will use this to understand your software development and AI integration skills.

---

## Repository Description
A tool for managing feature resources locally in your workspace and generating documentation.

---

## README Content
# DocAIssistant

A tool for managing feature resources locally in your workspace and generating documentation. This is now part of the TCXGenAIContext package.

## Overview

This package allows you to upload and manage feature resources locally in your workspace, then use AI to generate documentation content plans, drafts, and more. 
1. Input your feature resources
2. Tell AI to `Run X prompt` to kick off advanced prompts to help build:
   - Content plan
   - A more robust doc draft based the content plan
   - Edit passes
   - Fact checks 

## Directory structure

```
<workspace>/src/                      # Your source code packages
└── TCXGenAIContext/                  # Main package
    └── prompts/                      # Prompt templates and scripts
        └── doc-assistant/            # This tool
            ├── feature-resources/    # Directory for your feature resources
            ├── prompts/              # Prompt templates for Amazon Q
            │   ├── draft-content-plan.script.md
            │   ├── draft-docs.script.md
            │   ├── editor-pass.script.md
            │   ├── fact-checker.script.md
            │   └── references/        # Reference materials for prompts
            │       └── scenario-guide.md
            │       └── style-guide.md
            ├── tools/                # Utility tools
            │   ├── bedrock-summarizer.py
            │   └── run-summarizer.sh
            └── output/               # Generated output files
                ├── content-plan.md
                ├── docs.md
                └── resources-summary.md
```

## Prerequisites

This package has been tested with macOS, VS Code, and Amazon Q extension. It *should* work with other setups, though they haven't been tested.

- **AWS Setup**:
  - [Install the latest AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
  - [Configure your default profile with ADA CLI](https://w.amazon.com/bin/view/AWSDocs/ML/CodeExamplesPrerequisites#HInstalltheADACLIandconfigureadefaultprofiletouseittogetyourAWScredentials)
  - [Enable access to Amazon Bedrock Claude models (choose all 2+ models)](https://docs.aws.amazon.com/bedrock/latest/userguide/model-access-modify.html) in `us-east-1` (same region as Amazon Q extension)

- **Development Environment**:
  - [Python 3.6+](https://www.python.org/downloads/)
  - [VS Code](https://code.visualstudio.com/download)
  - [Amazon Q extension for VS Code](https://docs.hub.amazon.dev/qdeveloper/user-guide/getting-started/)
  - (Recommended) [Amazon MCP server installation and Setup](https://w.amazon.com/bin/view/ASBX/AI/FAQs/QCLI/#installation) for enhanced Model Context Protocol support.
      - Make sure to set up Quip and Slack integration for compatibility for more features in this tool
      - If the Amazon Q extension in VS Code is failing to find your MCP configuration: 
         1. Find the absolute path by running `which amzn-mcp` in your terminal
         1. Modify your `~/.aws/amazonq/mcp.json` file and replace `"command": "amzn-mcp"` with `"command": "<ouput-from-previous-step>"`

- **Python Dependencies** (automatically installed):
  - `boto3` (latest) - AWS SDK for Bedrock API access
  - `python-docx` (latest) - For reading .docx files

**Note**: Dependencies are automatically installed when you run `./tools/run-summarizer.sh`. If you prefer manual installation: `pip3 install -r requirements.txt`

## Set up

This is now part of the TCXGenAIContext package for you to use along with an AI extension in an IDE. 
- No need to build
- Access it through the TCXGenAIContext package

1. Use brazil to create a new workspace:
   ```bash
   cd ~/workplace/${USER}
   brazil ws create -n tcx-context -versionset AWSDevDocsAlpha/alpha
   cd tcx-context
   brazil ws use -p TCXGenAIContext
   ```
2. In VS Code, open the repository in a new window (File > New Window > Open folder)
   - If the Amazon Q extension isn't available on the left sidebar, you may need to [install it again](https://docs.hub.amazon.dev/qdeveloper/user-guide/getting-started/)
3. Follow the example workflow below to get started

# Usage instructions

**Important**: Use one Amazon Q chat per feature. Amazon Q remembers conversation, which can affect the quality of documentation for your current work. To work on a new feature, either:
- Create a new VS Code profile, or
- Create a new workspace with TCXGenAIContext

## Example workflow

> **Important**: Always review, edit, and verify the content of each output file before proceeding to the next step for better quality outputs.

1. First, add your feature resources to the `feature-resources` directory.

   **Supported file types**: PDF (.pdf), Word documents (.docx), text files (.txt), and Markdown files (.md)

   **Option 1 - Copy existing files**:
   - Open your file manager (Finder on Mac, File Explorer on Windows)
   - Navigate to your existing documents (PRDs, specs, meeting notes, etc.)
   - Copy the files you want to analyze
   - In VS Code, left-click on the `feature-resources` folder in the file explorer panel
   - Paste (Cmd+V or Ctrl+V) to add your files

   **Option 2 - Create new files from copied content**:
   If you have content in emails, web pages, or other sources:
   - In VS Code, right-click on the `feature-resources` folder
   - Select "New File"
   - Name your file with a descriptive name ending in `.md` (for example: `requirements.md`, `meeting-notes.md`, `user-feedback.md`)
   - Copy your content from the source (email, web page, etc.)
   - Paste it into the new file
   - Save the file (Ctrl+S on Windows, Cmd+S on Mac) 

2. Navigate to the doc-assistant directory in the terminal.
   **In the terminal** (For example, [access the VS Code terminal](https://code.visualstudio.com/docs/terminal/getting-started) by selecting **View** > **Terminal** from the menu bar, or using the ⌃` keyboard shortcut), run: 
   ```bash
   cd ~/workplace/${USER}/tcx-context/src/TCXGenAIContext/prompts/doc-assistant
   ```
   The following commands and prompts assume that you are running them from within the `doc-assistant` directory.

3. Run `tools/run-summarizer.sh` to generate resource summaries. This processes your files into individual summaries and a master summary that AI tools can analyze efficiently.

   **In the terminal** (For example, [access the VS Code terminal](https://code.visualstudio.com/docs/terminal/getting-started) by selecting **View** > **Terminal** from the menu bar, or using the ⌃` keyboard shortcut), run:
   ```bash
   ./tools/run-summarizer.sh
   ```
   
   **Or ask Amazon Q** in the chat panel:
   ```
   Run the command: ./tools/run-summarizer.sh
   ```
   
   - **Important**: If you update any files in the `feature-resources` directory, make sure to rerun `./tools/run-summarizer.sh` to regenerate the summaries
   - This creates individual `summary-[filename].md` files and a `summary-master.md` in the output directory

4. To generate a content plan, **ask Amazon Q** in the chat panel:
   ```
   Run `draft-content-plan.script.md` prompt
   ```

5. To create documentation draft, **ask Amazon Q**:
   ```
   Run `draft-docs.script.md` prompt
   ```

6. (Optional) To check a draft for factual accuracy against the resource summary, **ask Amazon Q**:
   ```
   Run `fact-checker.script.md` prompt
   ```
   - The AI will ask which file you want to analyze against the `./output/summary-master.md` from step 3
   - Review the comparison report in `output/[filename]-fact-check.md`

7. To get an editor pass on any output file, **ask Amazon Q**:
   ```
   Run `editor-pass.script.md` prompt
   ```
   - The AI will ask which file you want to edit

### Converting Markdown to Word / Quip

To convert Markdown files to Word documents (.docx), **in VS Code terminal** run:

```bash
# Convert docs.md to docs.docx
pandoc -o output/docs.docx -f markdown -t docx output/docs.md

# Convert content-plan.md to content-plan.docx
pandoc -o output/content-plan.docx -f markdown -t docx output/content-plan.md
```

To install Pandoc, see [Installing Pandoc](https://pandoc.org/installing.html)

#### Converting Word to Quip

> **Note**: Unfortunately, Quip doesn't currently have a direct Markdown import feature. If you'd like to see this feature added, please +1 the ticket here: https://sim.amazon.com/issues/P120583309

1. Follow the instructions in [Converting Markdown to Word documents](./README.md#converting-markdown-to-word-documents)
2. Copy/paste the content to Quip.

### Working with Quip Documents

#### Converting Quip to Markdown with Comments

You can convert a Quip document to Markdown format with comments preserved in their appropriate locations by asking Amazon Q to:

```
Run `quip-to-markdown-with-comments.script.md` prompt
```

You can also include the Quip URL directly in your request:

```
Run `quip-to-markdown-with-comments.script.md` prompt with https://quip-amazon.com/abc123/Document-Title
```

This prompt will:
1. Read the Quip document content using MCP
2. Retrieve all comments from the document
3. Convert the HTML content to Markdown format
4. Insert comments at their appropriate locations in the Markdown
5. Save the result to a file named `quip-comments-{document_id}.md` in the output directory

**Note**: This prompt requires the MCP server to be configured with Quip access. See the [Prerequisites section](#prerequisites) for details on setting up the MCP server.

#### Analyzing and Addressing Comments

After converting a Quip document to Markdown with comments, you can analyze the comments and create a revised document that addresses them by asking Amazon Q to:

```
Run `analyze-and-address-comments.script.md` prompt
```

You can also specify a particular file to analyze:

```
Run `analyze-and-address-comments.script.md` prompt with output/quip-comments-abc123.md
```

This prompt will:
1. Identify and extract all comments from the document
2. Classify each comment into categories (action items, questions, suggestions, etc.)
3. Create a revised version of the document that addresses all actionable comments
4. Add an appendix that lists all comments with their classifications and actions taken
5. Save the revised document to a file named `{original_filename}-revised.md` in the output directory

The appendix provides a comprehensive record of how each comment was addressed, making it easy to track changes and ensure all feedback has been incorporated.

### Converting Markdown to AWS DocBook XML

To convert Markdown files to AWS DocBook XML format for publication, ask Amazon Q to:

```
Run `markdown-to-aws-xml.script.md` prompt with [filename].md
```

This automated process handles:
- Initial pandoc conversion to DocBook format
- AWS-specific XML formatting (emphasis, links, code blocks)
- Section metadata and info blocks
- Proper XML header with DocBook DTD
- Manual refinements including:
  - Complex section ID patterns
  - Advanced formatting requirements
  - Link validation and final XML structure verification
  - SEO abstracts and keywords for each section

**Prerequisites**: Requires [pandoc](https://pandoc.org/installing.html) to be installed.

## Troubleshooting

### Common Issues and Solutions

#### ❌ "feature-resources directory not found"
**Solution**: Create the directory:
```bash
mkdir -p feature-resources
```

#### ⚠️ "No resource files found"
**Solution**: Add documentation files to the feature-resources directory. Supported formats include .md, .txt, .pdf, .docx, .doc, .html, .csv, .xls, .xlsx, .json

#### ❌ "Missing required Python dependencies"
**Solution**: **In VS Code terminal**, install dependencies:
```bash
pip install -r requirements.txt
```

#### ⚠️ "AWS credentials not configured"
**Solutions**:
- Configure AWS CLI (**in VS Code terminal**):
  ```bash
  aws configure
  ```
- Set environment variables (**in VS Code terminal**):
  ```bash
  export AWS_ACCESS_KEY_ID=your_access_key
  export AWS_SECRET_ACCESS_KEY=your_secret_key
  export AWS_DEFAULT_REGION=us-east-1
  ```

#### ❌ "No suitable Claude models available"
**Solution**: Ensure you have access to Amazon Bedrock Claude models in your AWS account. You may need to:
1. Request access to Claude models in the AWS Bedrock console
2. Verify your AWS region supports Bedrock (try us-east-1 or us-west-2)

#### ❌ "Failed to generate summary with Claude"
**Possible causes and solutions**:
- **Rate limiting**: Wait a few minutes and try again
- **Content too large**: Reduce the number or size of files in feature-resources
- **Model access**: Verify Bedrock model permissions in AWS console

### Opening VS Code Terminal

To open the terminal in VS Code:
- **Menu**: View → Terminal
- **Keyboard shortcut**: Ctrl+` (backtick) on Windows/Linux, Cmd+` on Mac
- **Command Palette**: Ctrl+Shift+P → "Terminal: Create New Terminal"

### Getting Help

If you continue to experience issues:
1. Check the error messages for specific guidance
2. Verify all prerequisites are met
3. Ensure your AWS credentials have Bedrock access
4. Try with a smaller set of files first
**Solution**: Install dependencies:
```bash
pip install -r requirements.txt
```

#### ⚠️ "AWS credentials not configured"
**Solutions**:
- Configure AWS CLI: `aws configure`
- Set environment variables:
  ```bash
  export AWS_ACCESS_KEY_ID=your_access_key
  export AWS_SECRET_ACCESS_KEY=your_secret_key
  export AWS_DEFAULT_REGION=us-east-1
  ```

#### ❌ "No suitable Claude models available"
**Solution**: Ensure you have access to Amazon Bedrock Claude models in your AWS account. You may need to:
1. Request access to Claude models in the AWS Bedrock console
2. Verify your AWS region supports Bedrock (try us-east-1 or us-west-2)

#### ❌ "Failed to generate summary with Claude"
**Possible causes and solutions**:
- **Rate limiting**: Wait a few minutes and try again
- **Content too large**: Reduce the number or size of files in feature-resources
- **Model access**: Verify Bedrock model permissions in AWS console

### Getting Help

If you continue to experience issues:
1. Check the error messages for specific guidance
2. Verify all prerequisites are met
3. Ensure your AWS credentials have Bedrock access
4. Try with a smaller set of files first
5. Otherwise, feel free to contact @mwfong for help with the `doc-assistant` package


---

## Project Overview

### Purpose
Streamline drafting process for writing technical documentation for AI/ML feature work at AWS. From end-to-end, given the feature resources, I could create documentation draft within minutes. For more robust documentation, I would spend more time. However, using this tool significantly improved my output quality and speed

### Architecture
Uses service team resources + AI prompting to: create a robust content plan, documentation draft, editor pass, fact checker, and quip integration with review and comment resolution. This implemented the scenario and style guide of the company.

### Key Components
Please intepret from above

---

## Technologies & Tools Used

### Programming Languages
Python

### Development Tools
VS Code and AI extensions

---

## Key Features
 Please interpret from above

---

## Your Role & Contributions
I created everything in this package. 

---

## Skills Demonstrated

### Software Development
- Using AI tools to streamline work

---

## Project Impact

### User Benefits
Helps technical writers for documentation for new services and features

### Technical Achievements
Robust package that streamlined documentation drafting and reviews with service teams

### Learning Outcomes
How to create and improve AI tooling

---

## Future Enhancements
Many, but I can discuss this if someone asks.

---

## Notes for Profile Analyzer
- Emphasize software engineering skills
- Highlight AI/ML integration capabilities
- Note project management and planning abilities
- Identify transferable skills for various roles
- Show ability to create practical, user-focused solutions