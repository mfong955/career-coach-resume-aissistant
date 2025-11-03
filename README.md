# AI Project Assistant Template

This is a lightweight template for AI-assisted projects. It provides a structured workspace that helps AI assistants understand your project, maintain context across sessions, and work as a coordinated team of specialized personas.

## Quick Start

1. **Copy this template** to your new project directory
2. **Open your AI assistant** (Claude, ChatGPT, etc.) in VS Code or your preferred environment
3. **Provide the AI with the core instructions** from `AI_PROJECT_ASSISTANT_PROMPT.md`
4. **Let the AI read** the `.ai-workspace/` files to get oriented
5. **Describe your project** when prompted

The AI will then:
- Ask clarifying questions about your goals
- Propose a team of personas suited to your project
- Create a project plan with testable milestones
- Begin working with you incrementally

## How This Template Works

### The `.ai-workspace/` Directory
This is the AI's reference library. It contains:
- **Project context** (goals, progress, history)
- **Persona definitions** (specialized roles the AI embodies)
- **Session continuity** (memory between conversations)
- **Test checkpoints** (for incremental validation)

### Personas
Instead of re-explaining what you need every time, this template uses persistent **persona profiles**. The AI reads these to understand:
- What role(s) it should play
- What expertise to apply
- How to communicate with you
- What the project priorities are

The template includes a **Project Manager** persona by default. You create additional personas based on your project type:
- **Software Projects**: Developer, Tester, Technical Writer, DevOps Engineer
- **Writing Projects**: Author, Editor, Researcher, Fact Checker
- **Creative Projects**: Designer, Copywriter, Art Director, Brand Strategist
- **Business Projects**: Analyst, Strategist, Financial Planner, Market Researcher
- **Academic Projects**: Researcher, Statistician, Peer Reviewer, Academic Writer

### Incremental Progress
The AI breaks work into small, testable chunks. After each change:
- You're told what changed
- You're given instructions on how to test it
- You validate before moving forward

This prevents the "too many changes at once" problem where debugging becomes impossible.

## File Structure

```
your-project/
├── README.md (this file - customize for your project)
├── AI_PROJECT_ASSISTANT_PROMPT.md (core AI instructions)
├── .ai-workspace/
│   ├── README.md (explains workspace structure)
│   ├── session-start.md (AI reads this first each session)
│   ├── context-summary.md (high-level project overview)
│   ├── progress.md (milestones and status)
│   ├── session-log.md (interaction history)
│   ├── personas/
│   │   ├── active-personas.json
│   │   ├── project-manager.json/.md (included)
│   │   └── [your custom personas].json/.md (create based on project needs)
│   └── test-checkpoints/
│       └── [milestone test logs]
└── [your project files]
```

## Customization

- **Adjust personas** to match your project type
- **Modify the README** to describe your specific project
- **Update communication preferences** in persona files
- **Adapt the workflow** in `session-start.md` as needed

## Philosophy

This template solves the problem of repeatedly setting up AI collaborators for each project. Instead of explaining your preferences and project context every time:

1. The AI reads persistent files to understand the project
2. Personas provide consistent expertise across sessions
3. Progress tracking maintains continuity
4. Small increments keep work debuggable

## Getting Help

If the AI seems confused or off-track:
1. Ask it to re-read `.ai-workspace/session-start.md`
2. Check if personas need updating
3. Verify that progress tracking is current
4. Update `context-summary.md` if the project direction has changed