<div align="center">

# AeroScan AI

**A Windows desktop app for working with AI: chat, an agent that works in your projects, and image generation, all in one place.**

[![Latest release](https://img.shields.io/github/v/release/adminaeroscan/aeroscan-beta?include_prereleases&label=beta&color=7c3aed)](https://github.com/adminaeroscan/aeroscan-beta/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/adminaeroscan/aeroscan-beta/total?color=2f6fe4)](https://github.com/adminaeroscan/aeroscan-beta/releases)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-0078d4)

### [⬇ Download the beta](https://github.com/adminaeroscan/aeroscan-beta/releases/latest) &nbsp;·&nbsp; [Website download page](https://ai.aeroscan.co.za/download)

</div>

---

<div align="center">

<img src="docs/01-chat-model-costs.png" alt="Chat with the model picker showing each model's request cost" width="860">

<sub>Every model shows what one message costs before you send it.</sub>

<img src="docs/02-agent-mode.png" alt="Agent mode working in a project folder" width="860">

<sub>Agent mode works inside your project folder and asks before changing files.</sub>

<img src="docs/03-projects.png" alt="The Projects page with to-dos, notes and the agent" width="860">

<sub>Projects keep to-dos, notes, chats and the agent together.</sub>

<sub><i>Screenshots use sample chat and project content. The model list and request costs are the real beta catalog.</i></sub>

</div>

---

## 🧪 Closed beta: first 20 testers get free access

We are looking for **20 testers**. The first 20 people to register in the app get the **Tester plan** for free:

| Tester plan | |
|---|---|
| Requests per day | **1,000** |
| Resets of the daily count | **3 per month** |
| Images / videos / music per day | 10 each |
| Daily token limit | none |
| Models | every model on the platform |

When the 20 spots are gone, registration closes. The [download page](https://ai.aeroscan.co.za/download) shows how many are left.

## What you get

- **Chat** with many AI models from one app. Each model shows its request cost next to its name, so you know what a message will use before you send it.
- **Agent mode** that works inside your own project folders: it reads, edits and builds. It uses one request per step, so watch the cost of big builds.
- **Projects** page to keep a project's chats, notes, code and agent work together.
- **Image generation** from the same window.

## Install

1. Download **`AeroScan AI-Beta-Setup-…-x64.exe`** from the [latest release](https://github.com/adminaeroscan/aeroscan-beta/releases/latest). Prefer no install? Take the **Portable** file instead.
2. Run it. Windows SmartScreen will warn you because the beta is **not code-signed yet**: click **More info**, then **Run anyway**.
3. Open AeroScan AI and register with your email. You'll get your tester key automatically.

Requires Windows 10 or 11, 64-bit.

### Verify your download

Every release lists the SHA-256 hash of each file in its notes. In PowerShell:

```powershell
Get-FileHash "AeroScan AI-Beta-Setup-1.0.0-beta.1-x64.exe" -Algorithm SHA256
```

The result must match the hash in the [release notes](https://github.com/adminaeroscan/aeroscan-beta/releases/latest).

## Feedback wanted

This is a beta, so expect rough edges. The most useful reports cover:

- the first-run setup,
- agent mode,
- the projects page.

👉 **[Open an issue](https://github.com/adminaeroscan/aeroscan-beta/issues/new)** with what you did, what you expected, and what happened. A screenshot helps.

## FAQ

**Is it free?** Yes during the beta, for the first 20 registrants. Paid plans are planned for later.

**Is the source code available?** Not at the moment. This repository holds release builds only.

**Why the SmartScreen warning?** Signing certificates cost money and the beta is new. Use the hash check above if you want to confirm the file.

**Mac or Linux?** Windows only for now.

---

<div align="center">AeroScan AI · <a href="https://ai.aeroscan.co.za/download">ai.aeroscan.co.za</a></div>
