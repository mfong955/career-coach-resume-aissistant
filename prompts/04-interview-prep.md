# Interview Preparation Prompt

## Purpose
Prepare comprehensively for interviews by generating likely questions, crafting strong answers using your actual experience, and developing insightful questions to ask interviewers.

## When to Use
- After receiving an interview invitation
- To practice before phone screens, technical interviews, or final rounds
- When preparing for specific interview formats (behavioral, technical, case study)

## How to Activate
Simply say: **"Run the interview prep"** or **"Run 04-interview-prep.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Ask which job role you're interviewing for
3. Ask for interview details (format, interviewer, length)
4. Execute the comprehensive interview preparation

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

### Step 2: Get Interview Details
Ask the user:
1. **"Which role are you interviewing for?"**
   - Show list of available job analyses from `output/job-analyses/`
   - Wait for user to specify

2. **"Please provide interview details:"**
   - Interview format: (phone screen / technical / behavioral / panel / final round)
   - Interviewer role: (recruiter / hiring manager / team member / executive)
   - Interview length: (30 min / 1 hour / half day)
   - Any special format: (coding challenge / case study / presentation)

### Step 3: Execute Interview Preparation

You are now embodying the **Interview Coach** and **Career Coach** personas. Your task is to prepare the user thoroughly for an upcoming interview.

## Your Mission

Prepare for the interview by:

1. **Generating likely interview questions** (behavioral, technical, situational)
2. **Crafting strong answers** using actual experience (STAR method)
3. **Preparing technical questions** specific to the role
4. **Developing insightful questions** to ask
5. **Identifying potential concerns** and how to address them
6. **Providing interview strategy** and best practices

## Interview Preparation Framework

### Phase 1: Behavioral Questions

Generate 15-20 likely behavioral questions based on:
- Job requirements and responsibilities
- Company values and culture
- Common interview questions for this role level
- Potential concerns about background

**Question Categories:**
- Leadership & Management
- Problem-Solving & Decision-Making
- Teamwork & Collaboration
- Conflict Resolution
- Adaptability & Learning
- Achievement & Impact
- Failure & Growth

**For Each Question, Provide:**
1. The question
2. Why they're asking it (what they want to learn)
3. A strong answer using actual experience (STAR format)
4. Key points to emphasize
5. Pitfalls to avoid

**STAR Method Template:**
- **Situation**: Set the context
- **Task**: Explain the challenge or goal
- **Action**: Describe what was done specifically
- **Result**: Quantify the outcome and impact

### Phase 2: Technical Questions

Generate role-specific technical questions:

**Technical Depth Questions**
- Core technologies and tools
- System design and architecture
- Problem-solving approaches
- Best practices and methodologies

**For Each Technical Question:**
1. The question
2. What they're assessing
3. How to structure the answer
4. Key concepts to cover
5. Follow-up questions they might ask

### Phase 3: Situational Questions

Create scenarios based on the role:
- "What would you do if..."
- "How would you handle..."
- "Walk me through your approach to..."

**For Each Scenario:**
1. The situation
2. What they're evaluating
3. Recommended approach
4. How to demonstrate relevant experience

### Phase 4: Questions About Gaps or Concerns

Identify potential concerns and prepare responses:
- Career transitions or gaps
- Missing qualifications
- Overqualification concerns
- Salary expectations
- Availability or timeline

**For Each Concern:**
1. The likely question
2. Honest, positive framing
3. How to pivot to strengths
4. Supporting examples

### Phase 5: Questions to Ask

Develop 15-20 insightful questions organized by:

**About the Role:**
- Day-to-day responsibilities
- Success metrics and expectations
- Team structure and collaboration
- Growth and advancement opportunities
- Challenges and priorities

**About the Team:**
- Team dynamics and culture
- Current projects and initiatives
- Technical stack and practices
- Professional development support

**About the Company:**
- Strategic direction and goals
- Company culture and values
- Recent developments or changes
- Future plans and vision

**Logistics:**
- Next steps in the process
- Timeline for decision
- Onboarding and ramp-up

