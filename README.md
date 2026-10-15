# Postmaster Sovereign Desk & Omnichannel Hub (LoanCall Pro)

> Autonomous, zero-dependency, commercial-grade omnichannel communication suite, in-chat AI credit underwriter, and outbound telephony calling desk.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status: Production](https://img.shields.io/badge/Status-Production%20Ready-green.svg)](#)

---

## Overview

**Postmaster Sovereign Desk** is a high-performance, single-file standalone web application (`index.html`) and autonomous agent orchestrator designed as a drop-in upgrade over traditional WhatsApp-Web / Whapi-class messengers.

### Key Differentiators vs Standard WhatsApp Web & Whapi
1. **5-in-1 Omnichannel Unified Feed:** WhatsApp, Telegram, Google Chat, Slack, and Gmail synchronized in a single split-view inbox with real-time channel filters and unread badges.
2. **In-Chat Genie AI Underwriter:** Instant CIBIL score tiering, FOIR % calculations, multi-lender credit policy match (HDFC, ICICI, Bajaj), and monthly EMI calculator with 1-click composer insertion.
3. **Bhism Outbound Telephony Calling Desk:** Integrated softphone dialer, call duration timer, dynamic Hinglish sales/support pitch generator, and disposition logging.
4. **1-Click Meeting Orchestrator:** Dispatch interactive Google Meet, Zoom, and Microsoft Teams invite cards directly into active chat threads.
5. **Multi-Gateway Protocol Switcher:** Built-in payload compatibility and simulation for Whapi.Cloud REST v2, WAHA Plus Core, Evolution API v2.1, and Meta Cloud API v20.0 Graph.
6. **Zero Backend Lock-In (MPIN Compliant):** Runs completely offline or as a static SPA via `file://`, GitHub Pages, Vercel, or Cloudflare Pages with pure `localStorage` persistence.

---

## Project Structure

```
postmaster-sovereign-desk/
├── index.html                   # Standalone Production SPA (Postmaster Sovereign Desk)
├── install-postmaster.ps1       # Master PowerShell installer & omnichannel dispatcher module
├── languages.json               # 1100-language registry with strict commercial licensing tags
├── agent/
│   └── postmaster.md            # Sovereign Postmaster Agent definition (14 compacted skills)
├── skill/
│   └── SKILL.md                 # Postmaster Notifier Managed Skill
└── README.md                    # Project documentation & launch guide
```

---

## Quick Start

### 1. Launch the Web Application
Open `index.html` directly in any modern browser:
```powershell
Start-Process "index.html"
```
Or launch via the included PowerShell launcher:
```powershell
. .\install-postmaster.ps1
Start-PostmasterMessenger
```

### 2. Available Dispatcher Functions in PowerShell
- `Get-PostmasterWhatsAppUrl` - Generate clean, direct click-to-chat links.
- `Send-PostmasterTelegram` - Dispatch messages via Telegram Bot API.
- `Send-PostmasterDiscord` - Post structured notifications with rich embeds.
- `Send-PostmasterSlack` - Post Block Kit formatted webhook notifications.
- `Send-PostmasterGoogleChat` - Post cardsV2 interactive widgets and RSVP cards.
- `Send-PostmasterGmail` - Dispatch HTML emails via Google Apps Script mail bridge.
- `Send-PostmasterMeetingInvite` - Broadcast Google Meet / Zoom links to channels.
- `Get-PostmasterVoiceScript` - Generate customized Hinglish sales scripts.
- `Format-PostmasterCallLog` - Structure call outcomes and sync attendance records.

---

## Commercial Licensing & Valuation Readiness

- **IP & Trademark Safe:** 100% original brand dress, icons, and vectors. Zero trademark infringement (clean for ProductHunt, Flippa, CodeCanyon, and Acquire.com).
- **Speech Engine Tiers:**
  - **Tier 1 (Cloud Neural):** Azure / Google TTS / ElevenLabs (Commercial SLA).
  - **Tier 2 (Open-Source Edge):** Piper TTS (MIT License) & Whisper STT (MIT License).
  - **Tier 3 (Academic Research):** Meta MMS (CC-BY-NC-4.0) restricted strictly to research; zero commercial bundle contamination.

---

## License
MIT License. Commercial safe for distribution, SaaS white-labeling, and monetization.
