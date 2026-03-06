# genai Code Action

A general-purpose GenAI action for GitHub PRs and issues that can answer questions and implement code changes. This action intelligently detects when to activate based on your workflow context—whether responding to @genai mentions, issue assignments, or executing automation tasks with explicit prompts. 

## Features

- 🎯 **Intelligent Mode Detection**: Automatically selects the appropriate execution mode based on your workflow context—no configuration needed
- 🤖 **Interactive Code Assistant**: Claude can answer questions about code, architecture, and programming
- 🔍 **Code Review**: Analyzes PR changes and suggests improvements
- ✨ **Code Implementation**: Can implement simple fixes, refactoring, and even new features
- 💬 **PR/Issue Integration**: Works seamlessly with GitHub comments and PR reviews
- 🛠️ **Flexible Tool Access**: Access to GitHub APIs and file operations (additional tools can be enabled via configuration)
- 📋 **Progress Tracking**: Visual progress indicators with checkboxes that dynamically update as Claude completes tasks
- 📊 **Structured Outputs**: Get validated JSON results that automatically become GitHub Action outputs for complex automations
- 🏃 **Runs on Your Infrastructure**: The action executes entirely on your own GitHub runner (Anthropic API calls go to your chosen provider)
- ⚙️ **Simplified Configuration**: Unified `prompt` and `claude_args` inputs provide clean, powerful configuration aligned with Claude Code SDK


## Quickstart

**Note**:

- You must be a repository admin to install the GitHub app and add secrets

## 📚 Solutions & Use Cases

- **🔍 Automatic PR Code Review** - Full review automation
- **📂 Path-Specific Reviews** - Trigger on critical file changes
- **👥 External Contributor Reviews** - Special handling for new contributors
- **📝 Custom Review Checklists** - Enforce team standards
- **🔄 Scheduled Maintenance** - Automated repository health checks
- **🏷️ Issue Triage & Labeling** - Automatic categorization
- **📖 Documentation Sync** - Keep docs updated with code changes
- **🔒 Security-Focused Reviews** - OWASP-aligned security analysis
- **📊 DIY Progress Tracking** - Create tracking comments in automation mode

Each solution includes complete working examples, configuration details, and expected outcomes.

## Documentation


## 📚 FAQ


## License

This project is licensed under the MIT License—see the LICENSE file for details.