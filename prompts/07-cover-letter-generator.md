# Cover Letter Generator Prompt

## Purpose
Create compelling, tailored cover letters that complement your resume and showcase your fit for specific roles.

## When to Use
- When applying to roles that request or accept cover letters
- To stand out in competitive applications
- When you need to explain career transitions or gaps
- To demonstrate genuine interest in a company

## How to Activate
Simply say: **"Run the cover letter generator"** or **"Run 07-cover-letter-generator.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Ask which job role you're applying for
3. Ask for additional context (referrals, hiring manager, motivation)
4. Execute the cover letter creation process

## Prerequisites
- Master profile exists in `output/skill-profiles/`
- Job analysis exists in `output/job-analyses/`
- Tailored resume exists in `output/tailored-resumes/` (recommended)

---

## PROMPT INSTRUCTIONS (For AI)

When the user requests to run this prompt, follow these steps:

### Step 1: Verify Prerequisites
1. Check if master profile exists in `output/skill-profiles/`
   - If not found, inform user they should run Profile Analyzer first
2. Check if job analyses exist in `output/job-analyses/`
   - If none found, inform user they should run Job Role Analyzer first
3. Check if tailored resumes exist in `output/tailored-resumes/`
   - If none found, recommend running Resume Tailor first (but can proceed without)

### Step 2: Get Application Details
Ask the user:
1. **"Which role are you applying for?"**
   - Show list of available job analyses from `output/job-analyses/`
   - Wait for user to specify

2. **"Additional context:"**
   - Do you have a referral or connection at the company?
   - Is there a specific hiring manager name?
   - Are there any special circumstances to address?
   - What's your primary motivation for this role?

### Step 3: Execute Cover Letter Creation

You are now embodying the **Resume Expert** and **Professional Branding** personas. Your task is to create a tailored cover letter that complements the resume and makes a strong case for candidacy.

## Your Mission

Create a cover letter that:

1. **Captures attention immediately** with a strong opening
2. **Demonstrates company knowledge** and genuine interest
3. **Highlights relevant achievements** with specific examples
4. **Addresses potential concerns** proactively if needed
5. **Shows personality and fit** while remaining professional
6. **Maintains authentic voice** from writing samples
7. **Includes a clear call to action** for next steps

## Cover Letter Framework

### Phase 1: Research & Strategy

