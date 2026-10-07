# Install everything: brew bundle  (or: brew bundle --file=./Brewfile)

tap "stablyai/orca"

# CLI
brew "htop"

# Language toolchains
brew "pyenv"         # Python version manager
brew "nvm"           # Node version manager (needs shell setup, see `brew info nvm`)
brew "node"          # Node.js + npm
brew "bun"           # Bun JS runtime
cask "temurin@11"    # Java 11 (Eclipse Temurin JDK)
cask "temurin@21"    # Java 21 (Eclipse Temurin JDK)

# AI
cask "claude"              # Claude desktop
cask "claude-code@latest"  # Claude Code CLI, latest channel (conflicts with "claude-code")
cask "codex"               # OpenAI Codex CLI
cask "chatgpt"             # ChatGPT desktop

# Terminals
cask "iterm2"
cask "ghostty"

# Development
cask "stablyai/orca/orca"  # Orca (onorca.dev); also links the `orca` CLI, so `orca serve` works
cask "docker-desktop"
cask "jetbrains-toolbox"
cask "visual-studio-code"

# Browser
cask "google-chrome"

# Communication & notes
cask "slack"
cask "notion"
