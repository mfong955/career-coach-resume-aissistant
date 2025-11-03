# Output Directory

## Purpose
This directory stores all AI-generated materials from your career coaching prompts. Everything created by the AI prompts is organized here for easy access and reference.

## Directory Structure

```
output/
├── skill-profiles/          # Your comprehensive skill analyses
├── job-analyses/            # Job description and company research
├── tailored-resumes/        # Customized resumes for specific roles
├── cover-letters/           # Tailored cover letters
├── interview-prep/          # Interview preparation guides
├── career-plans/            # Strategic career development plans
├── professional-branding/   # LinkedIn and personal branding materials
└── salary-negotiation/      # Compensation negotiation guides
```

## What Gets Saved Here

### Skill Profiles (`skill-profiles/`)
**Created by**: Profile Analyzer prompt ([`prompts/01-profile-analyzer.md`](../prompts/01-profile-analyzer.md))

**Contains**:
- Master profile with comprehensive skill inventory
- Career progression analysis
- Unique value proposition
- Communication style guide
- Development roadmap

**File naming**: `master-profile_[DATE].md`

**When created**: First time setup and major updates

---

### Job Analyses (`job-analyses/`)
**Created by**: Job Role Analyzer prompt ([`prompts/02-job-role-analyzer.md`](../prompts/02-job-role-analyzer.md))

**Contains**:
- Job requirements breakdown
- Company research and intelligence
- Competitive positioning analysis
- Skills gap assessment
- Application strategy recommendations

**File naming**: `[company]_[role]_analysis_[DATE].md`

**When created**: For each job you're considering applying to

---

### Tailored Resumes (`tailored-resumes/`)
**Created by**: Resume Tailor prompt ([`prompts/03-resume-tailor.md`](../prompts/03-resume-tailor.md))

**Contains**:
- ATS-optimized plain text resume
- Human-readable formatted resume
- Tailoring notes and recommendations

**File naming**: 
- `[company]_[role]_resume_ATS_[DATE].txt`
- `[company]_[role]_resume_[DATE].md`
- `[company]_[role]_tailoring-notes_[DATE].md`

**When created**: For each job application

---

### Cover Letters (`cover-letters/`)
**Created by**: Cover Letter Generator prompt ([`prompts/07-cover-letter-generator.md`](../prompts/07-cover-letter-generator.md))

**Contains**:
- Tailored cover letter
- Alternative opening options
- Customization notes

**File naming**: `[company]_[role]_cover-letter_[DATE].md`

**When created**: When application requests or benefits from a cover letter

---

### Interview Prep (`interview-prep/`)
**Created by**: Interview Prep prompt ([`prompts/04-interview-prep.md`](../prompts/04-interview-prep.md))

**Contains**:
- Behavioral questions with STAR answers
- Technical questions and approaches
- Questions to ask interviewers
- Interview strategy guide
- Follow-up templates

**File naming**: `[company]_[role]_interview-prep_[DATE].md`

**When created**: After receiving interview invitation

---

### Career Plans (`career-plans/`)
**Created by**: Career Planning prompt ([`prompts/05-career-planning.md`](../prompts/05-career-planning.md))

**Contains**:
- Career vision and goals
- Current state assessment
- Career path options
- Development roadmap
- Action plan with milestones

**File naming**: `career-plan_[DATE].md`

**When created**: When planning career moves or during annual reviews

---

### Professional Branding (`professional-branding/`)
**Created by**: LinkedIn Optimizer prompt ([`prompts/06-linkedin-optimizer.md`](../prompts/06-linkedin-optimizer.md))

**Contains**:
- LinkedIn profile optimization guide
- Headline and About section options
- Content strategy
- Network building plan

**File naming**: `linkedin-optimization_[DATE].md`

**When created**: When updating LinkedIn or starting job search

---

### Salary Negotiation (`salary-negotiation/`)
**Created by**: Salary Negotiation prompt ([`prompts/08-salary-negotiation.md`](../prompts/08-salary-negotiation.md))

**Contains**:
- Market research and valuation
- Total compensation analysis
- Negotiation strategy and scripts
- Decision framework

**File naming**: `[company]_[role]_negotiation-guide_[DATE].md`

**When created**: After receiving job offer

## File Management Tips

### Organization
- Files are automatically named with dates for version tracking
- Keep all versions for reference and comparison
- Archive old materials periodically

### Version Control
- Each prompt run creates a new dated file
- Compare versions to track improvements
- Keep the most recent version easily accessible

### Cleanup
Consider archiving or deleting:
- Job analyses for positions you didn't apply to
- Old resume versions after accepting a job
- Interview prep for completed processes
- Outdated career plans (keep for historical reference)

### Backup
These files contain valuable career materials:
- Back up regularly to cloud storage
- Keep copies outside this directory
- Protect sensitive information

## Privacy & Security

⚠️ **Important**: These files may contain sensitive information:
- Personal achievements and salary history
- Company research and competitive intelligence
- Negotiation strategies and target numbers
- Interview preparation materials

**Best Practices**:
- Don't commit to public repositories
- Use `.gitignore` to exclude this directory
- Encrypt if storing in cloud
- Be cautious when sharing

## Using the Output

### For Job Applications
1. Use tailored resume and cover letter
2. Reference job analysis for application strategy
3. Review interview prep before interviews
4. Consult negotiation guide when offer comes

### For Career Development
1. Review master profile regularly
2. Update career plan annually
3. Track progress against goals
4. Adjust strategy based on results

### For Professional Branding
1. Implement LinkedIn optimizations
2. Follow content strategy
3. Track profile views and engagement
4. Update as career progresses

## Maintenance

### Regular Updates
- **Weekly**: Review active job applications
- **Monthly**: Update master profile if significant changes
- **Quarterly**: Review career plan progress
- **Annually**: Complete career planning refresh

### Cleanup Schedule
- **After accepting job**: Archive application materials
- **After 6 months**: Review and archive old analyses
- **Annually**: Clean up outdated materials

### Quality Check
Periodically review output for:
- Accuracy and currency
- Relevance to current goals
- Completeness of information
- Organization and accessibility

## Getting the Most Value

### Cross-Reference Materials
- Use job analysis when tailoring resume
- Reference master profile in all applications
- Connect interview prep to job analysis
- Align negotiation strategy with career plan

### Track Success
- Note which strategies worked
- Document successful applications
- Record interview feedback
- Track salary negotiation outcomes

### Continuous Improvement
- Refine prompts based on results
- Update master profile with new achievements
- Adjust strategies based on market feedback
- Learn from both successes and setbacks

## Need Help?

If you're not seeing expected output:
1. Check that you ran the prerequisite prompts
2. Verify the prompt was copied completely
3. Ensure you provided all requested information
4. Review the prompt's "Success Criteria" section
5. Try running the prompt again with more context