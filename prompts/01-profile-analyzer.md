# Profile Analyzer Prompt

## Purpose
This prompt performs a comprehensive deep-dive analysis of your professional profile, creating a detailed skill inventory and career summary that will be referenced in all future resume tailoring and career coaching activities.

## When to Use
- **First time setup**: Run this immediately after adding your documents to `personal-files/`
- **Major updates**: When you gain new skills, complete projects, or earn certifications
- **Career transitions**: When pivoting to a new role or industry
- **Annual review**: Refresh your profile yearly to capture growth

## How to Activate
Simply say: **"Run the profile analyzer"** or **"Run 01-profile-analyzer.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Verify required files exist in `personal-files/`
3. Ask for any missing information
4. Execute the comprehensive analysis

## Prerequisites
The following files should exist in `personal-files/`:
- `personal-files/current-resume/` - Your current resume(s) **(REQUIRED)**
- `personal-files/cover-letters/` - At least 2-3 cover letter examples (optional but recommended)
- `personal-files/research-papers/` - Any papers, articles, or technical writing (optional)
- `personal-files/certifications/` - Professional certifications (optional)
- `personal-files/portfolio-samples/` - Work samples or project descriptions (optional)

**Note**: The AI will verify these prerequisites before starting and ask you to add any critical missing files.

---

## PROMPT INSTRUCTIONS (For AI)

When the user requests to run this prompt, follow these steps:

### Step 1: Verify Prerequisites
Check for files in `personal-files/` directory:
- List all files in `personal-files/current-resume/`
- List all files in `personal-files/cover-letters/`
- List all files in `personal-files/research-papers/`
- List all files in `personal-files/certifications/`
- List all files in `personal-files/portfolio-samples/`

If `current-resume/` is empty, inform the user they must add at least one resume before proceeding.
For other directories, note what's available but proceed if they're empty.

### Step 2: Confirm and Begin
Inform the user what files were found and ask if they'd like to proceed or add more files first.

### Step 3: Execute Analysis

You are now embodying the **Career Coach** and **Resume Expert** personas. Your task is to create a CONCISE yet comprehensive professional profile.

## CRITICAL: Keep It Concise

**Length Target**: 500-800 lines maximum (not 1800+ lines)
**Focus**: Essential information only - avoid repetition and excessive detail
**Principle**: If it doesn't directly help with job applications, interviews, or career decisions, leave it out

## Your Mission

Analyze files in the `personal-files/` directory to create a focused profile with:

1. **Executive Summary** (3-4 paragraphs max)
2. **Key Skills** (organized by category, proficiency levels)
3. **Top 5-7 Achievements** (quantified, with context)
4. **Career Progression** (timeline with key milestones only)
5. **Unique Value Proposition** (3-5 key differentiators)
6. **Communication Style** (brief guidelines)
7. **Development Priorities** (top 3-5 areas)
8. **ATS Keywords** (organized list)

## Analysis Framework

### Phase 1: Document Review
Read ALL files in `personal-files/` including:
- Current resume(s) in `current-resume/`
- Cover letters in `cover-letters/`
- Research papers in `research-papers/`
- Certifications in `certifications/`
- Portfolio samples in `portfolio-samples/`

### Phase 2: Skill Extraction

Create a comprehensive inventory organized by:

**Technical Skills**
- Programming languages (with proficiency level)
- Frameworks and libraries
- Tools and platforms
- Methodologies and practices
- Domain-specific technical knowledge

**Soft Skills**
- Leadership and management
- Communication and collaboration
- Problem-solving approaches
- Adaptability and learning agility
- Emotional intelligence indicators

**Domain Expertise**
- Industry knowledge
- Specialized subject matter expertise
- Cross-functional experience
- Regulatory or compliance knowledge

**Achievements & Impact**
- Quantifiable results (revenue, efficiency, scale, etc.)
- Awards and recognition
- Publications and thought leadership
- Patents or innovations
- Team building and mentorship

### Phase 3: Career Trajectory Analysis

Map career progression:
- **Timeline**: Roles, companies, durations
- **Growth patterns**: Promotions, expanding responsibilities
- **Pivots**: Career transitions and how they were navigated
- **Consistency**: Themes across different roles
- **Trajectory**: Where the career is heading

### Phase 4: Unique Value Proposition

Identify what makes the user stand out:
- **Rare skill combinations**: Unique intersections of expertise
- **Measurable impact**: Biggest wins and contributions
- **Problem-solving approach**: How they tackle challenges
- **Leadership style**: How they influence and guide others
- **Innovation**: Creative solutions or new approaches

### Phase 5: Communication Style Analysis

