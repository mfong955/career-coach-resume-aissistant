# Quick Start Guide

Welcome to your Career Coach & Resume Assistant! This guide will get you up and running in 30 minutes.

## 📋 Prerequisites

- An AI assistant (Claude, ChatGPT, or similar)
- Your current resume
- 2-3 cover letter examples (if available)
- Any professional documents (certifications, papers, portfolio samples)

## 🚀 Step-by-Step Setup

### Step 1: Organize Your Documents (10 minutes)

Add your professional documents to the appropriate folders:

#### Required:
1. **Current Resume** → [`personal-files/current-resume/`](./personal-files/current-resume/)
   - Add your most recent resume (PDF, DOCX, or MD format)
   - Name it clearly: `resume_2024_current.pdf`

#### Recommended:
2. **Cover Letters** → [`personal-files/cover-letters/`](./personal-files/cover-letters/)
   - Add 2-3 cover letter examples
   - These help the AI learn your writing style

3. **Certifications** → [`personal-files/certifications/`](./personal-files/certifications/)
   - Professional certifications
   - Training certificates
   - Awards and recognition

#### Optional (but valuable):
4. **Research Papers** → [`personal-files/research-papers/`](./personal-files/research-papers/)
   - Published papers or articles
   - Technical blog posts
   - Presentations or white papers

5. **Portfolio Samples** → [`personal-files/portfolio-samples/`](./personal-files/portfolio-samples/)
   - Code samples or GitHub links
   - Project case studies
   - Design work or creative projects

### Step 2: Create Your Master Profile (30-45 minutes)

This is the **most important step** - don't skip it!

1. **Open** [`prompts/01-profile-analyzer.md`](./prompts/01-profile-analyzer.md)

2. **Scroll down** to the line that says "ACTIVATE THIS PROMPT"

3. **Copy everything below that line** (Ctrl+A or Cmd+A to select all, then copy)

4. **Open your AI assistant** (Claude, ChatGPT, etc.)

5. **Paste the prompt** into the conversation

6. **Follow the AI's instructions**:
   - It will list the files it found
   - It may ask clarifying questions
   - Answer honestly and thoroughly
   - Be patient - this takes 30-45 minutes

7. **Review the output**:
   - The AI will create a comprehensive profile in `output/skill-profiles/`
   - This profile becomes the foundation for everything else
   - Review it for accuracy

**✅ Success Check**: You should have a file like `output/skill-profiles/master-profile_2024-01-15.md` with:
- Executive summary of your professional profile
- Comprehensive skills inventory
- Career progression analysis
- Quantified achievements
- Unique value proposition

---

## 🎯 Your First Job Application

Now let's use the system to apply for a job!

### Step 3: Add a Job Description (5 minutes)

1. **Find a job** you want to apply to

2. **Create a new file** in [`job-roles/`](./job-roles/)
   - Name it: `company_role_date.md`
   - Example: `google_senior-engineer_2024-01-15.md`

3. **Use the template** from [`job-roles/EXAMPLE_job-description-template.md`](./job-roles/EXAMPLE_job-description-template.md)

