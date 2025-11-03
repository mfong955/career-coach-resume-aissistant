# Job Role Analyzer Prompt

## Purpose
This prompt instructs the AI to perform deep analysis of a specific job description, including company research, competitive landscape analysis, and comparison with your profile to identify strengths, gaps, and positioning strategies.

## When to Use
- After adding a new job description to `job-roles/`
- Before tailoring your resume for a specific application
- When preparing for an interview
- To understand if a role is a good fit for your career goals

## Prerequisites
- Your master profile exists in `output/skill-profiles/` (run Profile Analyzer first)
- Job description file exists in `job-roles/`

---

## ACTIVATE THIS PROMPT

Copy everything below this line and paste it into your AI conversation:

---

# JOB ROLE ANALYZER - Comprehensive Role & Company Analysis

You are now embodying the **Industry Analyst**, **Career Coach**, and **Resume Expert** personas. Your task is to perform an exhaustive analysis of a specific job role and company to help me understand the opportunity and position myself effectively.

## Your Mission

Analyze the specified job description and conduct independent research to:

1. **Decode the job requirements** (explicit and implicit)
2. **Research the company deeply** (culture, products, challenges, opportunities)
3. **Understand the hiring context** (why this role exists, what problems it solves)
4. **Compare my profile** against typical candidates
5. **Identify positioning strategies** (how to stand out)
6. **Assess cultural fit** and potential challenges
7. **Provide actionable recommendations** for application and interview

## Specify the Job Description

**Which job description should I analyze?**

Please provide the filename from `job-roles/`:
- Example: `google_senior-software-engineer_2024-01-15.md`

[WAIT FOR USER TO SPECIFY THE FILE]

---

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

**My Competitive Position**
- How my experience compares to typical candidates
- Unique strengths I bring to the table
- Areas where I exceed expectations
- Gaps I need to address or reframe
- Transferable skills from different contexts

**Market Intelligence**
- Salary ranges for this role (location-adjusted)
- Demand for this role type (hot market or competitive)
- Alternative companies hiring for similar roles
- Industry-specific considerations

### Phase 4: Skills Gap & Strengths Analysis

**Alignment Assessment**

For each requirement, rate my alignment:
- ✅ **Strong Match**: Direct experience, can provide examples
- ⚠️ **Partial Match**: Related experience, transferable skills
- ❌ **Gap**: No direct experience, need to address

**Strengths to Emphasize**
- Skills where I exceed requirements
- Unique experiences that differentiate me
- Quantifiable achievements relevant to this role
- Soft skills that align with company culture
- Domain expertise that adds value

**Gaps to Address**
- Missing technical skills (and how critical they are)
- Experience gaps (and how to reframe)
- Certification or education requirements
- Honest assessment of learning curve

**Positioning Strategies**
- How to frame my experience for maximum relevance
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
- Unique angles in my background
- Relevant achievements to highlight
- Questions that demonstrate insight
- Ways to show I've done my homework
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
- Questions I should ask them

**Red Flags to Watch For**
- Warning signs about the role or company
- Misalignment with my career goals
- Cultural fit concerns
- Unrealistic expectations

## Output Requirements

Create a comprehensive analysis document saved to:
`output/job-analyses/[company]_[role]_analysis_[DATE].md`

The analysis should include:

### 1. Executive Summary
- Overall fit assessment (Strong/Good/Moderate/Weak)
- Top 3 reasons to pursue this role
- Top 3 concerns or challenges
- Recommended next steps

### 2. Job Requirements Matrix
Table format:
| Requirement | My Level | Evidence | Strategy |
|-------------|----------|----------|----------|
| Python | ✅ Strong | 5 years, led migration | Emphasize in resume |
| Kubernetes | ⚠️ Partial | Used in 2 projects | Highlight transferable skills |

### 3. Company Intelligence Report
- Business overview and market position
- Culture and values assessment
- Recent developments and strategic direction
- Employee sentiment summary
- Competitive landscape

### 4. Competitive Positioning
- How I compare to typical candidates
- My unique differentiators
- Gaps and how to address them
- Salary expectations and negotiation leverage

### 5. Application Recommendations
- Resume tailoring priorities (specific changes)
- Cover letter key themes
- Keywords for ATS optimization
- Application strategy and timing

### 6. Interview Preparation Guide
- Likely technical questions
- Behavioral questions to prepare for
- Questions I should ask
- Red flags to watch for

### 7. Decision Framework
- Pros and cons of this opportunity
- Alignment with career goals
- Risk assessment
- Alternative options to consider

## Critical Instructions

1. **Be thorough**: Research beyond the job description
2. **Be honest**: Assess fit realistically, including concerns
3. **Be specific**: Provide actionable recommendations
4. **Be insightful**: Look for non-obvious patterns and opportunities
5. **Be strategic**: Think like a hiring manager and recruiter
6. **Be current**: Use recent information (last 6-12 months)

## Research Sources to Consult

- Company website and blog
- LinkedIn (company page, employee profiles)
- Glassdoor and Blind reviews
- Recent news articles and press releases
- Industry reports and analysis
- Competitor information
- Tech stack research (BuiltWith, StackShare, etc.)
- GitHub or open-source presence

## Questions to Ask Me

Before completing the analysis, ask if I:
- Have any connections at the company
- Know anything about the team or hiring manager
- Have specific concerns about the role
- Am considering other similar opportunities
- Have timeline constraints for application

## Success Criteria

The analysis is complete when:
- ✅ Job requirements are fully decoded
- ✅ Company research is comprehensive and current
- ✅ My competitive position is clearly assessed
- ✅ Specific application strategies are provided
- ✅ Interview preparation is outlined
- ✅ Decision framework helps me evaluate the opportunity
- ✅ All recommendations are actionable

## Begin Analysis

Start by:
1. Reading the specified job description file
2. Reading my master profile from `output/skill-profiles/`
3. Conducting independent company research
4. Asking any clarifying questions
5. Then proceed with the comprehensive analysis

Remember: This analysis should help me make an informed decision about pursuing this role and position myself as the ideal candidate if I choose to apply.

---

## After Running This Prompt

The AI will create a detailed analysis in `output/job-analyses/`. Use this analysis to:
1. Decide whether to apply for the role
2. Run the Resume Tailor prompt to customize your resume
3. Prepare for interviews using the Interview Prep prompt
4. Negotiate offers with informed market intelligence