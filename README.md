# sync-work Opencode Skill

An Opencode skill that turns your agent into a project orchestrator (mini-Symphony).

It actively monitors and synchronizes tasks from:
1. **GitHub Issues** (filtering by tags like `todo` or `doing`)
2. **Feishu / Lark Docs** (finding unchecked Todo blocks assigned to Opencode)

When invoked, the agent gathers pending work, reports it to you, and seamlessly transitions from branch creation to implementation, and finally to PR submission and status update.

## Installation

```bash
# Add this skill to your Opencode installation
npx skills add <your-github-username>/sync-work
```

## Usage

In any Opencode session, just type:
```
/sync-work
```
Or simply say: "帮我同步一下任务"

The agent will take over and guide you through your daily tasks!
