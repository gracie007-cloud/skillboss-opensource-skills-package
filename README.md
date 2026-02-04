<div align="center">

# <img src="assets/skillboss-logo.svg" alt="SkillBoss" width="56" /> SkillBoss Skills

**Production-ready skills for AI coding agents**

[![Website](https://img.shields.io/badge/Website-skillboss.co-blue?style=for-the-badge)](https://skillboss.co)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/U9eM6Vn6g7)
[![Docs](https://img.shields.io/badge/Docs-Help%20Center-green?style=for-the-badge)](https://skillboss.co/help)

</div>

---

SkillBoss is an AI skills platform by HeyBoss (backed by an OpenAI fund) that equips Claude Code, Codex, and other agent platforms with production-ready capabilities for content generation, application building, product deployment, and real-world workflow automation. By providing a unified, modular skills layer, SkillBoss helps AI agents move beyond text and reliably execute real-world tasks at scale.

## Features

- Deploy websites to Cloudflare Workers
- Auto-provision D1/KV/R2 databases
- Stripe payments integration
- Google OAuth / Email OTP authentication
- AI Image/Audio/Video generation
- Email sending
- Web scraping and search

## Get Started

### 1. Get API Key

Visit [skillboss.co](https://skillboss.co) to sign up and obtain your API key.

### 2. Configure

Replace the placeholder in `skillboss/config.json`:

```json
{
  "apiKey": "sk-your-real-api-key-here"
}
```

### 3. Install

#### Auto Install (macOS/Linux)

```bash
bash ./skillboss/install/install.sh
```

#### Manual Install

Copy the `skillboss/` folder to your AI tool's skills directory:

**Global Installation (auto-detected)**

| Platform | Path |
|----------|------|
| Claude Code | `~/.claude/skills/` |
| Codex CLI | `~/.codex/skills/` |
| OpenClaw | `*/openclaw/skills/` |
| Continue.dev | `~/.continue/` |

**Project-Level Installation (manual)**

| Platform | Path |
|----------|------|
| Cursor | `.cursor/rules/` |
| Windsurf | `.windsurf/rules/` |
| Cline | `.clinerules/` |

## Quick Usage

Ask your AI agent to:

- "Deploy a landing page to Cloudflare Workers"
- "Create an e-commerce site with Stripe checkout"
- "Generate an AI image for my blog post"
- "Send an email notification"
- "Scrape product data from a website"

## Documentation

See `skillboss/SKILL.md` for complete documentation.

## License

Apache 2.0
