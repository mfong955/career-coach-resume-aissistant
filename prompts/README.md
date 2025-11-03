# Career Coach Prompts Directory

## Overview

This directory contains carefully crafted AI prompt templates that form the backbone of your Career Coach & Resume Assistant package. Each prompt is designed to activate specific AI personas and guide comprehensive analysis and creation of career-related materials.

## How to Use These Prompts

1. **Open the prompt file** you want to use (e.g., `01-profile-analyzer.md`)
2. **Read the "When to Use" section** to confirm it's the right prompt
3. **Check Prerequisites** to ensure you have the necessary files
4. **Copy everything below the "ACTIVATE THIS PROMPT" line**
5. **Paste into your AI conversation** (Claude, ChatGPT, etc.)
6. **Follow the AI's instructions** and provide requested information
7. **Review the output** saved to the `output/` directory

## Prompt Workflow

### Getting Started (First Time Setup)

**Step 1: Profile Analysis**
- **Prompt**: [`01-profile-analyzer.md`](./01-profile-analyzer.md)
- **Purpose**: Deep dive into your skills and experience
- **Output**: Master profile in `output/skill-profiles/`
- **Time**: 30-45 minutes
- **Run this FIRST** - it's the foundation for everything else

### Job Application Workflow

**Step 2: Job Role Analysis**
- **Prompt**: [`02-job-role-analyzer.md`](./02-job-role-analyzer.md)
- **Purpose**: Analyze a specific job description and company
- **Output**: Comprehensive analysis in `output/job-analyses/`
- **Time**: 20-30 minutes
- **Run this** after adding a job description to `job-roles/`

**Step 3: Resume Tailoring**
- **Prompt**: [`03-resume-tailor.md`](./03-resume-tailor.md)
- **Purpose**: Create a customized resume for the role
- **Output**: Tailored resume in `output/tailored-resumes/`
- **Time**: 15-20 minutes
- **Run this** after completing job role analysis

**Step 4: Cover Letter (Optional)**
- **Prompt**: [`07-cover-letter-generator.md`](./07-cover-letter-generator.md)
- **Purpose**: Create a compelling cover letter
- **Output**: Cover letter in `output/cover-letters/`
- **Time**: 10-15 minutes
- **Run this** if the application requests a cover letter

**Step 5: Interview Preparation**
- **Prompt**: [`04-interview-prep.md`](./04-interview-prep.md)
- **Purpose**: Prepare for interviews with questions and answers
- **Output**: Interview guide in `output/interview-prep/`
- **Time**: 30-45 minutes
- **Run this** after receiving an interview invitation

**Step 6: Salary Negotiation**
- **Prompt**: [`08-salary-negotiation.md`](./08-salary-negotiation.md)
- **Purpose**: Prepare for salary negotiations
- **Output**: Negotiation guide in `output/salary-negotiation/`
- **Time**: 20-30 minutes
- **Run this** after receiving a job offer

### Career Development Workflow

**Career Planning**
- **Prompt**: [`05-career-planning.md`](./05-career-planning.md)
- **Purpose**: Create a strategic career development plan
- **Output**: Career plan in `output/career-plans/`
- **Time**: 45-60 minutes
- **Run this** when planning your next career move

**LinkedIn Optimization**
- **Prompt**: [`06-linkedin-optimizer.md`](./06-linkedin-optimizer.md)
- **Purpose**: Optimize your LinkedIn profile
- **Output**: LinkedIn guide in `output/professional-branding/`
- **Time**: 30-45 minutes
- **Run this** when updating your professional online presence

## Prompt Details

### 01. Profile Analyzer
**File**: [`01-profile-analyzer.md`](./01-profile-analyzer.md)

**What it does:**
- Analyzes all your professional documents
- Extracts and categorizes every skill
- Maps your career progression
- Quantifies achievements
- Creates a comprehensive skill profile

**When to use:**
- First time setup (REQUIRED)
- After major career milestones
- When gaining new skills or certifications
- Annual career review

**Output location:** `output/skill-profiles/`

---

### 02. Job Role Analyzer
**File**: [`02-job-role-analyzer.md`](./02-job-role-analyzer.md)

**What it does:**
- Deep analysis of job requirements
- Independent company research
- Competitive positioning assessment
- Skills gap analysis
- Application strategy recommendations

**When to use:**
- After adding a job description to `job-roles/`
- Before tailoring your resume
- When evaluating if a role is a good fit

**Output location:** `output/job-analyses/`

---

### 03. Resume Tailor
**File**: [`03-resume-tailor.md`](./03-resume-tailor.md)

**What it does:**
- Creates ATS-optimized resume
- Emphasizes relevant experience
- Quantifies achievements
- Maintains honesty and accuracy
- Optimizes for specific role

**When to use:**
- After completing job role analysis
- Before submitting any application
- When applying to different role types

**Output location:** `output/tailored-resumes/`

**Critical principle:** 100% honesty - no exaggeration or fabrication

---