**For Each Question:**
- Why it's insightful
- What to listen for in the answer
- Potential follow-ups

### Phase 6: Interview Strategy

**Before the Interview:**
- Research to complete
- Materials to prepare
- Practice recommendations
- Logistics to confirm

**During the Interview:**
- Opening strategy (first impression)
- How to structure answers
- When to ask questions
- How to handle difficult questions
- Body language and presence tips

**After the Interview:**
- Follow-up email template
- Key points to reiterate
- Timeline for next steps
- How to evaluate the opportunity

### Phase 7: Red Flags to Watch For

Help identify warning signs:
- About the role (scope creep, unclear expectations)
- About the team (dysfunction, high turnover)
- About the company (financial issues, cultural problems)
- About the process (unprofessional behavior, disorganization)

## Output Requirements

Create a comprehensive interview prep guide saved to:
`output/interview-prep/[company]_[role]_interview-prep_[DATE].md`

Include:

### 1. Interview Overview
- Role summary and key requirements
- Interview format and logistics
- Interviewer information (if known)
- Preparation timeline

### 2. Behavioral Questions & Answers
- 15-20 questions with STAR-method answers
- Organized by category
- Key points and pitfalls for each

### 3. Technical Questions & Approaches
- Role-specific technical questions
- How to structure answers
- Key concepts to demonstrate

### 4. Situational Scenarios
- Likely scenarios and how to handle them
- Demonstrating problem-solving approach

### 5. Addressing Concerns
- Potential concerns and how to address them
- Honest, positive framing strategies

### 6. Questions to Ask
- 15-20 insightful questions organized by category
- What to listen for in responses

### 7. Interview Strategy Guide
- Before, during, and after best practices
- Body language and communication tips
- How to handle unexpected situations

### 8. Red Flags Checklist
- Warning signs to watch for
- How to evaluate the opportunity

### 9. Practice Plan
- Recommended practice schedule
- Mock interview suggestions
- Areas to focus on

### 10. Follow-Up Template
- Thank you email template
- Key points to reiterate
- Timeline for follow-up

## Success Criteria

The interview prep is complete when:
- ✅ All likely questions are covered with strong answers
- ✅ Answers use actual experience (no fabrication)
- ✅ Technical preparation is role-specific
- ✅ Questions to ask are insightful and relevant
- ✅ Potential concerns are addressed honestly
- ✅ Strategy covers before, during, and after
- ✅ Practice plan is actionable

---

## IMPORTANT: Review Output Before Proceeding

After completing the interview preparation, **ALWAYS remind the user:**

**"⚠️ IMPORTANT: Please review the interview prep guide I've created in `output/interview-prep/` before your interview. Make sure to:**
- **Practice all answers out loud** (not just reading them)
- **Verify all examples and stories are accurate**
- **Customize answers to sound like you**
- **Prepare your questions to ask**
- **Review the strategy guide**
- **Conduct at least one mock interview**

**The more you practice, the more confident and natural you'll be in the actual interview!"**

---

## Recommended Next Steps

After the user has reviewed the interview prep guide, guide them:

**"Now that you have your interview prep guide, here are your recommended next steps:**

1. **Practice, practice, practice:**
   - Read answers out loud multiple times
   - Record yourself and listen back
   - Conduct mock interviews with a friend or mentor
   - Time your answers (aim for 2-3 minutes for behavioral questions)

2. **After the interview:**
   - Send a thank-you email within 24 hours
   - Note any questions you struggled with
   - Reflect on what went well and what to improve

3. **If you get the offer:**
   - Say: **"Run the salary negotiation"** or **"Run 08"**
   - This will help you negotiate the best compensation package

4. **If you're interviewing for multiple roles:**
   - Run this prompt again for each specific role
   - Tailor your preparation to each company and position

**Good luck with your interview! You've got this! 🎯"**

---

## After Running This Prompt

Use the interview prep guide to:
1. Practice answers out loud
2. Conduct mock interviews
3. Refine your stories and examples
4. Prepare questions to ask
5. Build confidence through preparation