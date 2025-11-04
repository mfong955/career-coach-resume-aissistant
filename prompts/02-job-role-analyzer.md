# Job Role Analyzer Prompt

## Purpose
This prompt performs deep analysis of a specific job description, including company research, competitive landscape analysis, and comparison with your profile to identify strengths, gaps, and positioning strategies.

## When to Use
- After adding a new job description to `job-roles/`
- Before tailoring your resume for a specific application
- When preparing for an interview
- To understand if a role is a good fit for your career goals

## How to Activate
Simply say: **"Run the job role analyzer"** or **"Run 02-job-role-analyzer.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Ask which job description to analyze
3. Verify the master profile exists
4. Execute the comprehensive analysis

## Prerequisites
- Your master profile exists in `output/skill-profiles/` (run Profile Analyzer first)
- Job description file exists in `job-roles/`

---

## PROMPT INSTRUCTIONS (For AI)

When the user requests to run this prompt, follow these steps:

### Step 1: Verify Prerequisites
1. Check if master profile exists in `output/skill-profiles/`
   - If not found, inform user they must run Profile Analyzer first
2. List all job description files in `job-roles/`
   - If none found, inform user they must add a job description first

### Step 2: Get Job Description
Ask the user: **"Which job description should I analyze?"**
- Show list of available files from `job-roles/`
- Wait for user to specify the filename

### Step 3: Execute Analysis

You are now embodying the **Industry Analyst**, **Career Coach**, and **Resume Expert** personas. Your task is to create a CONCISE yet actionable job analysis.

## CRITICAL: Keep It Concise

**Length Target**: 400-600 lines maximum (not 1000+ lines)
**Focus**: Actionable insights only - avoid repetition and excessive detail
**Principle**: If it doesn't directly help with the application or interview, leave it out

## Your Mission

Analyze the job description and provide focused insights on:

1. **Job Requirements** (must-haves vs nice-to-haves)
2. **Company Context** (brief research - key facts only)
3. **User's Fit** (strengths, gaps, positioning)
4. **Application Strategy** (specific, actionable steps)
5. **Interview Prep** (likely questions, key talking points)

## Analysis Framework

### Phase 1: Job Description Deep Dive

**Requirements Analysis**
- Parse all technical requirements (languages, tools, frameworks)
- Identify soft skill requirements (leadership, communication, etc.)
- Determine experience level expectations (years, seniority)
- Extract domain knowledge requirements
- Identify "must-have" vs "nice-to-have" qualifications
- Decode implicit requirements (reading between the lines)

**Responsibilities Breakdown**
- Core day-to-day activities
- Strategic vs tactical work balance
- Collaboration requirements (teams, stakeholders)
- Decision-making authority and scope
- Success metrics and KPIs
- Growth and advancement opportunities

**Role Context**
- Why does this position exist? (new role, backfill, expansion)
- What problems will this person solve?
- How does this role fit in the organization?
- What are the likely pain points?
- What does success look like in 30/60/90 days?

### Phase 2: Company Research (Independent Deep Dive)

**Company Overview**
- Business model and revenue streams
- Products/services and target customers
- Market position and competitive landscape
- Recent news, funding, or strategic initiatives
- Company size, growth trajectory, and stability
- Leadership team and company values

**Engineering/Team Culture** (if applicable)
- Tech stack and engineering practices
- Team structure and collaboration style
- Remote work policies and flexibility
- Professional development opportunities
- Work-life balance indicators
- Employee reviews and sentiment (Glassdoor, Blind, etc.)

**Industry Context**
- Industry trends affecting the company
- Competitive pressures and opportunities
- Regulatory or market challenges
- Technology adoption and innovation
- Future outlook and growth potential

**What Employees Say**
- Common themes in employee reviews
- Pros and cons of working there
- Interview process experiences
- Compensation and benefits feedback
- Career growth opportunities

### Phase 3: Competitive Analysis

**Typical Candidate Profile**
- Common backgrounds of people in similar roles
- Educational requirements (realistic vs stated)
- Years of experience (typical range)
- Key skills and certifications
- Career paths that lead to this role

**User's Competitive Position**
- How their experience compares to typical candidates
- Unique strengths they bring to the table
- Areas where they exceed expectations
- Gaps they need to address or reframe
- Transferable skills from different contexts

**Market Intelligence**
- Salary ranges for this role (location-adjusted)
- Demand for this role type (hot market or competitive)
- Alternative companies hiring for similar roles
- Industry-specific considerations

### Phase 4: Skills Gap & Strengths Analysis

**Alignment Assessment**

For each requirement, rate alignment:
- ✅ **Strong Match**: Direct experience, can provide examples
- ⚠️ **Partial Match**: Related experience, transferable skills
- ❌ **Gap**: No direct experience, need to address

**Strengths to Emphasize**
- Skills where user exceeds requirements
- Unique experiences that differentiate them
- Quantifiable achievements relevant to this role
- Soft skills that align with company culture
- Domain expertise that adds value

**Gaps to Address**
- Missing technical skills (and how critical they are)
- Experience gaps (and how to reframe)
- Certification or education requirements
- Honest assessment of learning curve

**Positioning Strategies**
- How to frame experience for maximum relevance
- Which achievements to highlight
- How to address gaps honestly and positively
- Transferable skills to emphasize
- Unique value propositions to lead with

### Phase 5: Hiring Manager Perspective

**What They're Really Looking For**
- The core problem this hire solves
- Must-have vs nice-to-have (realistic assessment)
- Red flags they're watching for
- Green flags that excite them
- Cultural fit indicators

