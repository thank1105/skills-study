# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a learning and documentation project for Claude Code skills. It contains:
- **docs/Git操作手册.md** - Git workflow guide for the team
- **docs/skills使用手册.md** - Reference guide for available Claude Code skills and how to trigger them
- **.agents/skills/** - Installed skills directory (e.g., weather skill)

## Repository Information

- **Repository**: https://github.com/thank1105/skills-study.git
- **Main Branch**: main
- **Owner**: thank1105

## Common Tasks

### Managing Skills

Install a new skill:
```bash
npx skills add <package-url> --skill <skill-name>
```

List installed skills:
```bash
npx skills list
```

Remove a skill:
```bash
npx skills remove <skill-name>
```

Search for skills:
```bash
npx skills find <query>
```

### Git Workflow

Commit and push changes:
```bash
git add .
git commit -m "your message"
git push origin main
```

Check status and changes:
```bash
git status
git diff
```

View commit history:
```bash
git log --oneline
```

## Documentation Maintenance

When updating documentation:
1. Keep the skills使用手册.md in sync with newly installed skills
2. Update Git操作手册.md if workflow changes
3. Commit documentation changes with clear messages

## Key Skills Available

- **find-skills** - Discover and install new agent skills
- **skill-creator** - Create, modify, and optimize skills
- **brainstorming** - Explore requirements before implementation
- **code-review** - Review code changes
- **verify** - Test changes in the real app

See docs/skills使用手册.md for the complete list and usage examples.
