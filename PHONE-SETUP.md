# Set up Caleb’s phone terminal on your computer

Give this page to **Codex or Claude Code running on your computer**. It explains what to download and gives your agent the source and setup guide.

This is a source handoff, not a finished installer. The supplied APK is Caleb’s reference build. Your agent must change its built-in computer addresses and rebuild it for you; it must also adapt the computer-side title service to your own account.

## 1. Download the two protected packages

- [Phone APK, Android source, computer-side source and setup guide](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/download/phone-handoff-2026.11.16/mantis-phone-handoff.zip) ([SHA-256](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/download/phone-handoff-2026.11.16/mantis-phone-handoff.zip.sha256)).
- [Existing AGENTS.md, workflow and 36-skill bundle](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/latest/download/kaleeb-agent-workflow.zip), including Agent Browser.

Ask Caleb for the passwords privately. They are not published here. Extract with an AES-compatible tool such as 7-Zip. Your agent can help download and extract them, but enter passwords in a hidden local prompt rather than its chat or a shell command.

## 2. Paste this into your agent

> Read this page and the extracted phone package’s START-HERE.md, docs/AGENT-SETUP.md and docs/SOURCE-MAP.md. Help me set this up on my own computer and Android phone. Inspect my OS and existing setup, preserve it, and explain each step briefly. Install the required tools, set up private Tailscale access, adapt and run the supplied local terminal/title services with my own account, change the Android host settings, then build and install my APK. Use USB debugging or paired wireless debugging to connect to my phone and verify the actual app. Install the workflow/skills bundle for my chosen agent after previewing its changes. Ask me only for decisions, sign-ins and phone approvals that require me. Do not call setup complete until phone input, titles, session switching and reconnect work.

## 3. The small part you do

1. Tell your agent which computer and Android phone you want to use. Windows with Ubuntu in WSL2 is closest to the original setup. Native Linux is another adaptation path; macOS has additional host work.
2. Sign in to **your own** Tailscale and Codex/Claude accounts when prompted. Keep the phone and computer in your own private network.
3. Connect your unlocked phone with USB and approve Android’s debugging prompt, or enable Wireless debugging and pair it on the same Wi-Fi.
4. Approve any required OS install prompts and Android app permissions. Your agent can then install and check the app.

**tmux is required for persistent sessions. WezTerm is an optional desktop terminal.** The original uses a customized tmux build; its matching Linux x86-64 binary and settings are included; verified tmux source is not included. The APK talks to the local control service, which supplies titles and session state. Installing WezTerm alone does not supply that service. The supplied title backend uses a Codex account even for Claude terminal sessions; a Claude-only setup needs a provider adaptation.

The protected guide covers startup, title-provider adaptation, APK rebuilding, security and verification. It does not promise a five-minute setup or claim that a different computer/phone has already been tested. Ordinary use does not require leaving USB debugging connected.

[Back to the workflow bundle](README.md)
