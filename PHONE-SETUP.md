# Your phone terminal setup

Give this link to **Codex or Claude Code running on your computer**. Your agent gets the APK source, matching host/title code, settings, optional browser runtime and workflow/skills.

## Download

- [Protected phone/system package](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/download/phone-handoff-2026.11.16.4/mantis-phone-handoff.zip) · [SHA-256](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/download/phone-handoff-2026.11.16.4/mantis-phone-handoff.zip.sha256)
- [Protected workflow +36 skills](https://github.com/CalebDane7/kaleeb-agent-workflow-download/releases/latest/download/kaleeb-agent-workflow.zip)

Get both passwords privately from Caleb. Use an AES-compatible extractor such as7-Zip; enter passwords in a hidden local prompt.

## Paste this into your agent

> Read this page and the phone package's README.md and docs/AGENT-SETUP.md. Set up my Android phone terminal on my computer using my own accounts. Offer “Install everything” first. If I prefer “Select components”, explain each briefly and install those choices plus required companions. Before replacing my workflow, follow docs/INSTRUCTION-BACKUP.md: back up my existing AGENTS.md/CLAUDE.md and related personal rules, disable competing old workflow instructions, and tell me where the originals are saved and how to restore them. Preserve my project knowledge and other settings. Pair my phone through debugging, install/configure Tailscale, adapt the local title service, rebuild the APK for my host and install it. Do the accessible setup yourself; guide me through required sign-ins and phone approvals. Verify actual phone input, titles, session switching and reconnect before calling it ready.

## Your existing instructions are saved

Before replacing your workflow, the agent backs up your old `AGENTS.md`/`CLAUDE.md` and checks for other instructions that would compete. Your originals stay recoverable. At the end, it reports: **“I backed up your old instructions to [location] and replaced the workflow so they won’t compete.”** It also gives you restoration steps.

## Your part

1. Tell the agent your computer OS and whether you use Codex, Claude Code or both.
2. On your phone, enable **Developer options → Wireless debugging**. On Samsung, first tap **Settings → About phone → Software information → Build number** seven times.
3. On the same Wi-Fi as your computer, show the agent the Wireless debugging screen. When ready, open **Pair device with pairing code** and share that popup privately. USB debugging is an alternative.
4. Complete your own Tailscale/agent sign-ins and Android VPN/permission prompts. The agent handles installation and verification after pairing.

The two debugging screens have different ports; enabling debugging alone does not authorize the computer. [Official Android steps and example screens](https://developer.android.com/tools/adb#wireless), [Tailscale Android setup](https://tailscale.com/docs/install/android).

## What gets installed

| Component | Purpose |
| --- | --- |
| Android APK | Phone display, input and session controls. Your agent rebuilds it with your host address. |
| Host controller + title service | Connect the APK to your CLI; generate and publish session titles locally. |
| Customized tmux | Keep CLI sessions alive after closing a terminal window. Included Linux x64 binary. |
| Tailscale | Private phone-to-computer connection. Uses your own account. |
| Codex or Claude Code | Run your chosen agent on your computer. The supplied title backend also needs Codex authentication unless adapted. |
| WezTerm — optional | Matching desktop terminal appearance and session access. |
| Agent Browser — optional | Let your agent operate your existing Chrome profile. Runtime, extension and native host are included. |
| Workflow + chosen skills | Preserve project decisions, route specialist work, avoid repeating failed fixes and require real verification. |

Windows+Ubuntu WSL2 is closest to the original. The optional browser binary requires Linux x64/glibc2.39+ and Windows Chrome. Other platforms need adaptation. The reference APK contains the original addresses: **build yours before installing**. The package supplies source, exact settings and a tested local-title adaptation reference. Your agent builds/configures your installation and verifies your machine.

The protected agent guides explain each required setting, why it exists, what to replace and how to check it. They cover phone input, title/account contracts, private networking, startup, Android signing, browser enrollment, dependencies and recovery. Your personal credentials and signing key stay yours.

## Choose your setup

**Install everything** — the phone system, matching optional desktop/browser tools, workflow and all36 skills. Your agent configures the tools with your own accounts.

**Select components** — choose what you need; open the brief explanations below. Your agent includes required companions. Large optional model downloads and paid subscriptions remain separate choices.

<details>
<summary>What each skill does</summary>

Choose the rows you need; your agent adds required companions.

| Skill | Use it to… |
| --- | --- |
| `agent-browser` | Sign into websites, operate controls and verify the actual rendered page and saved changes. |
| `agent-communication` | Inspect relevant agent sessions and exchange task status, evidence and handoffs through native messages. |
| `animate` | Add React or Next.js hover effects, modal transitions and responsive interface motion. |
| `app-building` | Trace app failures across components, repair the cause and replay the original failing journey. |
| `beautiful-converting-frontend-design` | Build responsive pages with audience-led layout, clear copy, visible product proof and browser checks. |
| `best-copywriting` | Write persuasive pages, ads, emails and offers while preserving the approved argument and voice. |
| `blender-animation-workflow` | Animate hinges, moving assemblies and object actions; check timing, contacts and exported motion. |
| `blender-art-direction-intake` | Set a 3D object's style, materials, scale and views before modeling. |
| `blender-asset-validation` | Inspect topology, dimensions, materials and exported models; render views exposing geometry defects. |
| `blender-character-workflow` | Build characters, rig joints, paint skin weights and test facial expressions and deformation. |
| `blender-iterative-refinement` | Improve an existing Blender asset, comparing fixed before-and-after views and preserving accepted details. |
| `blender-modeling-workflow` | Create editable 3D props and assemblies; printing still needs slicer and printer validation. |
| `blender-procedural-workflow` | Generate repeatable terrain, scattered objects and parametric scenes using Geometry Nodes. |
| `blender-rendering-workflow` | Render product photos, turntables and animation videos with controlled cameras, lighting and materials. |
| `blender-simulation-workflow` | Simulate fluids, smoke, cloth and collisions; bake caches and inspect the resulting motion. |
| `blender-to-web` | Turn Blender models into interactive website objects with drag, motion and fallback states. |
| `brainstorm-plan` | Keep evolving requirements, rejected approaches and remaining acceptance together in one project plan. |
| `browser-swarm` | Run independent browser checks across separate agent-owned tabs, then close their finished tabs. |
| `codex-workflow-router` | Recover earlier project decisions and load the specific workflow rules needed for continuing work. |
| `compact-keywords-seo` | Find search queries, map pages, optimize on-page phrases and investigate local or AI-search visibility. |
| `copyable-links` | Provide download and repository URLs in plain text that can be copied reliably. |
| `design-taste-frontend` | Design landing pages and portfolios around a chosen visual style; audit before redesigning. |
| `form-cro` | Simplify contact, quote, checkout and survey forms through fields, validation and mobile layout. |
| `image-to-3d` | Turn object photos into a reusable base mesh using free local tools. |
| `impeccable` | Audit and refine interface typography, layout, accessibility, responsive behavior and loading/error states. |
| `marketing-psychology` | Apply buyer psychology to offers, pricing, objections and the choices visitors face. |
| `media-research` | Download videos, extract transcripts and frames, and analyze what they show with optional Gemini. |
| `page-cro` | Find where landing-page messaging, proof and calls to action lose potential customers. |
| `poe-media` | Generate or edit images, upscale pictures and create video through your Poe API account. |
| `popup-cro` | Design popup offers, triggers, frequency and dismissal for email capture, promotions or announcements. |
| `pricing-strategy` | Choose pricing tiers, value metrics and packaging using customer willingness-to-pay and competitor evidence. |
| `product-marketing-context` | Record audience, positioning, objections, customer language and proof once for subsequent marketing work. |
| `recover-wsl-via-windows` | Preserve ongoing agent work while diagnosing Windows/WSL faults that may require stopping WSL. |
| `remotion-best-practices` | Create videos in React, including animated text, captions, audio visualizations and composited footage. |
| `run-powershell-safely` | Run Windows commands from WSL with reliable quoting, host checks and captured exit status. |
| `signup-flow-cro` | Reduce account-creation dropoff by improving signup fields, steps, validation and immediate post-submit behavior. |

</details>

## Suggested project routine

1. **Name the project.** Tell your agent what you want and what “done” means.
2. **Keep one plan per project.** Ask it to record intent, decisions, corrections and verified progress in `PROJECT_PLAN.md`, reusing an existing project plan when present.
3. **For longer Codex work:** ask it to set a goal using that plan and keep working until the result is verified. Supported Codex builds offer `/goal <outcome>`; `/goal pause` and `/goal resume` control it. [Official Codex goal guide](https://developers.openai.com/cookbook/examples/codex/using_goals_in_codex).
4. **Next time:** say, “Continue this project from `PROJECT_PLAN.md`.” The plan preserves context across sessions and helps prevent old mistakes returning.

This is an optional starting routine. AGENTS.md/CLAUDE.md and the selected skills guide the detailed work. Claude can use the same project plan; Codex's `/goal` command is not a Claude command.
