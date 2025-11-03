# Job Roles Directory

## Purpose
Store job descriptions from positions you're interested in applying to. The AI will analyze these to understand requirements, company culture, and how to tailor your resume effectively.

## How to Add Job Descriptions

### File Naming Convention
Use this format for consistency:
```
[company-name]_[role-title]_[date].md
```

Examples:
- `google_senior-software-engineer_2024-01-15.md`
- `microsoft_product-manager_2024-01-20.md`
- `amazon_data-scientist_2024-02-01.md`

### What to Include in Each File

Create a markdown file with the following structure:

```markdown
# [Job Title] at [Company Name]

## Job Posting Details
- **Company**: [Company Name]
- **Location**: [City, State/Remote]
- **Posted Date**: [Date]
- **Application Deadline**: [Date if known]
- **Job URL**: [Link to posting]
- **Salary Range**: [If provided]

## Job Description
[Paste the full job description here]

## Requirements
[List all requirements - both required and preferred]

## Responsibilities
[List all key responsibilities]

## Company Information
[Any additional info about the company, team, or culture]

## Personal Notes
[Your thoughts, questions, or concerns about this role]
- Why this role interests you
- Potential challenges
- Questions to ask in interview
- Connections at the company
```

## How the AI Uses These Files

When you activate the **Job Role Analyzer** prompt ([`prompts/02-job-role-analyzer.md`](../prompts/02-job-role-analyzer.md)), the AI will:

1. **Deep Role Analysis**
   - Parse all requirements (technical, soft skills, experience)
   - Identify key responsibilities and success metrics
   - Understand the seniority level and expectations

2. **Company Research**
   - Research the company's products, services, and culture
   - Understand the industry context and competitive landscape
   - Identify what employees say about working there
   - Find recent news, funding, or strategic initiatives

3. **Skills Gap Analysis**
   - Compare your profile against job requirements
   - Identify your strengths that align with the role
   - Highlight areas where you may need to emphasize transferable skills
   - Suggest honest ways to address gaps

4. **Resume Comparison**
   - Analyze how your experience compares to typical candidates
   - Identify unique differentiators in your background
   - Suggest which experiences to emphasize
   - Recommend quantifiable achievements to highlight

5. **Hiring Manager Perspective**
   - Understand what the hiring manager is likely looking for
   - Identify pain points this role is meant to solve
   - Suggest how to position yourself as the solution
   - Recommend tone and emphasis for your application

## Example Job Description File

See [`job-roles/EXAMPLE_job-description-template.md`](./EXAMPLE_job-description-template.md) for a complete example.

## Workflow

### Step 1: Add Job Description
1. Find a job posting you're interested in
2. Create a new markdown file using the naming convention
3. Copy the job description and fill in all sections
4. Add your personal notes about why this role interests you

### Step 2: Analyze the Role
1. Open [`prompts/02-job-role-analyzer.md`](../prompts/02-job-role-analyzer.md)
2. Copy the prompt and specify which job file to analyze
3. The AI will create a comprehensive analysis in [`output/job-analyses/`](../output/job-analyses/)

### Step 3: Tailor Your Resume
1. Review the job analysis
2. Open [`prompts/03-resume-tailor.md`](../prompts/03-resume-tailor.md)
3. The AI will create a customized resume in [`output/tailored-resumes/`](../output/tailored-resumes/)

### Step 4: Prepare for Interview
1. If you get an interview, use [`prompts/04-interview-prep.md`](../prompts/04-interview-prep.md)
2. The AI will help you prepare based on the role analysis

## Tips for Better Analysis

✅ **DO:**
- Include the complete job description (don't summarize)
- Add any information about the team or hiring manager
- Note any connections you have at the company
- Include salary range if provided
- Add your personal thoughts and questions

❌ **DON'T:**
- Edit or shorten the original job description
- Remove "nice to have" requirements
- Skip company research sections
- Forget to update the date

## Privacy Note

These files are stored locally. The AI only accesses them when you explicitly run analysis prompts. You can delete job descriptions after you've completed the application process or decided not to apply.

## Organization Tips

Consider creating subdirectories by:
- **Status**: `active/`, `applied/`, `interviewing/`, `archived/`
- **Industry**: `tech/`, `finance/`, `healthcare/`
- **Priority**: `high-priority/`, `medium-priority/`, `backup-options/`

Example:
```
job-roles/
├── active/
│   ├── google_senior-swe_2024-01-15.md
│   └── microsoft_pm_2024-01-20.md
├── applied/
│   └── amazon_data-scientist_2024-01-10.md
└── archived/
    └── old-applications/