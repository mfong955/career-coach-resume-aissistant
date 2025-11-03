# Personal Files Directory

## Purpose
This directory stores your private professional documents that the AI will analyze to understand your skills, experience, and career trajectory.

## What to Include

### 1. Current Resume (`current-resume/`)
- Your most up-to-date resume in any format (.pdf, .docx, .md)
- Multiple versions if you have them (technical, managerial, etc.)
- Name files clearly: `resume_2024_current.pdf`

### 2. Cover Letters (`cover-letters/`)
- Examples of cover letters you've written
- Both successful and unsuccessful applications
- These help the AI understand your writing style and how to maintain your voice

### 3. Research Papers (`research-papers/`)
- Published papers, articles, or blog posts
- Technical documentation you've written
- Presentations or white papers
- These showcase your expertise and thought leadership

### 4. Certifications (`certifications/`)
- Professional certifications
- Training completion certificates
- Awards and recognitions
- License documentation

### 5. Portfolio Samples (`portfolio-samples/`)
- Code samples or GitHub links
- Design work or creative projects
- Case studies or project summaries
- Performance reviews or testimonials

## Privacy & Security

⚠️ **IMPORTANT**: These files remain local on your machine. The AI only reads them when you explicitly activate analysis prompts. Never share sensitive information like:
- Social Security Numbers
- Personal addresses (unless needed for applications)
- Confidential company information
- Salary details (unless needed for negotiation prep)

## How the AI Uses These Files

When you activate the **Profile Analyzer** prompt ([`prompts/01-profile-analyzer.md`](../prompts/01-profile-analyzer.md)), the AI will:

1. **Deep Dive Analysis**: Read all your documents thoroughly
2. **Skill Extraction**: Identify technical and soft skills
3. **Experience Mapping**: Understand your career progression
4. **Achievement Quantification**: Find measurable results
5. **Writing Style**: Learn your communication patterns
6. **Gap Analysis**: Identify areas for development

The AI creates a comprehensive profile stored in [`output/skill-profiles/`](../output/skill-profiles/) that serves as a reference for all future resume tailoring and career coaching.

## File Organization Tips

```
personal-files/
├── current-resume/
│   ├── resume_2024_technical.pdf
│   └── resume_2024_leadership.docx
├── cover-letters/
│   ├── cover_letter_google_2024.pdf
│   └── cover_letter_microsoft_2023.pdf
├── research-papers/
│   ├── ml_optimization_paper.pdf
│   └── tech_blog_articles.md
├── certifications/
│   ├── aws_solutions_architect.pdf
│   └── pmp_certification.pdf
└── portfolio-samples/
    ├── project_case_study_1.pdf
    └── github_portfolio_links.md
```

## Getting Started

1. **Add your current resume** to `current-resume/`
2. **Add 2-3 cover letter examples** to `cover-letters/`
3. **Add any relevant papers or articles** to `research-papers/`
4. **Add certifications** to `certifications/`
5. **Add portfolio samples** to `portfolio-samples/`
6. **Run the Profile Analyzer** prompt to create your skill profile

## Next Steps

After populating this folder, activate the Profile Analyzer prompt:
- Open [`prompts/01-profile-analyzer.md`](../prompts/01-profile-analyzer.md)
- Copy the prompt and paste it into your AI conversation
- The AI will analyze all your files and create a comprehensive skill profile