Understand professional voice:
- **Tone**: Formal, conversational, technical, etc.
- **Structure**: How information is organized
- **Emphasis**: What is highlighted (results, process, collaboration)
- **Language patterns**: Phrases and terminology used
- **Storytelling**: How achievements are presented

### Phase 6: Gap Analysis

Identify areas for development:
- **Missing skills**: For next-level roles
- **Underutilized strengths**: Skills they have but don't emphasize
- **Emerging trends**: Industry skills they should develop
- **Certification opportunities**: Credentials that would strengthen profile

## Output Requirements

Create a CONCISE profile document (500-800 lines max) saved to:
`output/skill-profiles/master-profile-[DATE].md`

**Structure** (in order of importance):

### 1. Executive Summary (3-4 paragraphs)
- Who they are professionally
- Core strengths (top 3-5)
- Career trajectory (brief)
- Unique value proposition

### 2. Top Achievements (5-7 items)
For each achievement:
- What: Brief description
- Impact: Quantified result
- Skills: Key skills demonstrated
- Context: When/where (1 line)

### 3. Technical Skills (organized, concise)
**Format**: Skill Category: skill1, skill2, skill3 (proficiency level)
- Programming & Tools
- ML/AI & Data Science
- Cloud & Infrastructure
- Domain Expertise

### 4. Soft Skills (top 5-7 only)
Brief list with one example each

### 5. Career Timeline (key milestones only)
**Format**: Year | Role | Company | Key Achievement (1 line each)

### 6. Unique Value Proposition (3-5 points)
What makes them stand out - be specific and concise

### 7. Communication Style (brief)
- Tone characteristics (2-3 points)
- Key phrases they use
- Writing patterns

### 8. Development Priorities (top 3-5)
What to focus on next for career growth

### 9. ATS Keywords (organized list)
- Technical keywords
- Soft skills keywords
- Industry terms
- Role-specific terms

### 10. Quick Reference (1 paragraph each)
- For Technical IC roles
- For Leadership roles
- For Cross-functional roles

## Critical Instructions

1. **Be CONCISE**: Avoid repetition, keep descriptions brief
2. **Be SPECIFIC**: Use exact numbers and technologies
3. **Be HONEST**: Only include documented skills and achievements
4. **Be FOCUSED**: Include only information useful for job search
5. **Be ACTIONABLE**: Provide concrete, usable recommendations

**AVOID**:
- ❌ Repeating the same information in multiple sections
- ❌ Excessive detail that won't be used
- ❌ Long explanations when bullet points suffice
- ❌ Creating 20+ subsections when 10 will do
- ❌ Writing 1800+ lines when 600 is sufficient

## Questions to Ask

If you need clarification on:
- Specific projects or achievements
- Technical proficiency levels
- Career goals or target roles
- Industries or companies of interest
- Timeline or urgency for job search

Ask directly before completing the analysis.

## Success Criteria

The profile is complete when:
- ✅ All documents have been thoroughly analyzed
- ✅ Every skill is categorized and rated
- ✅ All achievements are quantified with context
- ✅ Unique value proposition is clearly articulated
- ✅ Communication style is documented with examples
- ✅ Development roadmap is specific and actionable
- ✅ The profile can be used as a reference for all future resume tailoring

---

## IMPORTANT: Review Output Before Proceeding

After completing the analysis, **ALWAYS remind the user:**

**"⚠️ IMPORTANT: Please review the master profile I've created in `output/skill-profiles/` before proceeding to the next step. Verify that:**
- **All information is accurate and complete**
- **Skills and proficiency levels are correct**
- **Achievements are properly quantified**
- **Nothing important is missing**
- **The profile represents you authentically**

**Once you've reviewed and are satisfied with your master profile, you're ready for the next step!"**

---

## Recommended Next Steps

After the user has reviewed and approved their master profile, guide them:

**"Now that your master profile is complete, here are your recommended next steps:**

1. **If you're ready to apply for a job:**
   - Add a job description to the `job-roles/` folder
   - Then say: **"Run the job role analyzer"** or **"Run 02"**
   - This will analyze the job and company to help you understand the opportunity

2. **If you want to optimize your LinkedIn:**
   - Say: **"Run the LinkedIn optimizer"** or **"Run 06"**
   - This will help you create a compelling LinkedIn profile

3. **If you want to plan your career path:**
   - Say: **"Run the career planning"** or **"Run 05"**
   - This will help you set goals and create a development roadmap

**Which would you like to do next?"**

---

## After Running This Prompt

The AI will create a master profile in `output/skill-profiles/`. This profile will be referenced automatically when you run other prompts like:
- Job Role Analyzer
- Resume Tailor
- Interview Prep
- Career Planning

You can update this profile anytime by running this prompt again with updated documents.