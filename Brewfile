# Install everything: brew bundle  (or: brew bundle --file=./Brewfile)

# Third-party taps (trusted so newer Homebrew agrees to load them)
tap "stablyai/orca", trusted: true
tap "nguyenphutrong/tap", trusted: true
tap "hashicorp/tap", trusted: true
tap "azure/kubelogin", trusted: true

# ── Core CLI ──────────────────────────────────────────────
brew "gh"               # GitHub CLI (PRs, issues, actions)
brew "glab"             # GitLab CLI
brew "htop"             # interactive process monitor
brew "age"              # simple file encryption
brew "sops"             # encrypted secrets in YAML/JSON
brew "pandoc"           # document converter (md, docx, pdf, html)
brew "ffmpeg"           # video and audio processing
brew "yt-dlp"           # video downloader (YouTube and others)

# ── Language toolchains ───────────────────────────────────
brew "pyenv"            # Python version manager
brew "uv"               # fast Python package and venv manager
brew "nvm"              # Node version manager (needs shell setup, see `brew info nvm`)
brew "node"             # Node.js + npm
brew "pnpm"             # JS package manager
brew "yarn"             # JS package manager
brew "bun"              # JS runtime, bundler and package manager
brew "go"               # Go compiler
brew "rust"             # Rust compiler + cargo
brew "cmake"            # C/C++ build system
cask "temurin@11"       # Java 11 (Eclipse Temurin JDK)
cask "temurin@21"       # Java 21 (Eclipse Temurin JDK)

# ── Cloud & DevOps ────────────────────────────────────────
brew "awscli"           # AWS CLI
brew "azure-cli"        # Azure CLI
cask "gcloud-cli"       # Google Cloud CLI
cask "yandex-cloud-cli" # Yandex Cloud CLI
brew "kubernetes-cli"   # kubectl
brew "azure/kubelogin/kubelogin"  # AKS auth via Azure AD (core "kubelogin" is a different OIDC plugin)
brew "helm"             # Kubernetes package manager
brew "hashicorp/tap/terraform"    # infrastructure as code
brew "hashicorp/tap/vault"        # HashiCorp secrets store
brew "tailscale"        # Tailscale VPN CLI
brew "wireguard-tools"  # WireGuard VPN tools
brew "postgresql@18"    # PostgreSQL server + psql (keg-only, see `brew info postgresql@18`)
brew "duckdb"           # embedded analytical SQL database

# ── AI ────────────────────────────────────────────────────
cask "claude"              # Claude desktop
cask "claude-code@latest"  # Claude Code CLI, latest channel (conflicts with "claude-code")
cask "codex"               # OpenAI Codex CLI
cask "chatgpt"             # ChatGPT desktop
cask "nguyenphutrong/tap/quotio"  # control panel for AI coding assistants (quotas, accounts)
cask "lm-studio"           # GUI for local LLMs

# ── Terminals ─────────────────────────────────────────────
cask "iterm2"
cask "ghostty"

# ── Development ───────────────────────────────────────────
cask "stablyai/orca/orca"  # agent & worktree manager, Ghostty-based terminal; also links the `orca` CLI (`orca serve`)
cask "visual-studio-code"  # code editor
cask "cursor"              # code editor
cask "zed"                 # code editor
cask "jetbrains-toolbox"   # JetBrains IDE manager
cask "docker-desktop"      # Docker
cask "rapidapi"            # HTTP client for APIs
cask "ngrok"               # public tunnel to localhost

# ── Network & VPN ─────────────────────────────────────────
cask "tailscale-app"       # Tailscale GUI
cask "tunnelblick"         # OpenVPN client

# ── Browsers ──────────────────────────────────────────────
cask "google-chrome"
cask "arc"

# ── Communication & notes ─────────────────────────────────
cask "telegram"
cask "slack"
cask "notion"
cask "obsidian"            # Markdown notes
