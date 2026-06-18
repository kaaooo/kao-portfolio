<div align="center">

```
████████████████████████████████████████████████████████████████████████████████
██                                                                          ██
██                              █████╗ ██╗  ██╗ █████╗  ██████╗             ██
██                             ██╔═══██╗██║ ██╔╝██╔══██╗██╔═══██╗            ██
██                             ██║   ██║█████╔╝ ██║  ██║██║   ██║            ██
██                             ██║   ██║██╔═██╗ ██║  ██║██║   ██║            ██
██                             ╚██████╔╝██║  ██╗╚█████╔╝╚██████╔╝            ██
██                              ╚═════╝ ╚═╝  ╚═╝ ╚════╝  ╚═════╝             ██
██                                                                          ██
██               ARCHITECTING DISCORD ECOSYSTEMS & NODE.JS SOLUTIONS         ██
██                                                                          ██
████████████████████████████████████████████████████████████████████████████████

</div>

---

# Table of Contents

1. [About Me](#about-me)
2. [Pricing](#pricing)
3. [Bot Fleet](#bot-fleet)
4. [Tech Stack](#tech-stack)
5. [Testimonials](#testimonials)
6. [FAQ](#faq)
7. [Contact](#contact)

---

## About Me

```yaml
name: !kao!
role: Discord Bot Developer
experience: Multiple production bots deployed
approach: 100% custom code, no templates, no frameworks
location: EU
status: Accepting commissions
```

I'm a Discord bot developer who builds production-grade automation for communities. Everything I make is written from scratch — every command, every event, every database model. No copy-paste, no generators, no template repos.

I've built bots handling hundreds of users across ticketing, applications, AI automation, leveling systems, queue management, moderation, and more. My work is deployed on Linux servers using PM2 and MongoDB, running 24/7.

---

## Pricing

All bots are custom-built for your specific needs. You pay once and own the full source code.

| Tier | Price | Scope | Examples |
|:----:|:-----:|:------|:---------|
| 🟢 **Easy** | **€5** | Small tasks, 1-3 commands, basic embeds, simple logic | `/ping`, `/avatar`, `/userinfo`, a single reaction role, minor bot fixes |
| 🟡 **Medium** | **€7** | Full systems with database, multi-command, panels | Ticket system, application system, leveling/XP, suggestion engine, moderation suite |
| 🔴 **Hard** | **€10** | Complex logic, AI integration, web dashboards, automations | AI auto-responder, queue manager, web dashboard with OAuth, multi-bot ecosystems |

### What's included

- Full source code delivered via GitHub or ZIP
- MongoDB database integration (if applicable)
- Deployment support — I help you get it running on your server
- Free bug fixes if something breaks
- Modular codebase — easy to extend later

### Payment

PayPal or Revolut. Pay once, done. No subscriptions, no monthly fees, no recurring charges.

---

## Bot Fleet

A complete overview of every bot system I've built and deployed.

---

### 🟢 NV-01 — Nova Tiers Ticket Bot

**Status:** `PRODUCTION` · **Members:** Multiple servers

A high-throughput ticket lifecycle system designed for servers that need serious support infrastructure.

**Features:**
- 4-category dropdown panel (Support, Report, Application, Bug Report)
- Role-based permission system for staff channels
- Claim / unclaim system with ownership tracking
- Queue management for unclaimed tickets
- AI auto-responder integration via Groq API (Qwen 3 32B)
- Minecraft account linking and in-game verification
- Rating & feedback system with 1-5 star reviews
- HTML transcripts with full message history
- Audit logging to dedicated log channel
- Mod-only notes system per ticket

---

### 🟢 NV-02 — Application & Forms System

**Status:** `PRODUCTION` · **Members:** Multiple servers

A premium DM-based application system for staff recruitment, whitelist applications, or any form-based submission.

**Features:**
- Multi-step DM interview flow (configurable number of questions)
- Button or dropdown panel deployment
- Staff review panel with Accept / Deny / Trial buttons
- Automatic role assignment on accept (Staff Role, Trial Role)
- Customizable DM messages per status (accept/deny/trial)
- Cooldown system to prevent spam applications
- Application statistics dashboard (pending/accepted/denied)
- Web dashboard built with Express + EJS + Discord OAuth
- Review history tracking (who reviewed, when, reason)

---

### 🟢 NV-03 — Ticket Support Core

**Status:** `PRODUCTION` · **Members:** Multiple servers

Foundational ticket infrastructure for servers that need reliable, permission-based support channels.

**Features:**
- Button-based ticket creation with category selection
- Permission-locked channels (only user + staff can see)
- Welcome embed with ticket information on creation
- Claim / unclaim with visual indicators
- Priority levels (Low, Medium, High, Urgent)
- Private staff notes visible only to moderators
- Move ticket between categories
- Add / remove users from ticket
- Close with reason, close without reason
- Reopen closed tickets
- Full channel rename support
- Deadline system with timestamp display
- Blacklist to prevent ticket abuse
- Transcripts on close

---

### 🟢 NV-04 — AI Auto-Responder Engine

**Status:** `PRODUCTION` · **Members:** Multiple servers

An intelligent AI system that monitors support channels and responds to user queries automatically, reducing staff workload.

**Features:**
- Powered by **Groq API** with **Qwen 3 32B** model
- Monitors ticket channels for user messages
- Automatically responds to common support questions
- Detects when staff replies and pauses AI responses
- Resumes automatically after 2 hours of staff inactivity
- Context-aware — understands ticket category and reason
- Configurable response length and tone
- Toggle on/off per server or per channel
- Ignore list for specific topics or users
- Response rate analytics

---

### 🟢 NV-05 — Queue & Waitlist Manager

**Status:** `PRODUCTION` · **Members:** Active

A region-based queue system designed for testing servers, Minecraft whitelists, or any waitlist workflow.

**Features:**
- EU and NA region channels
- Modal-based signup collecting server, IGN, and region
- Auto-assigns queue roles on registration
- Capacity limit (capped at 20 per queue)
- Automatic tester ping when someone joins
- `/pull` command to pull next user from queue
- `/next` command to preview next in line
- Auto-create ticket when user is pulled
- Queue position display
- Remove / leave queue commands

---

### 🟡 NV-06 — Moderation & Utility Suite

**Status:** `STANDBY` · **Members:** Available for deployment

A comprehensive moderation toolkit covering every standard moderation need plus advanced utility commands.

**Commands:**
- `/warn` — Issue warnings with reason tracking
- `/warnings` — View user warning history
- `/reset-warns` — Clear all warnings for a user
- `/modstats` — Moderation activity statistics
- `/timeout` / `/untimeout` — Discord timeout management
- `/mute` / `/unmute` — Text-based mute system
- `/ban` / `/unban` — Ban management with reason logging
- `/kick` — Kick with reason
- `/purge` — Bulk message deletion
- `/nuke` — Clone and delete channel
- `/slowmode` — Per-channel rate limiting
- `/lock` / `/unlock` — Channel lockdown
- `/hide` / `/unhide` — Channel visibility toggle
- `/report` — User-to-staff reporting system

---

### 🟢 NV-07 — Custom Leveling & XP System

**Status:** `PRODUCTION` · **Members:** Active

A full-featured engagement tracking system with XP, levels, reputation, and rewards.

**Features:**
- Text activity XP gain with cooldown
- Voice channel XP tracking
- Multi-server global leaderboard
- Level-up role rewards (configurable)
- Reputation system (`/rep`)
- Daily rewards (`/daily`)
- XP boost multipliers for events
- Prestige ranks at max level
- Embed-based rank cards with progress bars
- `/level` — View level and XP
- `/leaderboard` — Server rankings
- `/profile` — Full user profile
- `/rank` — Rank card display
- AFK tracking with auto-removal on message

---

### 🟡 NV-08 — Suggestion & Feedback Engine

**Status:** `STANDBY` · **Members:** Available for deployment

A community suggestion system with voting, moderation, and organization features.

**Features:**
- Button-based suggestion submission
- Upvote / downvote system
- Auto-create thread for discussion
- Staff approval gate (suggestions hidden until approved)
- Status tracking: Pending, Approved, Denied, Implemented
- Anonymous submission mode
- Weekly digest summaries
- Suggestion statistics
- Feedback command for direct staff messages
- Poll creation with reaction voting

---

## Tech Stack

```
Category              Skill Level
────────────────────────────────────────────────────────────
Language              ████████████████████████████████░░░░  TypeScript / JavaScript (ES6+)
Runtime               ████████████████████████████████████  Node.js
Library               ████████████████████████████████████  discord.js v14
Database              ██████████████████████████████████░░  MongoDB (Mongoose)
AI / LLM              ██████████████████████████████████░░  Groq API (Qwen 3 32B)
Web Frameworks        ████████████████████████████████░░░░  Express.js, EJS
Authentication        ██████████████████████████████████░░  Discord OAuth2
Process Manager       ████████████████████████████████████  PM2
Version Control       ████████████████████████████████████  Git / GitHub
Hosting               ████████████████████████████████████  Linux (Ubuntu, Debian)
Deployment            ████████████████████████████████████  Wispbyte, VPS
Frontend Templating   ██████████████████████████████████░░  EJS
API Integration       ████████████████████████████████████  REST, Webhooks
```

---

## Testimonials

> *"Incredible quality. Nova built our entire ticket system from scratch and it handles hundreds of users without a single issue. Fast turnaround and great communication."*
>
> **— AlphaDragon**, Server Admin

> *"The AI auto-responder is next-level. It handles 90% of support questions so my mods can focus on real issues."*
>
> **— XyLo**, Community Owner

> *"Best developer I've worked with on Discord. Clean code, reliable uptime, and always goes above expectations."*
>
> **— VexNeon**, Dev Partner

---

## FAQ

### What tech stack do you use?

TypeScript with discord.js v14, MongoDB via Mongoose for data persistence. Web dashboards are built with Express.js and EJS templates. AI features use the Groq API with the Qwen 3 32B model. Everything runs on Node.js under PM2 process management on Linux servers.

### How long does it take to build a bot?

It depends on complexity:

- **Easy (€5):** 1–2 days
- **Medium (€7):** 2–4 days
- **Hard (€10):** 3–7 days

These are estimates based on past projects. I'll give you a precise timeline before starting.

### Do you use templates or generators?

**No.** Every bot is written from scratch. No copy-paste, no template repos, no code generators. Every command, every event, every database schema is hand-written for your specific requirements. This means cleaner code, fewer bugs, and a bot that actually fits your server.

### Can you add features to an existing bot?

Yes. If you already have a bot (even one I didn't build), I can add new features, fix bugs, or refactor the codebase. The price depends on the scope of work.

### What if the bot breaks?

I stand behind my work. If something breaks due to a bug in my code, I fix it for free. If it's a Discord API change or a dependency update, I handle that too.

### How do I pay?

PayPal or Revolut. Payment is handled upfront for smaller projects, or 50/50 split for larger ones. You receive the full source code once payment is complete.

### Do you offer refunds?

If I can't deliver what was agreed upon, you get a full refund. If the project is completed and delivered, no refund — but you own the code and can use it however you want.

### Can I host the bot myself?

Absolutely. You get the full source code and detailed setup instructions. I can also deploy it to your VPS or hosting provider if needed.

### How do I contact you?

See the contact section below. Discord is the fastest way to reach me.

---

## Contact

<div align="center">

| Platform | Link |
|:---------|:-----|
| 🐙 **GitHub** | [github.com/kaaooo](https://github.com/kaaooo) |
| 🧑‍💻 **Reddit** | [u/Terrible-Walk-7467](https://reddit.com/u/Terrible-Walk-7467) |
| 💬 **Discord** | [kaaooosupport](https://discord.gg/4cfk6R74yK) |

</div>

---

<div align="center">

```
████████████████████████████████████████████████████████████████████████████████
██                                                                          ██
██              !kao! — building bots that actually work.                  ██
██              Commissions open · From scratch · €5–€10                    ██
██                                                                          ██
████████████████████████████████████████████████████████████████████████████████
```

</div>