4. **Fill in all sections**:
   - Job posting details
   - Complete job description (don't edit or summarize!)
   - Requirements
   - Responsibilities
   - Company information
   - Your personal notes

### Step 4: Analyze the Job (20-30 minutes)

1. **Open** [`prompts/02-job-role-analyzer.md`](./prompts/02-job-role-analyzer.md)

2. **Copy everything below "ACTIVATE THIS PROMPT"**

3. **Paste into your AI conversation**

4. **Specify the job file** when asked:
   - Example: `google_senior-engineer_2024-01-15.md`

5. **The AI will**:
   - Read your master profile
   - Analyze the job description
   - Research the company independently
   - Compare your profile to typical candidates
   - Provide strategic recommendations

6. **Review the analysis** in `output/job-analyses/`

**✅ Success Check**: You should have a comprehensive analysis including:
- Job requirements breakdown
- Company research and intelligence
- Your competitive positioning
- Skills gap assessment
- Application strategy recommendations

### Step 5: Tailor Your Resume (15-20 minutes)

1. **Open** [`prompts/03-resume-tailor.md`](./prompts/03-resume-tailor.md)

2. **Copy everything below "ACTIVATE THIS PROMPT"**

3. **Paste into your AI conversation**

4. **Specify the job analysis file** when asked

5. **The AI will create**:
   - ATS-optimized plain text resume
   - Human-readable formatted resume
   - Tailoring notes with recommendations

6. **Review and personalize**:
   - Check all facts are accurate
   - Ensure it sounds like you
   - Make any final adjustments

7. **Convert to PDF** for submission (if needed)

**✅ Success Check**: You should have:
- `output/tailored-resumes/company_role_resume_ATS_date.txt`
- `output/tailored-resumes/company_role_resume_date.md`
- `output/tailored-resumes/company_role_tailoring-notes_date.md`

### Step 6: Write a Cover Letter (Optional, 10-15 minutes)

If the application requests a cover letter:

1. **Open** [`prompts/07-cover-letter-generator.md`](./prompts/07-cover-letter-generator.md)

2. **Follow the same process** as above

3. **Review and personalize** the generated cover letter

### Step 7: Submit Your Application! 🎉

You now have:
- ✅ A tailored, ATS-optimized resume
- ✅ A compelling cover letter (if needed)
- ✅ Deep understanding of the role and company
- ✅ Strategic positioning for your application

**Submit with confidence!**

---

## 🎤 When You Get an Interview

### Step 8: Prepare for the Interview (30-45 minutes)

1. **Open** [`prompts/04-interview-prep.md`](./prompts/04-interview-prep.md)

2. **Activate the prompt** (same process as before)

3. **Specify**:
   - The job analysis file
   - Interview format (phone, technical, panel, etc.)
   - Any other details you have

4. **The AI will create**:
   - Likely behavioral questions with STAR answers
   - Technical questions and approaches
   - Questions for you to ask
   - Interview strategy guide

5. **Practice**:
   - Read answers out loud
   - Practice with a friend
   - Refine your stories
   - Build confidence

**✅ Success Check**: You should feel prepared and confident for the interview!

---

## 💰 When You Get an Offer

### Step 9: Negotiate Your Compensation (20-30 minutes)

1. **Open** [`prompts/08-salary-negotiation.md`](./prompts/08-salary-negotiation.md)

2. **Activate the prompt**

3. **Provide offer details**:
   - Base salary offered
   - Equity/stock options
   - Bonus structure
   - Benefits overview

4. **The AI will**:
   - Research market rates
   - Calculate your market value
   - Develop negotiation strategy
   - Provide negotiation scripts

5. **Practice and negotiate** with confidence!

---

## 📚 Additional Workflows

### Career Planning

Use [`prompts/05-career-planning.md`](./prompts/05-career-planning.md) to:
- Set career goals
- Create development roadmap
- Plan career transitions
- Track progress

### LinkedIn Optimization

Use [`prompts/06-linkedin-optimizer.md`](./prompts/06-linkedin-optimizer.md) to:
- Optimize your profile
- Develop content strategy
- Build your network
- Establish thought leadership

---

## 💡 Tips for Success

### Do's ✅
- **Run Profile Analyzer first** - it's the foundation
- **Provide complete information** - more context = better results
- **Review and personalize** - make AI output your own
- **Update regularly** - keep your profile current
- **Follow the workflow** - prompts build on each other
- **Be honest** - the system is designed for truthfulness

### Don'ts ❌
- **Don't skip Profile Analyzer** - everything depends on it
- **Don't edit job descriptions** - analyze them as-is
- **Don't accept AI output blindly** - always review
- **Don't forget to update** - refresh your profile as you grow
- **Don't rush** - quality preparation takes time
- **Don't exaggerate** - honesty is the core principle

---

## 🆘 Troubleshooting

### "The AI didn't create the output file"
- The AI generates content - you may need to save it manually
- Check the `output/` directory for the file
- If missing, copy the AI's response and save it yourself

### "The AI is asking for files I don't have"
- It's okay to not have everything
- Provide what you have
- The AI will work with available information

### "The output seems generic"
- Make sure you ran Profile Analyzer first
- Provide more specific information when asked
- Ask the AI to be more specific or detailed

### "I need to update my profile"
- Just run Profile Analyzer again with updated files
- It will create a new dated version
- Previous versions are preserved for reference

---

## 📈 Measuring Success

Track your progress:
- **Application quality**: Are you applying to better-fit roles?
- **Interview rate**: Are you getting more interviews?
- **Interview performance**: Do you feel more prepared?
- **Offer quality**: Are offers improving?
- **Confidence**: Do you feel more confident in your search?

---

## 🎯 Next Steps

Now that you're set up:

1. **Complete your first application** using the workflow above
2. **Explore other prompts** as needed (career planning, LinkedIn, etc.)
3. **Update your profile** as you gain new skills or complete projects
4. **Track your results** and adjust your approach
5. **Stay consistent** - job search is a marathon, not a sprint

---

## 📞 Need More Help?

- **Check the main README**: [`README.md`](./README.md)
- **Read prompt documentation**: [`prompts/README.md`](./prompts/README.md)
- **Review folder READMEs**: Each directory has usage instructions
- **Try again**: Sometimes rephrasing or providing more context helps

---

## 🎉 You're Ready!

You now have a powerful system for:
- ✅ Understanding your professional value
- ✅ Analyzing job opportunities
- ✅ Creating tailored application materials
- ✅ Preparing for interviews
- ✅ Negotiating offers
- ✅ Planning your career

**Go land that dream job! 🚀**

---

**Remember**: This system helps you present your authentic self effectively. You're in control, and the AI is here to help you shine. Good luck! 🌟