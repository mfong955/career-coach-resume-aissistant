# GitHub Repository: Career Coach Resume Assistant

**Repository URL**: https://github.com/mfong955/career-coach-resume-aissistant

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
A comprehensive AI-powered career coaching and resume assistance package designed to help you navigate your career journey, optimize your job search, and land your dream role.

---

## README Content
# Career Coach & Resume Assistant

A comprehensive AI-powered career coaching and resume assistance package designed to help you navigate your career journey, optimize your job search, and land your dream role.

## 🎯 What This Package Does

This package provides you with:

- **Unlimited Career Coaching**: Strategic guidance for career planning, transitions, and professional development
- **Professional Resume Assistance**: AI-powered resume review, tailoring, and optimization for specific roles
- **Professional Branding**: LinkedIn optimization and personal brand development
- **Interview Preparation**: Comprehensive prep with likely questions, strong answers, and strategy
- **Salary Negotiation**: Data-driven negotiation strategies and market intelligence
- **Job Search Strategy**: Systematic approach to finding and landing the right opportunities

## ✨ Key Features

### 🎓 Expert AI Personas
Five specialized AI personas work together to provide comprehensive support:
- **Career Coach**: Strategic career planning and guidance
- **Resume Expert**: Resume writing and optimization (with 100% honesty guarantee)
- **Professional Branding**: LinkedIn and personal brand development
- **Interview Coach**: Interview preparation and practice
- **Industry Analyst**: Company research and market intelligence

### 📝 Ready-to-Use Prompt Templates
Eight carefully crafted prompts for every stage of your job search:
1. **Profile Analyzer**: Deep dive into your skills and experience
2. **Job Role Analyzer**: Comprehensive job and company analysis
3. **Resume Tailor**: Customized resumes for specific roles
4. **Interview Prep**: Complete interview preparation
5. **Career Planning**: Strategic career development roadmap
6. **LinkedIn Optimizer**: Professional online presence
7. **Cover Letter Generator**: Compelling, tailored cover letters
8. **Salary Negotiation**: Compensation strategy and scripts

### 🗂️ Organized Workflow
- **Personal Files**: Store your resume, cover letters, and professional documents
- **Job Roles**: Save and analyze job descriptions
- **Prompts**: Activate AI assistance for specific tasks
- **Output**: All generated materials organized and accessible

## 🚀 Quick Start

### 1. Set Up Your Personal Files

Add your professional documents to [`personal-files/`](./personal-files/):
- Current resume → `personal-files/current-resume/`
- Cover letter examples → `personal-files/cover-letters/`
- Research papers or articles → `personal-files/research-papers/`
- Certifications → `personal-files/certifications/`
- Portfolio samples → `personal-files/portfolio-samples/`

### 2. Run Profile Analyzer (REQUIRED FIRST STEP)

**Simply say**: **"Run the profile analyzer"** or **"Run 01-profile-analyzer.md"**

The AI will automatically check prerequisites and guide you through creating your master profile that all other prompts reference.

**Time**: 30-45 minutes
**Output**: Comprehensive skill profile in `output/skill-profiles/`

### 3. Add Job Descriptions

When you find a role you want to apply to:
1. Create a file in [`job-roles/`](./job-roles/) using the template
2. Name it: `company_role_date.md`
3. Include the full job description and your notes

### 4. Analyze the Job

**Simply say**: **"Run the job role analyzer"** or **"Run 02"**

The AI will:
- Research the company deeply
- Analyze job requirements
- Compare your profile to typical candidates
- Provide application strategy

**Time**: 20-30 minutes
**Output**: Detailed analysis in `output/job-analyses/`

### 5. Tailor Your Resume

**Simply say**: **"Run the resume tailor"** or **"Run 03"**

The AI will create a customized resume that:
- Emphasizes relevant experience
- Optimizes for ATS systems
- Maintains 100% honesty
- Positions you as the ideal candidate

**Time**: 15-20 minutes
**Output**: Tailored resume in `output/tailored-resumes/`

### 6. Prepare for Interviews

**Simply say**: **"Run the interview prep"** or **"Run 04"**

The AI will:
- Generate likely questions
- Craft strong STAR-method answers
- Develop insightful questions to ask
- Build confidence through preparation

**Time**: 30-45 minutes
**Output**: Interview guide in `output/interview-prep/`

### 7. Negotiate Your Offer

**Simply say**: **"Run the salary negotiation"** or **"Run 08"**