### 04. Interview Prep
**File**: [`04-interview-prep.md`](./04-interview-prep.md)

**What it does:**
- Generates likely interview questions
- Crafts STAR-method answers
- Prepares technical questions
- Develops questions to ask
- Provides interview strategy

**When to use:**
- After receiving interview invitation
- Before phone screens or technical interviews
- When preparing for final rounds

**Output location:** `output/interview-prep/`

---

### 05. Career Planning
**File**: [`05-career-planning.md`](./05-career-planning.md)

**What it does:**
- Clarifies career goals
- Assesses current position
- Identifies development needs
- Creates actionable roadmap
- Defines success metrics

**When to use:**
- When planning next career move
- During annual reviews
- When considering career transitions
- To set long-term goals

**Output location:** `output/career-plans/`

---

### 06. LinkedIn Optimizer
**File**: [`06-linkedin-optimizer.md`](./06-linkedin-optimizer.md)

**What it does:**
- Optimizes LinkedIn headline
- Writes compelling About section
- Enhances experience descriptions
- Improves searchability
- Creates content strategy

**When to use:**
- When updating LinkedIn profile
- Before starting job search
- To improve recruiter visibility
- When pivoting careers

**Output location:** `output/professional-branding/`

---

### 07. Cover Letter Generator
**File**: [`07-cover-letter-generator.md`](./07-cover-letter-generator.md)

**What it does:**
- Creates tailored cover letters
- Demonstrates company knowledge
- Highlights relevant achievements
- Maintains authentic voice
- Complements resume

**When to use:**
- When application requests cover letter
- To stand out in competitive applications
- When explaining career transitions
- To demonstrate genuine interest

**Output location:** `output/cover-letters/`

---

### 08. Salary Negotiation
**File**: [`08-salary-negotiation.md`](./08-salary-negotiation.md)

**What it does:**
- Researches market rates
- Calculates your market value
- Develops negotiation strategy
- Creates negotiation scripts
- Analyzes total compensation

**When to use:**
- After receiving job offer
- During annual review discussions
- When discussing promotions
- When evaluating multiple offers

**Output location:** `output/salary-negotiation/`

## Best Practices

### 1. Start with Profile Analyzer
Always run the Profile Analyzer first. It creates the foundation that all other prompts reference.

### 2. Keep Files Updated
Update your `personal-files/` whenever you:
- Complete major projects
- Gain new skills or certifications
- Receive awards or recognition
- Change roles or responsibilities

### 3. Run Prompts in Sequence
For job applications, follow the workflow:
1. Profile Analyzer (one time)
2. Job Role Analyzer (per job)
3. Resume Tailor (per job)
4. Cover Letter (if needed)
5. Interview Prep (when invited)
6. Salary Negotiation (when offered)

### 4. Customize as Needed
These prompts are templates. Feel free to:
- Add specific questions
- Request additional analysis
- Adjust the focus areas
- Combine prompts if appropriate

### 5. Review AI Output
Always review and verify:
- Factual accuracy
- Tone and voice
- Completeness
- Relevance to your situation

### 6. Iterate and Improve
If the output isn't quite right:
- Provide more context
- Ask clarifying questions
- Request specific changes
- Run the prompt again with updates

## Prompt Design Philosophy

These prompts are designed with several key principles:

### Comprehensive Research
Each prompt instructs the AI to conduct thorough research and analysis, not just respond to surface-level information.

### Honesty First
Especially in resume and application materials, the prompts emphasize 100% factual accuracy and explicitly forbid exaggeration.

### Context Awareness
Prompts reference your master profile and previous analyses to maintain consistency and build on prior work.

### Actionable Output
Every prompt produces specific, usable deliverables saved to organized directories.

### Persona-Based
Prompts activate specific AI personas (Career Coach, Resume Expert, etc.) to provide specialized expertise.

### Question-Driven
Prompts encourage the AI to ask clarifying questions rather than make assumptions.

## Troubleshooting

### "The AI didn't follow the prompt"
- Ensure you copied everything below "ACTIVATE THIS PROMPT"
- Try rephrasing or emphasizing specific sections
- Provide more context about your situation

### "The output is too generic"
- Make sure you've run Profile Analyzer first
- Provide more specific information when asked
- Request more detailed analysis in specific areas

### "The AI is making things up"
- Remind it to stick to documented facts
- Provide your actual documents for reference
- Ask it to cite specific examples from your profile

### "I need something different"
- Customize the prompt for your needs
- Combine elements from multiple prompts
- Ask the AI to adjust its approach

## Getting Help

If you need assistance:
1. Review the prompt's "When to Use" and "Prerequisites" sections
2. Check that you have the required files in place
3. Read the "Success Criteria" to understand expected outcomes
4. Try running the prompt again with more context
5. Consult the main project README for overall guidance

## Contributing

As you use these prompts, you may discover improvements:
- More effective phrasing
- Additional analysis areas
- Better output formats
- New use cases

Feel free to modify and enhance these prompts for your needs!