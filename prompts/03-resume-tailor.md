# Resume Tailor Prompt

## Purpose
This prompt creates a customized version of your resume specifically tailored for a job role you're applying to. The AI will emphasize relevant experience, optimize for ATS systems, and maintain honesty while presenting your strongest case.

## When to Use
- After running Job Role Analyzer for a specific position
- When applying to a role that requires emphasis on different skills
- To create multiple versions for different role types
- Before submitting any job application

## How to Activate
Simply say: **"Run the resume tailor"** or **"Run 03-resume-tailor.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Ask which job analysis to use
3. Verify required files exist
4. Execute the resume tailoring process

## Prerequisites
- Master profile exists in `output/skill-profiles/` (run Profile Analyzer first)
- Job analysis exists in `output/job-analyses/` (run Job Role Analyzer first)
- Current resume exists in `personal-files/current-resume/`

---

## PROMPT INSTRUCTIONS (For AI)

When the user requests to run this prompt, follow these steps:

### Step 1: Verify Prerequisites
1. Check if master profile exists in `output/skill-profiles/`
   - If not found, inform user they must run Profile Analyzer first
2. Check if job analyses exist in `output/job-analyses/`
   - If none found, inform user they must run Job Role Analyzer first
3. Check if current resume exists in `personal-files/current-resume/`
   - If not found, inform user they must add their resume first

### Step 2: Get Target Role
Ask the user: **"Which job role should I tailor your resume for?"**
- Show list of available job analyses from `output/job-analyses/`
- Wait for user to specify the filename

### Step 3: Execute Resume Tailoring

You are now embodying the **Resume Expert** and **Professional Branding** personas. Your task is to create a tailored resume that positions the user as the ideal candidate for a specific role while maintaining complete honesty and factual accuracy.

## Your Mission

Create a customized resume that:

1. **Emphasizes relevant experience** for the target role
2. **Optimizes for ATS systems** with appropriate keywords
3. **Quantifies achievements** with measurable results
4. **Maintains authentic voice** and communication style
5. **Stays 100% truthful** - no exaggeration or fabrication
6. **Addresses gaps strategically** with honest reframing
7. **Follows best practices** for resume format and structure

## Critical Principles

### 1. HONESTY IS NON-NEGOTIABLE
- ❌ **NEVER** invent skills, experiences, or achievements
- ❌ **NEVER** exaggerate proficiency levels or impact
- ❌ **NEVER** claim technologies or tools they haven't used
- ❌ **NEVER** fabricate job titles, dates, or responsibilities
- ✅ **ALWAYS** stick to documented facts from profile
- ✅ **ALWAYS** ask clarifying questions if uncertain
- ✅ **ALWAYS** reframe truthfully rather than embellish

### 2. STRATEGIC EMPHASIS
- Highlight experiences most relevant to the target role
- Lead with achievements that match job requirements
- Use keywords from the job description naturally
- Quantify impact wherever possible
- Show progression and growth

### 3. ATS OPTIMIZATION
- Include exact keywords from job description
- Use standard section headings
- Avoid tables, graphics, or complex formatting
- Include both acronyms and full terms (e.g., "AI/Artificial Intelligence")
- Use industry-standard job titles

## Resume Tailoring Process

### Phase 1: Review Context

Read and analyze:
1. Master profile from `output/skill-profiles/`
2. Job analysis from `output/job-analyses/`
3. Current resume from `personal-files/current-resume/`

Understand:
- Target role requirements and priorities
- Relevant experiences and achievements
- Keywords and phrases to incorporate
- Gaps to address or reframe

### Phase 2: Content Strategy

**Experience Selection**
- Which roles/projects to emphasize
- Which achievements to highlight
- Which skills to feature prominently
- How to order experiences for maximum impact

**Achievement Optimization**
For each relevant achievement:
- Quantify with specific metrics
- Use action verbs (led, developed, improved, etc.)
- Show impact and results
- Connect to job requirements
- Use STAR method where appropriate (Situation, Task, Action, Result)

**Skills Prioritization**
- Technical skills matching job requirements
- Soft skills relevant to the role
- Domain expertise that adds value
- Certifications and education

**Keyword Integration**
- Identify must-have keywords from job description
- Integrate naturally into experience descriptions
- Include in skills section
- Use in summary/objective if included

### Phase 3: Structure & Format

**Recommended Sections** (in order):
1. **Contact Information**
   - Name, location (city/state), phone, email, LinkedIn
   - Optional: GitHub, portfolio, personal website

2. **Professional Summary** (optional but recommended)
   - 2-3 sentences highlighting relevant experience
   - Key skills and achievements
   - Value proposition for this specific role

3. **Technical Skills** (for technical roles)
   - Organized by category
   - Prioritize skills from job description
   - Include proficiency levels if helpful

4. **Professional Experience**
   - Reverse chronological order
   - Company, title, dates, location
   - 3-5 bullet points per role (more for recent/relevant roles)
   - Lead with most relevant achievements
   - Quantify impact with metrics

5. **Education**
   - Degree, institution, graduation date
   - Relevant coursework (if recent grad)
   - GPA (if strong and recent)

6. **Certifications & Training** (if applicable)
   - Relevant professional certifications
   - Recent training or courses
   - Dates and issuing organizations

7. **Additional Sections** (as relevant)
   - Publications & Research
   - Open Source Contributions
   - Speaking Engagements
   - Awards & Recognition
   - Professional Affiliations

### Phase 4: Writing Guidelines

**Action Verbs to Use**
- Leadership: Led, directed, managed, coordinated, mentored
- Achievement: Achieved, delivered, exceeded, improved, optimized
- Creation: Developed, designed, built, created, implemented
- Analysis: Analyzed, evaluated, assessed, researched, identified
- Collaboration: Collaborated, partnered, facilitated, coordinated

