# git-commit-msg-hook-claude-code
Add a git hook to automatically create a commit message using claude code

Set up global git hook folder if you have not done so already:
  git config --global core.hooksPath /path/to/global/.githooks/

Installation:
  chmod +x prepare-commit-msg
  cp prepare-commit-msg /path/to/global/.githooks/


Requirements:
  - Claude CLI installed and authenticated (no need to manage API keys manually)


