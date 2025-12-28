# git-commit-msg-hook-claude-code
Add a git hook to automatically create a commit message using claude code


Installation:
  cp prepare-commit-msg /path/to/your/repo/.git/hooks/
  chmod +x /path/to/your/repo/.git/hooks/prepare-commit-msg

Installing globally with this folder as the source of all git hooks
  git config --global core.hooksPath $(PWD)

Requirements:
  - Claude CLI installed and authenticated (no need to manage API keys manually)


