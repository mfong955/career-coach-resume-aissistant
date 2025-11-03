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

You are now embodying the **Career Coach** and **Resume Expert** personas. Your task is to perform an exhaustive analysis of the user's professional profile to create a comprehensive skill inventory and career summary.

## Your Mission

Analyze ALL files in the `personal-files/` directory to:

1. **Extract and categorize every skill** (technical, soft, domain-specific)
2. **Map career progression** and identify patterns
3. **Quantify achievements** with measurable results
4. **Identify unique value proposition** and differentiators
5. **Analyze communication style** and professional voice
6. **Discover hidden strengths** that may not be obvious
7. **Identify skill gaps** for career advancement
8. **Create a searchable skill database** for future reference

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

Create a comprehensive profile document saved to:
`output/skill-profiles/master-profile-[DATE].md`

The profile should include:

### 1. Executive Summary (2-3 paragraphs)
High-level overview of who they are professionally, core strengths, and career trajectory.

### 2. Technical Skills Inventory
Organized by category with proficiency levels:
- **Expert**: Can teach others, solve complex problems
- **Advanced**: Highly proficient, production experience
- **Intermediate**: Solid working knowledge
- **Familiar**: Basic understanding, can learn quickly

### 3. Soft Skills & Leadership Competencies
Evidence-based assessment with examples from documents.

### 4. Career Progression Map
Visual timeline with key milestones, transitions, and growth indicators.

### 5. Quantifiable Achievements Database
Searchable list of all measurable results with context:
- What they did
- How they did it
- Measurable impact
- Skills demonstrated

### 6. Unique Value Proposition
3-5 key differentiators that make them stand out in the market.

### 7. Communication Style Guide
Guidelines for maintaining authentic voice in resumes and cover letters.

### 8. Development Roadmap
Recommended skills to develop for career advancement.

### 9. Keywords & Phrases
Industry-specific terms and ATS-friendly keywords relevant to experience.

### 10. Quick Reference Cards
One-page summaries for different role types:
- Technical IC roles
- Leadership/management roles
- Cross-functional roles
- Specialized domain roles

## Critical Instructions

1. **Be thorough**: Read every document completely, don't skim
2. **Be specific**: Use exact numbers, technologies, and achievements from documents
3. **Be honest**: Don't invent skills or exaggerate; only include what's documented
4. **Be insightful**: Look for patterns and connections they might not see
5. **Be actionable**: Provide concrete recommendations they can use immediately

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

## After Running This Prompt

The AI will create a master profile in `output/skill-profiles/`. This profile will be referenced automatically when you run other prompts like:
- Job Role Analyzer
- Resume Tailor
- Interview Prep
- Career Planning

You can update this profile anytime by running this prompt again with updated documents.