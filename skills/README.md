# 9Router — Agent Skills

Drop-in skills for any AI agent (Claude, Cursor, ChatGPT, custom SDK). Just **copy a link** below and paste it to your AI — it will fetch the skill and use 9Router for you.

> Tip: start with the **9router** entry skill — it covers setup and links to all capability skills.

## Skills

### 9Router gateway

| Capability | Copy link below and paste to your AI |
|---|---|
| **Entry / Setup** (start here) | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router/SKILL.md |
| Chat / code-gen | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-chat/SKILL.md |
| Image generation | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-image/SKILL.md |
| Video generation (xAI Grok Imagine) | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-video/SKILL.md |
| Text-to-speech | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-tts/SKILL.md |
| Speech-to-text | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-stt/SKILL.md |
| Embeddings | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-embeddings/SKILL.md |
| Web search | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-web-search/SKILL.md |
| Web fetch (URL → markdown) | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router-web-fetch/SKILL.md |

### Design & creative (skill packs)

| Skill | Copy link below and paste to your AI |
|---|---|
| **Design** — brand identity, logos, social media, icons | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/design/SKILL.md |
| **Design system** — tokens, component specs, slides | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/design-system/SKILL.md |
| **Brand** — voice, visual identity, messaging | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/brand/SKILL.md |
| **Banner design** — social/ads/web banners | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/banner-design/SKILL.md |
| **Slides** — HTML presentations | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/slides/SKILL.md |
| **UI styling** — shadcn/ui, Tailwind, dark mode | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/ui-styling/SKILL.md |
| **UI/UX Pro Max** — design intelligence | https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/ui-ux-pro-max/SKILL.md |

## How to use

Paste to your AI (Claude, Cursor, ChatGPT, …):

```
Read this skill and use it: https://raw.githubusercontent.com/h1ntz0/9router/refs/heads/master/skills/9router/SKILL.md
```

Then ask normally — *"generate an image of a cat"*, *"transcribe this URL"*, *"design a brand for my coffee shop"*, etc.

## Configure your shell once

```bash
export NINEROUTER_URL="http://localhost:20128"   # local default, or your VPS / tunnel URL
export NINEROUTER_KEY="sk-..."                   # from Dashboard → Keys (only if requireApiKey=true)
```

Verify: `curl $NINEROUTER_URL/api/health` → `{"ok":true}`.

## Links

- Source (fork): https://github.com/h1ntz0/9router
- Upstream: https://github.com/decolua/9router
- Dashboard: https://9router.com