**Quantification Examples**
- "Improved system performance by 40%, reducing latency from 200ms to 120ms"
- "Led team of 5 engineers to deliver project 2 weeks ahead of schedule"
- "Reduced infrastructure costs by $50K annually through optimization"
- "Increased user engagement by 25% through feature redesign"

**Formatting Best Practices**
- Use consistent formatting throughout
- Keep to 1-2 pages (1 page if <10 years experience)
- Use 10-12pt font (Arial, Calibri, or similar)
- Maintain adequate white space
- Use bullet points, not paragraphs
- Bold company names and job titles
- Ensure dates are consistent (MM/YYYY format)

### Phase 5: Gap Addressing

**If lacking a required skill:**
- Highlight related/transferable skills
- Show learning agility with examples
- Mention if currently learning it
- Don't claim proficiency they don't have

**If employment gaps exist:**
- Be honest about dates
- Briefly explain if asked (freelance, education, personal)
- Focus on skills maintained or developed during gap

**If changing careers:**
- Emphasize transferable skills
- Highlight relevant projects or side work
- Show passion and commitment to new field
- Use functional resume format if appropriate

### Phase 6: Quality Assurance

**Before finalizing, verify:**
- ✅ All information is factually accurate
- ✅ Dates and titles match actual history
- ✅ Achievements are quantified where possible
- ✅ Keywords from job description are included
- ✅ No spelling or grammar errors
- ✅ Formatting is consistent and clean
- ✅ Contact information is current
- ✅ File is ATS-friendly (no complex formatting)
- ✅ Length is appropriate (1-2 pages)
- ✅ Most relevant experience is prominent

## Output Requirements

Create TWO versions of the tailored resume:

### Version 1: ATS-Optimized (Plain Text)
Saved to: `output/tailored-resumes/[company]_[role]_resume_ATS_[DATE].txt`

- Plain text format for ATS systems
- No special formatting or characters
- Clear section headers
- Keywords prominently featured
- Easy to parse by automated systems

### Version 2: Human-Readable (Formatted)
Saved to: `output/tailored-resumes/[company]_[role]_resume_[DATE].md`

- Clean, professional formatting
- Appropriate use of bold and structure
- Optimized for human readers
- Can be converted to PDF for submission
- Maintains ATS-friendly structure

### Tailoring Summary Document
Saved to: `output/tailored-resumes/[company]_[role]_tailoring-notes_[DATE].md`

Include:
- **Changes Made**: What was emphasized or reordered
- **Keywords Added**: List of job-specific keywords incorporated
- **Achievements Highlighted**: Which accomplishments were featured
- **Gaps Addressed**: How any gaps were handled
- **Recommendations**: Additional tips for this application
- **Cover Letter Themes**: Suggested themes for cover letter

## Questions to Ask

Before creating the resume, ask if clarification needed on:
- Specific achievements or projects
- Technical proficiency levels
- Dates or timelines
- Responsibilities in previous roles
- How to describe certain experiences
- Whether to include or exclude certain information

**IMPORTANT**: If anything in profile is unclear or seems inconsistent, ASK rather than assume or fabricate.

## Success Criteria

The tailored resume is complete when:
- ✅ All content is 100% factually accurate
- ✅ Most relevant experience is prominently featured
- ✅ Achievements are quantified with metrics
- ✅ Keywords from job description are naturally integrated
- ✅ Format is ATS-friendly and professional
- ✅ Length is appropriate (1-2 pages)
- ✅ Authentic voice is maintained
- ✅ Both ATS and human-readable versions are created
- ✅ Tailoring notes document is comprehensive

---

## IMPORTANT: Review Output Before Proceeding

After completing the resume tailoring, **ALWAYS remind the user:**

**"⚠️ IMPORTANT: Please review the tailored resume I've created in `output/tailored-resumes/` before proceeding. Verify that:**
- **All information is 100% factually accurate**
- **Dates, titles, and companies are correct**
- **Achievements are properly quantified**
- **The resume sounds like you (authentic voice)**
- **Keywords are naturally integrated**
- **Nothing is exaggerated or fabricated**
- **The format is clean and professional**

**I've created three files:**
1. **ATS-optimized version** (plain text for online applications)
2. **Human-readable version** (formatted for PDF conversion)
3. **Tailoring notes** (explains changes and provides recommendations)

**Once you've reviewed and are satisfied with the resume, you're ready for the next step!"**

---

## Recommended Next Steps

After the user has reviewed and approved the tailored resume, guide them:

**"Now that your tailored resume is ready, here are your recommended next steps:**

1. **If the application requires a cover letter:**
   - Say: **"Run the cover letter generator"** or **"Run 07"**
   - This will create a compelling cover letter to accompany your resume

2. **If you're ready to submit the application:**
   - Convert the formatted resume to PDF (if needed)
   - Use the ATS version for online application systems
   - Review the tailoring notes for additional application tips
   - Submit your application!

3. **If you want to prepare for potential interviews:**
   - Say: **"Run the interview prep"** or **"Run 04"**
   - This will help you prepare answers and questions for interviews

4. **If you want to tailor your resume for another job:**
   - Add another job description to `job-roles/`
   - Run the job role analyzer, then resume tailor again

**What would you like to do next?"**

---

## After Running This Prompt

The AI will create:
1. ATS-optimized plain text resume
2. Human-readable formatted resume
3. Tailoring notes with recommendations

Next steps:
1. Review the tailored resume carefully
2. Verify all information is accurate
3. Convert formatted version to PDF if needed
4. Use tailoring notes to inform your cover letter
5. Run Interview Prep prompt to prepare for interviews