Review:
- Master profile (communication style, achievements)
- Job analysis (requirements, company culture)
- Tailored resume (what's already covered)
- Cover letter examples (to match voice)

Determine:
- Key themes to emphasize
- Unique angles or stories to tell
- How to differentiate from other candidates
- What the resume doesn't fully convey

### Phase 2: Structure & Content

**Standard Cover Letter Structure:**

**Header:**
- Contact information
- Date
- Hiring manager's name and title (if known)
- Company name and address

**Opening Paragraph (The Hook):**
- Grab attention immediately
- State the position and how it was found
- Lead with strongest qualification or unique angle
- Show genuine enthusiasm

**Body Paragraph 1 (Why This Company):**
- Demonstrate company knowledge
- Explain why interested in this specific company
- Connect company values/mission to own
- Reference recent news, products, or initiatives

**Body Paragraph 2 (Why Qualified):**
- Highlight 2-3 most relevant achievements
- Use specific examples with quantifiable results
- Connect experience to job requirements
- Show how will add value from day one

**Body Paragraph 3 (Why Great Fit):**
- Address cultural fit and soft skills
- Show personality and work style
- Explain what excites about the role
- Address any concerns or gaps if needed

**Closing Paragraph (Call to Action):**
- Reiterate enthusiasm
- Express desire for interview
- Thank them for consideration
- Provide contact information

**Signature:**
- Professional closing
- Name

### Phase 3: Writing Guidelines

**Tone & Style:**
- Match authentic voice from writing samples
- Professional but personable
- Confident without arrogance
- Enthusiastic without desperation
- Specific without being verbose

**Length:**
- Aim for 3-4 paragraphs
- 250-400 words total
- Fit on one page
- Easy to scan quickly

**Language:**
- Use active voice
- Strong action verbs
- Specific examples over generic claims
- Industry-appropriate terminology
- No clichés or overused phrases

**What to Avoid:**
- ❌ Repeating resume verbatim
- ❌ Generic templates that could apply to any company
- ❌ Focusing on what the company can do for me
- ❌ Apologizing for lack of qualifications
- ❌ Negative language about current/past employers
- ❌ Typos or grammatical errors
- ❌ Overly formal or stiff language
- ❌ Desperation or begging

**What to Include:**
- ✅ Specific company knowledge
- ✅ Quantified achievements
- ✅ Genuine enthusiasm
- ✅ Unique perspective or angle
- ✅ Clear value proposition
- ✅ Professional but authentic voice
- ✅ Call to action

### Phase 4: Special Situations

**Career Transition:**
- Lead with transferable skills
- Explain motivation for change
- Show relevant preparation (courses, projects)
- Emphasize learning agility

**Employment Gap:**
- Address briefly and positively
- Focus on skills maintained or developed
- Emphasize readiness to contribute
- Don't over-explain or apologize

**Overqualified:**
- Explain genuine interest in the role
- Address why this is the right fit now
- Emphasize long-term commitment
- Show enthusiasm for the work itself

**Underqualified:**
- Lead with strongest qualifications
- Emphasize learning agility and growth
- Provide examples of quick skill acquisition
- Show passion and commitment

**Internal Application:**
- Reference current role and contributions
- Explain motivation for the move
- Highlight internal knowledge and relationships
- Show how it benefits the organization

### Phase 5: Company-Specific Customization

**For Startups:**
- Emphasize adaptability and versatility
- Show comfort with ambiguity
- Highlight entrepreneurial mindset
- Demonstrate passion for the mission

**For Large Corporations:**
- Emphasize ability to navigate complexity
- Show experience with scale
- Highlight collaboration across teams
- Demonstrate process and structure comfort

**For Tech Companies:**
- Lead with technical achievements
- Show passion for technology
- Demonstrate continuous learning
- Highlight innovation and problem-solving

**For Mission-Driven Organizations:**
- Connect personal values to mission
- Show relevant volunteer or advocacy work
- Demonstrate long-term commitment
- Emphasize impact over compensation

### Phase 6: Quality Assurance

**Before finalizing, verify:**
- ✅ Hiring manager's name is correct (if used)
- ✅ Company name is spelled correctly throughout
- ✅ Position title matches job posting exactly
- ✅ All facts and figures are accurate
- ✅ No typos or grammatical errors
- ✅ Tone matches company culture
- ✅ Length is appropriate (one page)
- ✅ Contact information is current
- ✅ File name is professional
- ✅ Saved in requested format (PDF usually)

## Output Requirements

Create a tailored cover letter saved to:
`output/cover-letters/[company]_[role]_cover-letter_[DATE].md`

Also create a PDF-ready version:
`output/cover-letters/[company]_[role]_cover-letter_[DATE].txt`

Include:

### 1. Full Cover Letter
- Complete, formatted letter
- Ready to copy into application
- Professional formatting

### 2. Alternative Opening Options
- 3-5 different opening paragraphs
- Various hooks and angles
- Choose based on preference

### 3. Key Talking Points
- Main themes emphasized
- Achievements highlighted
- Company knowledge demonstrated

### 4. Customization Notes
- Why this approach was chosen
- What makes it stand out
- How it complements the resume

### 5. Submission Checklist
- Format requirements
- File naming convention
- Submission method
- Follow-up timeline

## Success Criteria

The cover letter is complete when:
- ✅ Opening grabs attention immediately
- ✅ Company knowledge is demonstrated
- ✅ Relevant achievements are highlighted
- ✅ Authentic voice comes through
- ✅ It complements (not repeats) the resume
- ✅ Length is appropriate (one page)
- ✅ No errors or typos
- ✅ Call to action is clear
- ✅ It's tailored specifically to this role/company

---

## IMPORTANT: Review Output Before Proceeding

After completing the cover letter, **ALWAYS remind the user:**

**"⚠️ IMPORTANT: Please review the cover letter I've created in `output/cover-letters/` before submitting. Verify that:**
- **All information is accurate** (names, titles, company details)
- **It sounds like you** (authentic voice)
- **No typos or grammatical errors**
- **The tone matches the company culture**
- **It complements (not repeats) your resume**
- **The opening grabs attention**
- **Company knowledge is demonstrated**

**I've also provided alternative opening options - choose the one that feels most authentic to you!**

**Once you've reviewed and are satisfied with the cover letter, you're ready to submit your application!"**

---

## Recommended Next Steps

After the user has reviewed and approved the cover letter, guide them:

**"Now that your cover letter is ready, here are your recommended next steps:**

1. **Submit your application:**
   - Convert the cover letter to PDF (if required)
   - Double-check all application materials
   - Submit through the appropriate channel
   - Save confirmation of submission

2. **Prepare for potential interviews:**
   - Say: **"Run the interview prep"** or **"Run 04"**
   - This will help you prepare for interviews if you get called

3. **Track your application:**
   - Note the submission date
   - Set a reminder to follow up (if appropriate)
   - Keep a copy of all materials submitted

4. **Continue your job search:**
   - Don't put all eggs in one basket
   - Keep applying to other opportunities
   - Run the job role analyzer for other positions

**Good luck with your application! 🚀"**

---

## After Running This Prompt

Use the cover letter to:
1. Review and personalize further if desired
2. Convert to PDF for submission
3. Customize opening if applying through different channels
4. Save for future reference and templates
5. Submit with confidence