# Helena Park

**말로만 · 폰 하나로 · 누나를 위해** — *words only · one phone · for my sister.*

> **A one-woman media company — and a 24/7 care system — running on a single smartphone.**
> One old Galaxy S21 · ~$20 a month · no servers · no team · no investors.
> **489 commits · 893 files · 129 notebooks · 8 shipped systems · 3 weeks.**

> **Flagship: a Mobile-First Multi-Platform Content Foundry Boilerplate — powered by Termux/PRoot & MCP.**

![hardware](https://img.shields.io/badge/hardware-1%C3%97%20Galaxy%20S21-9cf) ![cost](https://img.shields.io/badge/cost-~%2420%2Fmonth-success) ![commits](https://img.shields.io/badge/commits-489-blue) ![systems](https://img.shields.io/badge/systems-8%20shipped-brightgreen)

---

## The origin

**Made in Korea — by a native South Korean developer. Not a transplant, not a rebrand.**

No M3 Max in a Palo Alto garage. No A100 cluster. No runway, no team, nothing to perform.

One developer, in Korea (Incheon/Seoul), on **one old Galaxy S21** — Termux + PRoot as the only PC — shipping a global boilerplate for **~$20 a month**. One reason to keep going: a sister to care for.

The code is global, so the world can fork it. The story is Korean, because that's the truth. **Both are the point.**

---

## The flex

- **Zero PC** — runs 100% on an Android smartphone (Galaxy S21). No desktop, no server.
- **MCP-Driven Verification** — every step hard-checked by `returncode == 0`. No agent hallucinations.
- **Resilience First** — a preflight system that self-heals quotas, cookies, and sessions before publishing.
- **Multi-Channel Pipeline** — Git SSOT → PWA / Tistory / YouTube / Telegram gate / bait channels.

## One phone. The whole stack.

| Layer | What actually runs on it |
|-------|--------------------------|
| **AI agents** | Claude Code · Grok · Aider — three agents that write, design, and patch code |
| **Voice studio** | TTS (Piper · Edge TTS) + RVC voice cloning |
| **Video factory** | URL → short-form film: Ken Burns motion, color grade, burned-in captions |
| **Publishing** | Markdown → PWA webzine → Tistory / Naver / Threads, fully automated |
| **Broadcast** | YouTube OAuth uploads, 5 Telegram bots, Discord reporting |
| **Care system** | A care daemon + a Tailscale mesh — remote care for the person I love |
| **Infra** | GitHub Actions CI, reusable workflows, one-command self-healing sessions |

## The repos

| Repo | What it does |
|------|-------------|
| [**helena_phone**](https://github.com/helena751107/helena_phone) | The hub & boilerplate — the whole studio, ready to fork. |
| [**helena-piano**](https://github.com/helena751107/helena-piano) | A classical-music webzine — piano rendered on-device + reviews & interviews. |
| [**helena-metalcare**](https://github.com/helena751107/helena-metalcare) | Getting to truly know my sister's schizophrenia — voices as audio, a doctor's counsel. |
| [**helana-faith**](https://github.com/helena751107/helana-faith) | Faith as fantasy — a doubting Thomas seeking belief through doubt, not doctrine. |
| [**helana_log**](https://github.com/helena751107/helana_log) | How Helena lives — the care daemon, from design to daily life. |

## Why people fork it

- **The moat is performance, not code.** Everything reproducible is published. What you can't copy is that I actually lived this story.
- **The cost is the flex.** One phone, $20 a month. If a studio runs on hardware you'd recycle, so can yours.
- **It's a curriculum, not a résumé.** Every decision, every conversation, every notebook is public — all 129 of them.

## The honest part

This isn't a money-grab automation account. It's a **turn-key system** — built by a developer, gifted to the person it's for:

- **Care, not clicks.** A care daemon watches over my sister 24/7; the publishing runs on the same phone.
- **Open and owned.** Every line of code, every decision, every notebook is public. MIT-licensed, one owner, one team.
- **Resilient, not flashy.** Preflight checks, `returncode == 0` gates, self-healing sessions — built to survive, not to impress.
- **One phone, $20.** No burn-rate, no investors, nothing to hide. Just family care, made into a product.

> The moat isn't the code — it's that this story is actually true.

## The roadmap

Three acts — from the lowest hardware to the warmest purpose.

**Act I · Seed (done).** One Galaxy S21, Termux/PRoot. A care daemon for my sister + a mobile-first content foundry, running today.

**Act II · Spread (next).** Global open source — forks, issues, and citations from the indie scene (Reddit · GitHub · Hacker News). Then public-good proof: national / public R&D validation, so "it works" is a verified fact, not a claim.

**Act III · Sublimate (north star).** A humanism project — *AI for the marginalized*: care technology that lifts up the overlooked, on hardware anyone can afford. The kind of work measured not by specs, but by **who it saves**.

> The direction isn't technical. It's human — the lowest hardware, the warmest purpose, the widest reach.

## One-command setup

```bash
# On your phone (Termux/proot) — one line:
curl -sL https://raw.github.com/helena751107/helena_phone/main/g/install.sh | bash

# Full bootstrap — make it yours:
git clone https://github.com/helena751107/helena_phone.git
cd helena_phone && bash navigator.sh
```

> **Cite this:** Helena Park — *"Words only · One phone · For my sister"*, a one-person media studio on a single smartphone. <https://github.com/helena751107>
