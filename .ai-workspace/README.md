# AI Workspace Directory

This directory contains all the files that help the AI assistant understand and work on your project effectively.

## Directory Structure

```
.ai-workspace/
├── README.md (this file)
├── session-start.md (AI reads this first each session)
├── context-summary.md (high-level project overview)
├── progress.md (milestones and completion status)
├── session-log.md (detailed interaction history)
├── personas/
│   ├── active-personas.json (which personas are currently active)
│   ├── project-manager.json/.md (planning and coordination)
│   ├── developer.json/.md (implementation)
│   ├── tester.json/.md (quality assurance)
│   └── technical-writer.json/.md (documentation)
└── test-checkpoints/
    └── [milestone-based test logs]
```

## File Purposes

### session-start.md
The AI reads this file first in every session. It provides:
- Quick orientation to the project
- Current phase/milestone
- What to focus on next
- Any blockers or issues

### context-summary.md
High-level project overview including:
- Project goals and purpose
- Key decisions made
- Current architecture/approach
- Important constraints

### progress.md
Tracks project milestones:
- Planned milestones
- Completion status
- Current focus
- Next steps

### session-log.md
Detailed history of interactions:
- What was discussed
- Decisions made
- Changes implemented
- Issues encountered

### personas/
Contains persona definitions that guide the AI's behavior:
- **JSON files**: Structured data (role, expertise, priorities)
- **MD files**: Detailed instructions and guidelines
- **active-personas.json**: Configuration of which personas are active
- **Template includes Project Manager persona** - users create additional personas based on project needs
- **Examples**: For software (Developer, Tester), for writing (Author, Editor), for business (Analyst, Strategist)

### test-checkpoints/
Stores test logs and validation records:
- Created before significant changes
- Documents expected behavior
- Helps with debugging and rollback

## How the AI Uses These Files

1. **Every session starts** by reading `session-start.md`
2. **Context is maintained** through `context-summary.md` and `progress.md`
3. **Personas guide behavior** - the AI embodies the active personas
4. **History is preserved** in `session-log.md`
5. **Testing is systematic** using checkpoints

## Maintenance

- Update `session-start.md` at the end of each session
- Update `progress.md` as milestones are completed
- Add to `session-log.md` after significant interactions
- Update `context-summary.md` when major decisions are made
- Adjust personas as project needs evolve