The AI will:
- Research market rates
- Calculate your value
- Develop negotiation strategy
- Practice negotiation scripts

**Time**: 20-30 minutes
**Output**: Negotiation guide in `output/salary-negotiation/`

## 📁 Project Structure

```
career-coach-resume-assistant/
├── README.md                    # This file - project overview
├── QUICK_START.md              # Step-by-step getting started guide
│
├── personal-files/             # Your professional documents
│   ├── current-resume/         # Your current resume(s)
│   ├── cover-letters/          # Cover letter examples
│   ├── research-papers/        # Publications and articles
│   ├── certifications/         # Professional certifications
│   └── portfolio-samples/      # Work samples and projects
│
├── job-roles/                  # Job descriptions you're applying to
│   ├── README.md              # Instructions for this folder
│   └── EXAMPLE_job-description-template.md
│
├── prompts/                    # AI prompt templates (activate these!)
│   ├── README.md              # How to use prompts
│   ├── 01-profile-analyzer.md
│   ├── 02-job-role-analyzer.md
│   ├── 03-resume-tailor.md
│   ├── 04-interview-prep.md
│   ├── 05-career-planning.md
│   ├── 06-linkedin-optimizer.md
│   ├── 07-cover-letter-generator.md
│   └── 08-salary-negotiation.md
│
├── output/                     # AI-generated materials
│   ├── skill-profiles/         # Your comprehensive skill analyses
│   ├── job-analyses/           # Job and company research
│   ├── tailored-resumes/       # Customized resumes
│   ├── cover-letters/          # Tailored cover letters
│   ├── interview-prep/         # Interview preparation guides
│   ├── career-plans/           # Career development plans
│   ├── professional-branding/  # LinkedIn and branding materials
│   └── salary-negotiation/     # Compensation negotiation guides
│
└── .ai-workspace/              # AI memory and personas
    └── personas/               # Specialized AI expert profiles
```

## 🎯 Core Principles

### 1. Honesty is Non-Negotiable
All prompts, especially resume-related ones, are designed to maintain **100% factual accuracy**. The AI will:
- ✅ Never fabricate or exaggerate skills or experience
- ✅ Always ask for clarification rather than assume
- ✅ Present you strongly but truthfully
- ✅ Help you reframe experiences honestly

### 2. Comprehensive Research
The AI conducts deep, independent research to:
- Understand companies and roles thoroughly
- Provide market intelligence and competitive insights
- Position you strategically based on real data
- Support informed decision-making

### 3. Personalized Approach
Every output is tailored to:
- Your specific skills and experience
- The target role and company
- Your career goals and values
- Your authentic communication style

### 4. Systematic Workflow
Follow the prompts in sequence for best results:
1. Profile Analyzer (foundation)
2. Job Role Analyzer (understanding)
3. Resume Tailor (application)
4. Interview Prep (preparation)
5. Salary Negotiation (closing)

## 💡 Use Cases

### Job Search
- Analyze job descriptions and companies
- Tailor resumes for specific applications
- Prepare for interviews systematically
- Negotiate offers with confidence

### Career Development
- Create strategic career plans
- Identify skill development priorities
- Plan career transitions
- Set and track career goals

### Professional Branding
- Optimize LinkedIn profile
- Develop content strategy
- Build professional network
- Establish thought leadership

### Career Transitions
- Assess transferable skills
- Position for new industries or roles
- Address gaps or concerns
- Build confidence in new direction

## 🔒 Privacy & Security

- All files remain **local on your machine**
- AI only accesses files when you explicitly activate prompts
- No data is shared without your action
- You control what information to include
- Consider using `.gitignore` if using version control

## 📚 Additional Resources

### Documentation
- [`personal-files/README.md`](./personal-files/README.md) - How to organize your documents
- [`job-roles/README.md`](./job-roles/README.md) - How to add and structure job descriptions
- [`prompts/README.md`](./prompts/README.md) - Detailed prompt usage guide
- [`output/README.md`](./output/README.md) - Understanding generated materials

### Personas
Learn about the AI experts helping you:
- [Career Coach](./ai-workspace/personas/career-coach.md)
- [Resume Expert](./ai-workspace/personas/resume-expert.md)
- [Professional Branding](./ai-workspace/personas/professional-branding.md)
- [Interview Coach](./ai-workspace/personas/interview-coach.md)
- [Industry Analyst](./ai-workspace/personas/industry-analyst.md)

## 🎓 Best Practices

### For Best Results

