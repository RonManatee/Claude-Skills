# Claude Skills — Skill Registry

This file documents all available skills in this repository. Each skill lives in its own folder with a `Skill.md` file containing the full prompt, trigger conditions, methodology, and output format.

---

## Available Skills

| Skill | Description | Folder |
|-------|-------------|--------|
| [Positioning Consultant Prompt](./Positioning%20Consultant%20Prompt/Skill.md) | Strategic market positioning, value proposition development, and messaging framework creation | `./Positioning Consultant Prompt/` |

---

## How to Add a New Skill

1. Create a new folder: `./Your Skill Name/`
2. Add a `Skill.md` file inside it using the template below
3. Register it in the table above
4. `git add .`, `git commit`, and `git push`

---

## Skill Template

```markdown
# Skill Name

## Overview
Brief description of what this skill does and when to use it.

## Trigger Conditions
List of phrases, topics, or situations that should activate this skill.

## Skill Prompt
The full system prompt / instructions for Claude when this skill is active.

### Phase 1: ...
### Phase 2: ...

## Output Format
Describe the expected structure and format of the skill's output.
```
