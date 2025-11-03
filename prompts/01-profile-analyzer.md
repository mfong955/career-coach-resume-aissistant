# Profile Analyzer Prompt

## Purpose
This prompt instructs the AI to perform a comprehensive deep-dive analysis of your professional profile, creating a detailed skill inventory and career summary that will be referenced in all future resume tailoring and career coaching activities.

## When to Use
- **First time setup**: Run this immediately after adding your documents to `personal-files/`
- **Major updates**: When you gain new skills, complete projects, or earn certifications
- **Career transitions**: When pivoting to a new role or industry
- **Annual review**: Refresh your profile yearly to capture growth

## Prerequisites
Before running this prompt, ensure you have added files to:
- `personal-files/current-resume/` - Your current resume(s)
- `personal-files/cover-letters/` - At least 2-3 cover letter examples
- `personal-files/research-papers/` - Any papers, articles, or technical writing
- `personal-files/certifications/` - Professional certifications
- `personal-files/portfolio-samples/` - Work samples or project descriptions

---

## ACTIVATE THIS PROMPT

Copy everything below this line and paste it into your AI conversation:

---

# PROFILE ANALYZER - Deep Dive Analysis

You are now embodying the **Career Coach** and **Resume Expert** personas. Your task is to perform an exhaustive analysis of my professional profile to create a comprehensive skill inventory and career summary.

## Your Mission

Analyze ALL files in the `personal-files/` directory to:

1. **Extract and categorize every skill** (technical, soft, domain-specific)
2. **Map my career progression** and identify patterns
3. **Quantify achievements** with measurable results
4. **Identify my unique value proposition** and differentiators
5. **Analyze my communication style** and professional voice
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

Map my career progression:
- **Timeline**: Roles, companies, durations
- **Growth patterns**: Promotions, expanding responsibilities
- **Pivots**: Career transitions and how I navigated them
- **Consistency**: Themes across different roles
- **Trajectory**: Where my career is heading

### Phase 4: Unique Value Proposition

Identify what makes me stand out:
- **Rare skill combinations**: Unique intersections of expertise
- **Measurable impact**: Biggest wins and contributions
- **Problem-solving approach**: How I tackle challenges
- **Leadership style**: How I influence and guide others
- **Innovation**: Creative solutions or new approaches

### Phase 5: Communication Style Analysis

Understand my professional voice:
- **Tone**: Formal, conversational, technical, etc.
- **Structure**: How I organize information
- **Emphasis**: What I highlight (results, process, collaboration)
- **Language patterns**: Phrases and terminology I use
- **Storytelling**: How I present achievements

### Phase 6: Gap Analysis

Identify areas for development:
- **Missing skills**: For next-level roles
- **Underutilized strengths**: Skills I have but don't emphasize
- **Emerging trends**: Industry skills I should develop
- **Certification opportunities**: Credentials that would strengthen my profile

## Output Requirements

Create a comprehensive profile document saved to:
`output/skill-profiles/master-profile-[DATE].md`

The profile should include:

### 1. Executive Summary (2-3 paragraphs)
High-level overview of who I am professionally, my core strengths, and career trajectory.

### 2. Technical Skills Inventory
Organized by category with proficiency levels:
- **Expert**: Can teach others, solve complex problems
- **Advanced**: Highly proficient, production experience
- **Intermediate**: Solid working knowledge
- **Familiar**: Basic understanding, can learn quickly

### 3. Soft Skills & Leadership Competencies
Evidence-based assessment with examples from my documents.

### 4. Career Progression Map
Visual timeline with key milestones, transitions, and growth indicators.

### 5. Quantifiable Achievements Database
Searchable list of all measurable results with context:
- What I did
- How I did it
- Measurable impact
- Skills demonstrated

### 6. Unique Value Proposition
3-5 key differentiators that make me stand out in the market.

### 7. Communication Style Guide
Guidelines for maintaining my authentic voice in resumes and cover letters.

### 8. Development Roadmap
Recommended skills to develop for career advancement.

### 9. Keywords & Phrases
Industry-specific terms and ATS-friendly keywords relevant to my experience.

### 10. Quick Reference Cards
One-page summaries for different role types:
- Technical IC roles
- Leadership/management roles
- Cross-functional roles
- Specialized domain roles

## Critical Instructions

1. **Be thorough**: Read every document completely, don't skim
2. **Be specific**: Use exact numbers, technologies, and achievements from my documents
3. **Be honest**: Don't invent skills or exaggerate; only include what's documented
4. **Be insightful**: Look for patterns and connections I might not see
5. **Be actionable**: Provide concrete recommendations I can use immediately

## Questions to Ask Me

If you need clarification on:
- Specific projects or achievements
- Technical proficiency levels
- Career goals or target roles
- Industries or companies of interest
- Timeline or urgency for job search

Ask me directly before completing the analysis.

## Success Criteria

The profile is complete when:
- ✅ All documents have been thoroughly analyzed
- ✅ Every skill is categorized and rated
- ✅ All achievements are quantified with context
- ✅ My unique value proposition is clearly articulated
- ✅ Communication style is documented with examples
- ✅ Development roadmap is specific and actionable
- ✅ The profile can be used as a reference for all future resume tailoring

## Begin Analysis

Start by:
1. Listing all files you found in `personal-files/`
2. Confirming you have everything needed
3. Asking any clarifying questions
4. Then proceed with the comprehensive analysis

Remember: This profile is the foundation for all future career coaching and resume tailoring. Take your time and be thorough.

---

## After Running This Prompt

The AI will create a master profile in `output/skill-profiles/`. This profile will be referenced automatically when you run other prompts like:
- Job Role Analyzer
- Resume Tailor
- Interview Prep
- Career Planning

You can update this profile anytime by running this prompt again with updated documents.