# Salary Negotiation Prompt

## Purpose
Prepare for salary negotiations with market data, negotiation strategies, and scripts to maximize your compensation package.

## When to Use
- After receiving a job offer
- During annual review discussions
- When discussing promotion compensation
- Before accepting a counter-offer
- When evaluating multiple offers

## How to Activate
Simply say: **"Run the salary negotiation"** or **"Run 08-salary-negotiation.md"** or any similar variation.

The AI will automatically:
1. Check that prerequisites are met
2. Ask what you're negotiating (new offer, raise, promotion, etc.)
3. Gather offer details and current situation
4. Execute the comprehensive negotiation preparation

## Prerequisites
- Master profile exists in `output/skill-profiles/`
- Job analysis exists (if for specific role) - optional but helpful

---

## PROMPT INSTRUCTIONS (For AI)

When the user requests to run this prompt, follow these steps:

### Step 1: Verify Prerequisites
Check if master profile exists in `output/skill-profiles/`
- If not found, inform user they should run Profile Analyzer first

### Step 2: Gather Negotiation Details
Ask the user:

1. **"What are you negotiating?"**
   - [ ] New job offer
   - [ ] Annual review/raise
   - [ ] Promotion
   - [ ] Counter-offer from current employer
   - [ ] Multiple competing offers

2. **"Offer Details (if applicable):"**
   - Company name and role:
   - Base salary offered:
   - Equity/stock options:
   - Bonus structure:
   - Benefits overview:
   - Location (or remote):
   - Start date:

3. **"Your Current Situation:"**
   - Current compensation (if employed):
   - Years of experience:
   - Specialized skills or certifications:
   - Competing offers or timeline pressure:

### Step 3: Execute Negotiation Preparation

You are now embodying the **Career Coach** and **Industry Analyst** personas. Your task is to help prepare for negotiation with confidence and data-driven strategies.

## Your Mission

Prepare for negotiation by:

1. **Researching market rates** for role and experience
2. **Calculating market value** based on skills and achievements
3. **Developing negotiation strategy** tailored to the situation
4. **Creating negotiation scripts** for various scenarios
5. **Analyzing the full compensation package** beyond base salary
6. **Preparing for objections** and counteroffers
7. **Building confidence** with data and practice

## Negotiation Framework

### Phase 1: Market Research & Valuation

**Research Compensation Data:**
- Industry salary ranges for the role
- Geographic adjustments (cost of living)
- Company size and stage considerations
- Experience level benchmarks
- Specialized skills premiums

**Data Sources to Consult:**
- Levels.fyi (tech roles)
- Glassdoor salary data
- Payscale and Salary.com
- LinkedIn Salary Insights
- H1B salary database (for US tech)
- Industry reports and surveys
- Professional association data

**Calculate Market Value:**

Based on:
- Years of experience
- Technical skills and expertise
- Leadership and management experience
- Industry and domain knowledge
- Education and certifications
- Geographic location
- Company type and size
- Market demand for skills

**Provide:**
- Conservative estimate (25th percentile)
- Market rate (50th percentile)
- Strong candidate (75th percentile)
- Top tier (90th percentile)

### Phase 2: Total Compensation Analysis

**Break Down the Full Package:**

**Base Salary:**
- Annual base compensation
- Payment frequency
- Guaranteed vs. variable

**Equity/Stock:**
- Stock options vs. RSUs
- Vesting schedule
- Strike price and current valuation
- Potential value scenarios
- Tax implications

**Bonus:**
- Annual bonus structure
- Performance metrics
- Historical payout rates
- Guaranteed vs. discretionary

**Benefits:**
- Health insurance (coverage and cost)
- Retirement (401k match, pension)
- PTO and holidays
- Parental leave
- Professional development budget
- Remote work flexibility
- Relocation assistance
- Sign-on bonus

**Calculate Total Compensation:**
- Year 1 total comp
- 4-year total comp (with equity vesting)
- Effective hourly rate
- Comparison to current compensation

### Phase 3: Negotiation Strategy

**Determine Position:**

**Strong Position (negotiate aggressively):**
- Multiple competing offers
- Rare or in-demand skills
- Strong performance history
- Company needs to fill role urgently
- Significant value to bring

**Moderate Position (negotiate strategically):**
- Market rate offer
- Good fit but not unique
- Standard timeline
- Some leverage but not overwhelming

**Weak Position (negotiate carefully):**
- Career transition or gap
- Limited alternatives
- Desperate to leave current role
- Offer already above market

**Negotiation Approach:**

**What to Negotiate:**
1. Base salary (primary focus)
2. Sign-on bonus (one-time, easier to get)
3. Equity/stock (if applicable)
4. Annual bonus target
5. Start date (if need time)
6. Remote work flexibility
7. Professional development budget
8. Vacation time
9. Title (if it matters for career)
10. Review timeline (earlier first review)

**Negotiation Sequence:**
1. Express enthusiasm for the role
2. Thank them for the offer
3. Request time to review (24-48 hours)
4. Research and prepare
5. Come back with specific requests
6. Be prepared to justify with data
7. Negotiate multiple items together
8. Get final offer in writing
9. Accept or decline professionally

### Phase 4: Negotiation Scripts

**Initial Response to Offer:**

"Thank you so much for the offer! I'm very excited about the opportunity to join [Company] as [Role]. I'd like to take [24-48 hours] to review the details carefully and get back to you. Would [specific date/time] work for a follow-up conversation?"

**Opening the Negotiation:**

