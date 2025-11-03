# Career Coach & Resume Assistant - Project Structure

## Directory Organization

```
career-coach-resume-assistant/
├── README.md (main project guide)
├── QUICK_START.md (getting started guide)
├── AI_PROJECT_ASSISTANT_PROMPT.md (core AI instructions)
│
├── personal-files/ (your private documents)
│   ├── README.md (instructions for this folder)
│   ├── current-resume/
│   ├── cover-letters/
│   ├── research-papers/
│   ├── certifications/
│   └── portfolio-samples/
│
├── job-roles/ (job descriptions you're applying to)
│   ├── README.md (instructions for this folder)
│   └── [company-name]_[role-title]_[date].md
│
├── prompts/ (AI prompt templates - activate these)
│   ├── README.md (how to use prompts)
│   ├── 01-profile-analyzer.md (analyze your skills deeply)
│   ├── 02-job-role-analyzer.md (analyze job descriptions)
│   ├── 03-resume-tailor.md (customize resume for roles)
│   ├── 04-interview-prep.md (prepare for interviews)
│   ├── 05-career-planning.md (career development planning)
│   ├── 06-linkedin-optimizer.md (optimize LinkedIn profile)
│   ├── 07-cover-letter-generator.md (create tailored cover letters)
│   └── 08-salary-negotiation.md (negotiation strategies)
│
├── output/ (generated documents and analyses)
│   ├── skill-profiles/
│   ├── tailored-resumes/
│   ├── job-analyses/
│   ├── cover-letters/
│   └── career-plans/
│
└── .ai-workspace/ (AI memory and context)
    ├── README.md
    ├── session-start.md
    ├── context-summary.md
    ├── progress.md
    ├── session-log.md
    ├── personas/
    │   ├── active-personas.json
    │   ├── career-coach.json
    │   ├── career-coach.md
    │   ├── resume-expert.json
    │   ├── resume-expert.md
    │   ├── professional-branding.json
    │   ├── professional-branding.md
    │   ├── interview-coach.json
    │   ├── interview-coach.md
    │   ├── industry-analyst.json
    │   └── industry-analyst.md
    └── test-checkpoints/
```

## Key Features

1. **Personal Files Management**: Secure storage for your professional documents
2. **Job Role Analysis**: Deep analysis of job descriptions and company research
3. **Smart Prompts**: Pre-built, research-backed prompt templates
4. **Persona System**: Specialized AI experts for different career needs
5. **Output Tracking**: Organized storage of all generated materials
6. **Context Preservation**: AI remembers your profile across sessions