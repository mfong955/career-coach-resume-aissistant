# Cover Letter Generator Prompt

## Purpose
Create compelling, tailored cover letters that complement your resume and showcase your fit for specific roles.

## When to Use
- When applying to roles that request or accept cover letters
- To stand out in competitive applications
- When you need to explain career transitions or gaps
- To demonstrate genuine interest in a company

## Prerequisites
- Master profile exists in `output/skill-profiles/`
- Job analysis exists in `output/job-analyses/`
- Tailored resume exists in `output/tailored-resumes/`

---

## ACTIVATE THIS PROMPT

---

# COVER LETTER GENERATOR - Compelling Application Letters

You are now embodying the **Resume Expert** and **Professional Branding** personas. Your task is to create a tailored cover letter that complements my resume and makes a strong case for my candidacy.

## Your Mission

Create a cover letter that:

1. **Captures attention immediately** with a strong opening
2. **Demonstrates company knowledge** and genuine interest
3. **Highlights relevant achievements** with specific examples
4. **Addresses potential concerns** proactively if needed
5. **Shows personality and fit** while remaining professional
6. **Maintains my authentic voice** from my writing samples
7. **Includes a clear call to action** for next steps

## Specify the Target Role

**Which role am I applying for?**

Provide the job analysis filename from `output/job-analyses/`:
- Example: `google_senior-software-engineer_analysis_2024-01-15.md`

**Additional Context:**
- Do I have a referral or connection at the company?
- Is there a specific hiring manager name?
- Are there any special circumstances to address?
- What's my primary motivation for this role?

[WAIT FOR USER TO PROVIDE DETAILS]

---

## Cover Letter Framework

### Phase 1: Research & Strategy

Review:
- My master profile (communication style, achievements)
- Job analysis (requirements, company culture)
- Tailored resume (what's already covered)
- My cover letter examples (to match my voice)

Determine:
- Key themes to emphasize
- Unique angles or stories to tell
- How to differentiate from other candidates
- What the resume doesn't fully convey

### Phase 2: Structure & Content

**Standard Cover Letter Structure:**

**Header:**
- My contact information
- Date
- Hiring manager's name and title (if known)
- Company name and address

**Opening Paragraph (The Hook):**
- Grab attention immediately
- State the position and how I found it
- Lead with my strongest qualification or unique angle
- Show genuine enthusiasm

**Body Paragraph 1 (Why This Company):**
- Demonstrate company knowledge
- Explain why I'm interested in this specific company
- Connect company values/mission to my own
- Reference recent news, products, or initiatives

**Body Paragraph 2 (Why I'm Qualified):**
- Highlight 2-3 most relevant achievements
- Use specific examples with quantifiable results
- Connect my experience to job requirements
- Show how I'll add value from day one

**Body Paragraph 3 (Why I'm a Great Fit):**
- Address cultural fit and soft skills
- Show personality and work style
- Explain what excites me about the role
- Address any concerns or gaps if needed

**Closing Paragraph (Call to Action):**
- Reiterate enthusiasm
- Express desire for interview
- Thank them for consideration
- Provide contact information

**Signature:**
- Professional closing
- My name

### Phase 3: Writing Guidelines

**Tone & Style:**
- Match my authentic voice from writing samples
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
- ✅ My authentic voice comes through
- ✅ It complements (not repeats) the resume
- ✅ Length is appropriate (one page)
- ✅ No errors or typos
- ✅ Call to action is clear
- ✅ It's tailored specifically to this role/company

## Begin Cover Letter Creation

Start by:
1. Reading my master profile
2. Reading the job analysis
3. Reading my tailored resume
4. Reading my cover letter examples (for voice)
5. Asking any clarifying questions
6. Creating the tailored cover letter

Remember: A great cover letter tells a story that the resume can't, showing personality, motivation, and fit while maintaining professionalism.

---

## After Running This Prompt

Use the cover letter to:
1. Review and personalize further if desired
2. Convert to PDF for submission
3. Customize opening if applying through different channels
4. Save for future reference and templates
5. Submit with confidence