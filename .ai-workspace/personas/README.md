# AI Personas Directory

## Overview

This directory contains the specialized AI expert personas that power the Career Coach & Resume Assistant package. Each persona provides deep domain expertise in their specific area.

## Active Personas

The following personas are available for this project:

1. **Career Coach** ([`career-coach.md`](./career-coach.md))
   - Strategic career planning and guidance
   - Career transition support
   - Professional development planning
   - Goal setting and achievement

2. **Resume Expert** ([`resume-expert.md`](./resume-expert.md))
   - Resume writing and optimization
   - ATS optimization
   - Achievement quantification
   - 100% honesty guarantee

3. **Professional Branding** ([`professional-branding.md`](./professional-branding.md))
   - LinkedIn profile optimization
   - Personal brand development
   - Content strategy
   - Network building

4. **Interview Coach** ([`interview-coach.md`](./interview-coach.md))
   - Interview preparation
   - STAR method coaching
   - Question and answer development
   - Confidence building

5. **Industry Analyst** ([`industry-analyst.md`](./industry-analyst.md))
   - Company research
   - Market intelligence
   - Competitive analysis
   - Salary research

## How Personas Work

### Activation
Personas are automatically activated when you use the corresponding prompts in the [`prompts/`](../../prompts/) directory. For example:
- Profile Analyzer activates Career Coach + Resume Expert
- Job Role Analyzer activates Industry Analyst + Career Coach
- Resume Tailor activates Resume Expert + Professional Branding
- Interview Prep activates Interview Coach + Career Coach

### Collaboration
Personas work together seamlessly:
- Career Coach coordinates overall strategy
- Specialized personas provide deep expertise
- All maintain consistent messaging
- Context is shared across personas

### Customization
Each persona file (`.md`) contains:
- Role overview and expertise
- Approach and philosophy
- Key responsibilities
- Communication style
- Collaboration guidelines
- Best practices and frameworks

## Using the Personas

### For Users
You don't need to do anything special - just use the prompts in the [`prompts/`](../../prompts/) directory, and the appropriate personas will be activated automatically.

### For AI Assistants
When a prompt is activated:
1. Read the relevant persona file(s)
2. Embody the persona's expertise and approach
3. Follow the persona's guidelines and principles
4. Collaborate with other personas as needed
5. Maintain consistency across interactions

## Persona Principles

### All Personas Share
- **Honesty First**: Never fabricate or exaggerate
- **User-Centric**: Focus on user's goals and needs
- **Actionable**: Provide specific, implementable advice
- **Professional**: Maintain high standards
- **Supportive**: Build confidence and capability

### Unique Expertise
Each persona brings specialized knowledge:
- Career Coach: Career development theory and practice
- Resume Expert: ATS systems and recruiter psychology
- Professional Branding: LinkedIn algorithms and content strategy
- Interview Coach: Behavioral frameworks and interview techniques
- Industry Analyst: Market research and competitive intelligence

## File Structure

```
.ai-workspace/personas/
├── README.md                    # This file
├── active-personas.json         # Configuration file
├── career-coach.md             # Career Coach persona
├── resume-expert.md            # Resume Expert persona
├── professional-branding.md    # Professional Branding persona
├── interview-coach.md          # Interview Coach persona
└── industry-analyst.md         # Industry Analyst persona
```

## Maintenance

### Adding New Personas
To add a new persona:
1. Create a new `.md` file in this directory
2. Follow the structure of existing personas
3. Update `active-personas.json`
4. Document in this README

### Updating Personas
To update a persona:
1. Edit the relevant `.md` file
2. Maintain consistency with other personas
3. Test with relevant prompts
4. Update documentation if needed

## Notes

- Personas are designed to work with any AI assistant (Claude, ChatGPT, etc.)
- Each persona file is self-contained and comprehensive
- Personas maintain consistency across sessions
- All personas prioritize honesty and authenticity