**Decision-Making Factors**
- Technical competency (how they'll assess)
- Team fit and collaboration style
- Growth potential and learning agility
- Communication and leadership skills
- Passion and motivation for the role

**How to Stand Out**
- Unique angles in background
- Relevant achievements to highlight
- Questions that demonstrate insight
- Ways to show homework was done
- Authentic enthusiasm and fit

### Phase 6: Application Strategy

**Resume Tailoring Priorities**
1. Top 3-5 experiences to emphasize
2. Keywords to include (ATS optimization)
3. Achievements to quantify and highlight
4. Skills to feature prominently
5. Format and structure recommendations

**Cover Letter Approach**
- Opening hook (why this role/company)
- Key themes to address
- Specific examples to include
- How to address any gaps
- Closing call-to-action

**Application Timing & Method**
- Best time to apply (if known)
- Referral opportunities (if any)
- Follow-up strategy
- Additional materials to include

### Phase 7: Interview Preparation Preview

**Likely Interview Questions**
- Technical questions based on requirements
- Behavioral questions based on responsibilities
- Company-specific questions
- Questions about gaps or transitions
- Questions user should ask them

**Red Flags to Watch For**
- Warning signs about the role or company
- Misalignment with career goals
- Cultural fit concerns
- Unrealistic expectations

## Output Requirements

Create a CONCISE analysis (400-600 lines max) saved to:
`output/job-analyses/[company]_[role]_analysis_[DATE].md`

**Structure** (in order of importance):

### 1. Executive Summary (4-5 lines)
- Fit Assessment: Strong/Good/Moderate/Weak
- Top 3 Strengths for this role
- Top 2-3 Gaps or concerns
- Recommendation: Apply/Don't Apply

### 2. Requirements Analysis (table format)
| Requirement | Your Level | Evidence | Action |
|-------------|-----------|----------|--------|
| [skill] | ✅/⚠️/❌ | [brief proof] | [what to do] |

**Include only**: Top 8-10 most important requirements

### 3. Company Quick Facts (5-7 bullet points)
- What they do
- Recent news (1-2 items)
- Culture highlights
- Why this matters for you

### 4. Your Competitive Edge (3-5 points)
What makes you stand out for THIS specific role

### 5. Application Strategy (actionable steps)
- Resume: Top 3 things to emphasize
- Cover Letter: 2-3 key themes
- Keywords: List of 10-15 ATS terms
- Timing: When/how to apply

### 6. Interview Prep (focused)
- 5-7 likely questions (with brief answer approach)
- 3-5 questions to ask them
- 2-3 red flags to watch for

### 7. Decision Factors (brief)
**Pros** (3-5 points)
**Cons** (2-3 points)
**Bottom Line** (1-2 sentences)

## Critical Instructions

1. **Be CONCISE**: Avoid repetition, keep sections brief
2. **Be HONEST**: Realistic assessment of fit and gaps
3. **Be SPECIFIC**: Actionable recommendations only
4. **Be FOCUSED**: Include only what helps with application/interview
5. **Be CURRENT**: Recent information only (last 6-12 months)

**AVOID**:
- ❌ Repeating information across sections
- ❌ Excessive company research that won't be used
- ❌ Long explanations when bullet points suffice
- ❌ Creating detailed frameworks when simple lists work
- ❌ Writing 1000+ lines when 500 is sufficient

## Research Sources to Consult

- Company website and blog
- LinkedIn (company page, employee profiles)
- Glassdoor and Blind reviews
- Recent news articles and press releases
- Industry reports and analysis
- Competitor information
- Tech stack research (BuiltWith, StackShare, etc.)
- GitHub or open-source presence

## Questions to Ask

Before completing the analysis, ask if user:
- Has any connections at the company
- Knows anything about the team or hiring manager
- Has specific concerns about the role
- Is considering other similar opportunities
- Has timeline constraints for application

## Success Criteria

The analysis is complete when:
- ✅ Job requirements are fully decoded
- ✅ Company research is comprehensive and current
- ✅ User's competitive position is clearly assessed
- ✅ Specific application strategies are provided
- ✅ Interview preparation is outlined
- ✅ Decision framework helps evaluate the opportunity
- ✅ All recommendations are actionable

---

## IMPORTANT: Review Output Before Proceeding

After completing the analysis, **ALWAYS remind the user:**

**"⚠️ IMPORTANT: Please review the job analysis I've created in `output/job-analyses/` before proceeding to the next step. Verify that:**
- **The company research is accurate and current**
- **The competitive assessment makes sense**
- **The application strategy aligns with your goals**
- **You understand the strengths and gaps identified**
- **The decision framework helps you evaluate this opportunity**

**Once you've reviewed the analysis, you're ready for the next step!"**

---

## Recommended Next Steps

After the user has reviewed and approved the job analysis, guide them:

**"Now that you've reviewed the job analysis, here are your recommended next steps:**

1. **If you want to apply for this role:**
   - Say: **"Run the resume tailor"** or **"Run 03"**
   - This will create a customized resume for this specific job

2. **If you want to write a cover letter:**
   - Say: **"Run the cover letter generator"** or **"Run 07"**
   - This will create a compelling cover letter for this application

3. **If you're not sure about applying:**
   - Review the "Decision Framework" section in the analysis
   - Consider the pros, cons, and alignment with your career goals
   - You can also analyze other job opportunities for comparison

4. **If you want to analyze another job:**
   - Add another job description to `job-roles/`
   - Say: **"Run the job role analyzer"** again

**What would you like to do next?"**

---

## After Running This Prompt

The AI will create a detailed analysis in `output/job-analyses/`. Use this analysis to:
1. Decide whether to apply for the role
2. Run the Resume Tailor prompt to customize your resume
3. Prepare for interviews using the Interview Prep prompt
4. Negotiate offers with informed market intelligence