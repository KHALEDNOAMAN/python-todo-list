# Python Todo List - Usage Guide

## Commands
| Command | Description |
|---------|-------------|
| add "task" | Add new task |
| list | Show all tasks |
| done ID | Mark task complete |
| delete ID | Remove task |
| priority ID high | Set priority |
| search "keyword" | Find tasks |
| export | Save to file |

## Priority Levels
| Level | Color | Use When |
|-------|-------|----------|
| High | Red | Urgent deadlines |
| Medium | Yellow | Important, not urgent |
| Low | Green | Can wait |

## Data Storage
Tasks are stored in CSV format for easy portability:
```csv
id,task,priority,status,created_at
1,Write docs,high,pending,2026-09-01
2,Fix bug,medium,done,2026-09-02
```

## Tips
- Review and reprioritize weekly
- Break large tasks into subtasks
- Use search to find old tasks
- Export regularly for backup