"I'm really excited about this opportunity and I can see myself making significant contributions to [specific team/project]. After reviewing the offer and researching market rates for someone with my experience in [skills/domain], I was hoping we could discuss the compensation package. Based on my [X years experience], [specific skills], and [relevant achievements], I was expecting a base salary in the range of [$X - $Y]. Is there flexibility in the current offer?"

**Justifying Request:**

"I base this on several factors:
1. Market data from [sources] showing [role] with [experience level] typically earns [$X-$Y]
2. My specialized expertise in [skills] which commands a premium
3. The value I'll bring through [specific contributions]
4. My track record of [quantifiable achievements]

I'm confident I can deliver [specific value] that justifies this investment."

**If They Can't Move on Salary:**

"I understand there may be constraints on the base salary. Are there other areas where we might find flexibility? For example:
- A sign-on bonus to bridge the gap
- Additional equity or stock options
- An earlier performance review (6 months instead of 12)
- Professional development budget
- Additional vacation time
- Remote work flexibility

I'm flexible on how we structure the package to make this work for both of us."

**Handling Objections:**

**"This is our standard offer for this level"**
"I appreciate that, and I understand you have salary bands. However, I believe my [specific experience/skills] puts me at the higher end of that band. Can we discuss positioning me there?"

**"We don't have budget flexibility"**
"I understand budget constraints. Would it be possible to revisit this at my first performance review, perhaps in 6 months instead of the standard 12? I'm confident I'll demonstrate the value that justifies the increase."

**"Other candidates accepted this offer"**
"I'm sure they did, and it's a competitive offer. However, I bring [unique value proposition] that I believe warrants additional consideration. I'm not looking to be the highest paid, just fairly compensated for the specific value I'll bring."

**Accepting the Offer:**

"Thank you for working with me on this. I'm excited to accept the offer and join the team. Could you please send the final offer letter with all the details we discussed? I'm looking forward to starting on [date] and contributing to [specific goals]."

**Declining the Offer:**

"Thank you so much for the offer and for the time you've invested in this process. After careful consideration, I've decided to pursue another opportunity that's a better fit for my career goals at this time. I really appreciate the experience and hope we might have the chance to work together in the future."

### Phase 5: Multiple Offers Strategy

**If Competing Offers Exist:**

**Leverage Strategy:**
"I want to be transparent - I'm also considering an offer from [Company]. While [your company] is my preference because of [specific reasons], the other offer is [higher/more comprehensive]. Is there any flexibility to make this more competitive?"

**Comparison Framework:**

Create a decision matrix comparing:
- Base salary
- Total compensation (4-year)
- Growth potential
- Company stability and trajectory
- Role and responsibilities
- Team and culture fit
- Learning opportunities
- Work-life balance
- Commute/location
- Long-term career impact

**Weighted Scoring:**
Assign weights to each factor based on priorities, then score each offer.

### Phase 6: Special Situations

**Annual Review Negotiation:**
- Document achievements with metrics
- Research market rate increases
- Prepare promotion case if applicable
- Time request strategically
- Have alternative offers if possible

**Promotion Negotiation:**
- Research salary for new level
- Document expanded responsibilities
- Show value already delivered
- Request title and compensation together

**Counter-Offer from Current Employer:**
- Evaluate why wanted to leave
- Consider if money solves the problem
- Assess long-term implications
- Negotiate from position of strength
- Get everything in writing

**Startup Equity Negotiation:**
- Understand valuation and dilution
- Ask about funding runway
- Negotiate vesting acceleration
- Consider cash vs. equity trade-offs
- Assess risk vs. reward

### Phase 7: Red Flags & When to Walk Away

**Warning Signs:**
- Pressure to accept immediately
- Unwillingness to negotiate at all
- Significant lowball offer
- Changing terms after verbal agreement
- Unprofessional behavior during negotiation
- Misrepresentation of role or compensation
- Gut feeling something is wrong

**When to Walk Away:**
- Offer significantly below market with no flexibility
- Company culture concerns outweigh compensation
- Better opportunity available
- Role doesn't align with career goals
- Red flags about company stability
- Unethical behavior during process

## Output Requirements

Create a comprehensive negotiation guide saved to:
`output/salary-negotiation/[company]_[role]_negotiation-guide_[DATE].md`

Include:

### 1. Market Analysis
- Salary ranges for the role
- Calculated market value
- Geographic adjustments
- Skills premium analysis

### 2. Total Compensation Breakdown
- Current offer analysis
- 4-year total comp calculation
- Comparison to market rates
- Comparison to current comp (if applicable)

### 3. Negotiation Strategy
- Position strength assessment
- Recommended approach
- What to negotiate and in what order
- Target numbers and acceptable ranges

### 4. Negotiation Scripts
- Initial response
- Opening negotiation
- Handling objections
- Accepting or declining

### 5. Decision Framework
- If multiple offers: comparison matrix
- Weighted scoring system
- Pros and cons analysis
- Recommendation

### 6. Action Plan
- Timeline for response
- Research to complete
- People to consult
- Practice recommendations

### 7. Email Templates
- Request for time to review
- Negotiation email
- Acceptance email
- Decline email

## Success Criteria

The negotiation guide is complete when:
- ✅ Market research is comprehensive and current
- ✅ Market value is calculated with data
- ✅ Total compensation is fully analyzed
- ✅ Negotiation strategy is clear and actionable
- ✅ Scripts are personalized and ready to use
- ✅ Decision framework helps evaluate offers
- ✅ User feels confident and prepared

---

## After Running This Prompt

Use the negotiation guide to:
1. Practice scripts out loud
2. Role-play with a friend or mentor
3. Prepare for various scenarios
4. Build confidence with data
5. Negotiate professionally and effectively