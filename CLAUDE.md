# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a Claude Code configuration and setup repository designed to standardize the onboarding experience for Claude instances across different projects. It contains no source code - only documentation and configuration files to help Claude understand project context and user preferences.

## Key Files

### CLAUDE_SETUP.md
A structured questionnaire covering 6 areas:
- **Project Context**: Goals, project type, and user role
- **Interaction Style**: Response preferences and proactivity level
- **Focus Areas**: Code areas to prioritize or avoid
- **Conventions & Standards**: Coding patterns and formatting
- **Environment & Tools**: Development setup and dependencies
- **Communication Preferences**: Technical depth and security handling

Run this setup at the start of new projects to personalize assistance.

### .claude/settings.local.json
Contains Claude Code permission configuration using whitelist approach. Currently allows:
- `dir:*` - Directory listing commands
- `ls:*` - File listing operations  
- `find:*` - File search operations

## Usage as Template

This repository serves as a template for Claude-assisted projects:

1. Copy CLAUDE_SETUP.md to new projects
2. Customize the questionnaire for project-specific needs
3. Configure permissions in .claude/settings.local.json based on project requirements
4. Run the setup process to establish working preferences

## Current Project Configuration

Based on the completed setup questionnaire:

**Project Context:**
- Purpose: Documentation repository to help with Claude usage across other projects
- Status: New project
- Role: Owner

**Interaction Style:**
- Response preference: Concise responses
- Explanations: Always explain reasoning for suggestions
- Proactivity: Be proactive with improvements

**Focus Areas:**
- No specific focus areas currently

**Conventions & Standards:**
- No established standards yet

**Environment & Tools:**
- Primary tool: Git for cloud storage
- Repository status: Not yet initialized as git repo

**Communication Preferences:**
- Technical terms: Explain when used
- Best practices: Suggest proactively
- Security concerns: Notify immediately

## Git Integration

The repository is not currently a git repository. When using as a template, initialize git in target projects to enable version control and cloud storage.