1. **Start with Profile Analyzer**: This is the foundation - don't skip it
2. **Be thorough with personal files**: More information = better analysis
3. **Use complete job descriptions**: Don't summarize or edit them
4. **Follow the workflow**: Prompts build on each other
5. **Review and personalize**: AI provides drafts - make them yours
6. **Update regularly**: Keep your profile current as you grow

### Common Mistakes to Avoid

- ❌ Skipping the Profile Analyzer
- ❌ Not providing enough context
- ❌ Editing job descriptions before analysis
- ❌ Accepting AI output without review
- ❌ Forgetting to update your master profile
- ❌ Not tailoring for each application

## 🤝 How to Use This Package

### Easy Activation Method (Recommended) 🎉
**No more copying and pasting!** Just say:
- **"Run the profile analyzer"**
- **"Run the job role analyzer"**
- **"Run resume tailor"**
- Or any similar variation!

The AI will automatically check prerequisites and guide you through the process.

### Traditional Method (Still Works)
If you prefer the traditional approach:
1. Open the prompt file (e.g., `prompts/01-profile-analyzer.md`)
2. Copy everything below "PROMPT INSTRUCTIONS (For AI)"
3. Paste into your AI conversation
4. Follow AI's instructions
5. Review generated output

### Compatible AI Assistants
Works with Claude, ChatGPT, and other capable AI assistants.

## 📈 Success Metrics

Track your progress:
- Interview request rate
- Quality of opportunities
- Confidence in applications
- Time to interview
- Offer quality and quantity
- Career goal achievement

## 🆘 Getting Help

### If Something Isn't Working

1. **Check prerequisites**: Did you run Profile Analyzer first? (say "Run the profile analyzer")
2. **Try the activation command**: Say "Run [prompt name]" or "Run 01", "Run 02", etc.
3. **Provide more context**: The AI may need additional information
4. **Try variations**: "Activate profile analyzer", "Start 01-profile-analyzer.md", etc.
5. **Use traditional method**: Copy and paste the prompt if activation doesn't work
6. **Check the README**: Each directory has usage instructions

### Common Questions

**Q: Do I need to run Profile Analyzer every time?**  
A: No, just once initially and when you have major updates.

**Q: Can I customize the prompts?**  
A: Yes! They're templates - adjust them for your needs.

**Q: How long does each prompt take?**  
A: 15-45 minutes depending on the prompt and depth needed.

**Q: Is my data private?**  
A: Yes, everything stays local unless you explicitly share it.

**Q: Can I use this for multiple job searches?**  
A: Absolutely! That's what it's designed for.

## 🎉 What Makes This Package Special

### Comprehensive Coverage
From initial career planning through salary negotiation - everything you need in one place.

### Research-Backed Prompts
Each prompt is carefully designed based on career coaching best practices and recruiter insights.

### Honesty-First Approach
Unlike generic AI tools, this package prioritizes truthful, authentic representation.

### Systematic Workflow
Clear, step-by-step process that builds on itself for maximum effectiveness.

### Specialized Expertise
Five AI personas provide deep expertise in their specific domains.

### Organized Output
All generated materials are systematically organized and easy to find.

## 🚀 Ready to Get Started?

1. **Read** [`QUICK_START.md`](./QUICK_START.md) for detailed setup instructions
2. **Add** your professional documents to `personal-files/`
3. **Run** the Profile Analyzer prompt
4. **Start** applying to jobs with confidence!

## 📝 License & Usage

This package is designed for personal career development use. Feel free to customize and adapt it for your needs.

---

**Remember**: This package is a tool to help you present your authentic self effectively. The AI assists, but you're in control. Your career journey is unique - use these tools to tell your story honestly and compellingly.

**Good luck with your career journey! 🎯**

---

## Project Overview

### Purpose
Create a package for people to move on to their next company or role. One repository for keeping all resume, work, research, etc. resources.

### Architecture
It is this package. Please interpret from README

### Key Components
Please interpret from README

---

## Technologies & Tools Used
Please interpret from README

---

## Key Features
Please interpret from README

---

## Your Role & Contributions
I created this package on my own

---

## Skills Demonstrated
Please interpret from README

---

## Project Impact
Please interpret from README

---

## Future Enhancements
TBD

---

## Notes for Profile Analyzer
- Emphasize software engineering skills
- Highlight AI/ML integration capabilities
- Note project management and planning abilities
- Identify transferable skills for various roles
- Show ability to create practical, user-focused solutions