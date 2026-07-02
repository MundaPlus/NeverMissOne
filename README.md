# NeverMiss One

> A personal reminder and safety check-in platform that escalates to your trusted contacts if you don't respond — built for people who live alone or work in high-risk situations.

![Status](https://img.shields.io/badge/status-beta-yellow)

## Overview

Most reminder apps stop at the notification. NeverMiss One goes further: if a user fails to confirm a check-in, the platform automatically works through a configurable escalation sequence — retrying across different channels and notifying designated emergency contacts, all without requiring those contacts to create an account.

The platform is offered as a subscription SaaS product at [nevermiss.one](https://nevermiss.one), with Free, Standard, and Pro tiers. It targets individuals who want peace of mind that someone will be alerted if something goes wrong — from elderly people living alone to remote workers and solo travellers.

## Key Capabilities

- **Set reminders that actually matter** — one-off or recurring reminders (daily, weekly, monthly, or custom schedules) delivered across whichever channels the user prefers
- **Require confirmation, not just delivery** — reminders can require an explicit "I'm OK" response; if none arrives within a set window, the platform treats it as a missed check-in
- **Automatic escalation sequences** — if a user misses a check-in, the platform works through an ordered set of steps: retrying on different channels, then notifying emergency contacts, with configurable delays between each step
- **Reach users where they already are** — notifications delivered via email, browser push (no app install needed), Telegram, and Viber; each user chooses their own combination
- **Emergency contacts need no account** — trusted contacts receive a secure, one-time link that shows them the user's emergency plan and any relevant instructions; no registration required
- **Structured emergency plans** — users can pre-write instructions for contacts (e.g. "call my GP", "check the spare key is under the mat"), surfaced automatically when escalation triggers
- **Secure by design** — two-factor authentication, OAuth login via Google and GitHub, encrypted messaging credentials, and a full audit log of every notification and action

## Tech Highlights

| Layer | Technology |
|---|---|
| Backend | PHP / Laravel |
| Database | MariaDB |
| Frontend | Blade templates, Tailwind CSS, Bootstrap 5 |
| Progressive Web App | Installable on mobile and desktop, offline-capable |
| Notifications | Email, Web Push, Telegram Bot, Viber Bot |
| Billing | Stripe (subscription management + customer portal) |
| Authentication | Password, TOTP two-factor auth, Google/GitHub OAuth |
| Background processing | Laravel Queues + Scheduler (fully self-hosted, no third-party queue service) |

## Screenshots

> *Screenshots available on request or at [nevermiss.one](https://nevermiss.one)*

## Status & Availability

NeverMiss One is in active beta, deployed to production at [nevermiss.one](https://nevermiss.one). Core reminder, check-in, escalation, and notification flows are fully functional. Planned near-term additions include WhatsApp as a notification channel and expanded referral and rewards features. The platform is proprietary and operated by Munda Plus d.o.o.

## Interested?

This is a proprietary project by **Munda Plus d.o.o.**
The full codebase is available for review upon request.

📧 marko@munda.si  
🌐 [munda.si](https://www.munda.si)
