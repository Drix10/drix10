<div align="center">

**`drishtant@ghosh:~$`** `whoami`

# Drishtant Ghosh · Drix10

*20 · serial founder · AI systems engineer · building since 2019*

Bengaluru, India &nbsp;·&nbsp; B.Sc. Cybersecurity @ Dayananda Sagar University &nbsp;·&nbsp; building till it's fun

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/drix10)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ggdrishtant@gmail.com)
[![Website](https://img.shields.io/badge/drix10.com-6C5CE7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://drix10.com/)
[![CosLynx](https://img.shields.io/badge/CosLynx.com-FF6B35?style=for-the-badge)](https://coslynx.com)
[![IdolChat](https://img.shields.io/badge/IdolChat.app-8B5CF6?style=for-the-badge)](https://idolchat.app)
[![Followers](https://img.shields.io/github/followers/Drix10?style=for-the-badge&logo=github&label=followers&color=181717)](https://github.com/Drix10?tab=followers)

[**now**](#-now) · [**projects**](#-projects) · [**experience**](#-experience) · [**hackathons**](#-hackathons) · [**journey**](#-journey) · [**stack**](#-stack) · [**connect**](#-connect)

</div>

<br>

<div align="center">

| **$15K ARR** | **5M+** | **400+** | **3** |
|:---:|:---:|:---:|:---:|
| at 16 yrs old, acquired | bot interactions<br>(ReeF + Uchiha Bot) | MVPs shipped<br>via CosLynx | hackathon<br>rounds in 2026 |

</div>

<br>

## ▸ now

```json
{
  "name"    : "Drishtant Ghosh",
  "alias"   : "Drix10",
  "base"    : "Bengaluru, Karnataka, India",
  "studying": "B.Sc. Cybersecurity @ Dayananda Sagar University (2026–2029)",
  "current" : ["Agent Flow", "MiroHedge", "Keystroke-LLM", "IdolChat.app"],
  "focus"   : ["AI systems", "agent infrastructure", "security", "research + trading"],
  "status"  : "building till it's fun"
}
```

<br>

## ▸ projects

> `ls ./projects/ --sort=recent` &nbsp;·&nbsp; star counts and versions below are live badges.

### Flagship

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Agent Flow](https://github.com/Drix10/agent-flow)

**Run AI coding agents unattended without letting them go loose.**

One agent implements, another reviews, a third runs QA, and a guard blocks what they must never touch. You come back to a draft PR and a short list of what needs you.

- Context-drift detection, protected paths, secret/read restrictions
- Mechanical risk classification and policy gates
- Hash-chained, tamper-evident audit log
- Works with Claude Code, Codex, Gemini CLI, Cursor, Copilot, Windsurf, Pi and any tool that reads `AGENTS.md`
- Zero runtime dependencies · MIT

`TypeScript` `Node.js` `CLI` `AI agent tooling`

```bash
npx @drix10/agent-flow scan
```

[![npm](https://img.shields.io/npm/v/@drix10/agent-flow?style=flat-square&color=CB3837&logo=npm)](https://www.npmjs.com/package/@drix10/agent-flow)
[![downloads](https://img.shields.io/npm/dm/@drix10/agent-flow?style=flat-square&label=installs%2Fmo)](https://www.npmjs.com/package/@drix10/agent-flow)
[![stars](https://img.shields.io/github/stars/Drix10/agent-flow?style=flat-square&logo=github)](https://github.com/Drix10/agent-flow)

</td>
<td width="50%" valign="top">

#### 📈 [MiroHedge](https://github.com/Drix10/hypothesis-arena)

**An AI-assisted systematic fund that trades the slow spread of news between linked firms.**

News about one company reaches its suppliers, customers and peers late. The *Connected Drift Book* combines link propagation, filing-text change and insider buys, while deterministic code sizes, risks and executes every trade.

- **Models read, code decides**: a model never sizes, orders or touches an exit
- **HOLD is the default**: stale data or conflicting evidence means no trade
- Hash-chained trial ledger; strategies must pass net-of-cost, search-adjusted gates (deflated Sharpe, overfitting probability, 2x cost test)
- C++17 risk/execution kernel · Alpaca paper transport

`C++17` `Python` `Alpaca` `research/statistics`

**Paper only · no real money · no strategy has passed a gate yet**

[![stars](https://img.shields.io/github/stars/Drix10/hypothesis-arena?style=flat-square&logo=github)](https://github.com/Drix10/hypothesis-arena)
[![site](https://img.shields.io/badge/mirohedge.com-111?style=flat-square)](https://www.mirohedge.com/)

</td>
</tr>
</table>

### Security, payments & product builds

| Project | What it does | Signal |
|---|---|---|
| [**Sentinel**](https://github.com/Drix10/sentinal)<br>`TypeScript` `AST` `Gemini` | Application-security CLI: compiles code into an IR and knowledge graph, synthesizes multi-hop attack graphs, then applies AI patches only after zero-breakage verification, with snapshot rollback. SARIF export for GitHub Code Scanning. | **NYC Code Quest live round: #3** · [`npm i -g sentinel-ai-cli`](https://www.npmjs.com/package/sentinel-ai-cli) |
| [**PayScope**](https://github.com/Drix10/payscope)<br>`TypeScript` `React` `Supabase` `Razorpay` | Autonomous payment-operations platform: signed Razorpay webhooks become incident timelines, a Supervisor / Risk Analyst / Recovery Planner investigation, deterministic recovery selection, transactional-outbox execution and callback reconciliation. | **13 safety gates · <50ms SSE feed** · Razorpay AI Buildathon |
| [**Intent Canvas**](https://github.com/Drix10/intent-canvas)<br>`TypeScript` `React` `Vite` `Zod` | Browser-first spatial workspace where datasets, documents and intent compile into an inspectable plan you approve before anything runs. | **4 execution capabilities** · [live demo](https://intent-canvas.vercel.app/) |
| [**IdolChat.app**](https://idolchat.app)<br>`React Native` `Expo` `Prisma` `Redis` | AI character mobile game: create characters, chat with them and collect cards through daily drops. | **~1,000 waitlist** |
| [**YourResume**](https://github.com/Drix10/YourResume)<br>`React` `Vite` `TypeScript` | AI resume builder that merges GitHub and LinkedIn profile data into tailored, ATS-oriented resumes. | [live app](https://your-resume-ai.vercel.app) · ![stars](https://img.shields.io/github/stars/Drix10/YourResume?style=flat-square&label=%E2%98%85) |

### ML, hardware & research experiments

| Project | What it does | Signal |
|---|---|---|
| [**Keystroke-LLM**](https://github.com/Drix10/keystroke-llm)<br>`Python` `NumPy` `USB HID` | A character-level Transformer written from scratch in pure NumPy that predicts your next key locally and lights it up on a Kreo Hive 75 through a reverse-engineered EVision V2 HID protocol. Includes a gaming-mode toggle and a mock mode for no hardware. | **207K training chars · 82 keys mapped** · offline, nothing leaves the device |
| [**Night-Hunt**](https://github.com/Drix10/ml-videos)<br>`Python` `PyTorch` `Pygame` | First project in *ml-videos*, a lab for real training runs rendered as watchable videos: one shared, evolving brain controls 32 mice against an owl and gains six senses through staged training. | **9-unit MLP · genetic algorithm** · replayable checkpoints |
| [**Grind**](https://github.com/Drix10/Grind)<br>`C` | 100 programs to finish, in order, before touching LeetCode or DSA: basics, then moderate, then challenge. | ![stars](https://img.shields.io/github/stars/Drix10/Grind?style=flat-square&label=%E2%98%85) |

### Automation & knowledge systems

| Project | What it does | Signal |
|---|---|---|
| [**ai-resources**](https://github.com/Drix10/ai-resources)<br>`Next.js` `LLMs` `GitHub Actions` | An automated technical knowledge base: a pipeline scrapes curated X/Twitter lists, distills each signal into a quality-gated article and syndicates it to GitHub, [blogs.drix10.com](https://blogs.drix10.com), DEV.to and Medium. Powered by [`ai-resources-pipeline`](https://github.com/Drix10/ai-resources-pipeline). | ![stars](https://img.shields.io/github/stars/Drix10/ai-resources?style=flat-square&label=%E2%98%85) ![forks](https://img.shields.io/github/forks/Drix10/ai-resources?style=flat-square&label=forks) · **41 categories · 200+ editions** |
| [**ReeF DM Bot**](https://github.com/Drix10/instagram-ai)<br>`Node.js` `Gemini` `MongoDB` | Instagram DM companion that turns educational Reels into weekly study schedules, notes and reminders using transcription and LLM workflows. | production-oriented automation stack |
| [**autoposter**](https://github.com/Drix10/autoposter)<br>`Node.js` `Discord` | Discord bot that downloads Instagram reels and reposts them to multiple accounts with custom overlays. | ![stars](https://img.shields.io/github/stars/Drix10/autoposter?style=flat-square&label=%E2%98%85) |
| [**PyAdvisor**](https://github.com/Drix10/PyAdvisor)<br>`Python` `Hugging Face` | Terminal career advisor that analyzes your GitHub activity and generates guided skill recommendations. | ![stars](https://img.shields.io/github/stars/Drix10/PyAdvisor?style=flat-square&label=%E2%98%85) · CLI-first |
| **ReeF Bot** *(acquired)*<br>`Discord.js` `Mongoose` | Anime character collection and battling Discord game, built from scratch and run at scale. | **$15K ARR · 5M+ interactions · acquired Aug 2024** |

<br>

## ▸ experience

<details open>
<summary><b>Canopy × Founders Inc.</b> &nbsp;·&nbsp; AI Systems Engineer &nbsp;·&nbsp; <i>Apr 2026 – May 2026</i></summary>
<br>

Architected an autonomous multi-agent trading platform with four LLM agents in distinct methodology roles, real-time market streaming, persistent state and compliance logging.

</details>

<details open>
<summary><b>CosLynx.com</b> &nbsp;·&nbsp; Founder & CEO &nbsp;·&nbsp; <i>May 2024 – May 2025</i></summary>
<br>

Built and operated an AI code-generation platform where users shipped **400+ MVPs**. Wrote the core LLM orchestration system in TypeScript/Node.js. 🏆 Backdrop Build v4 Finalist · 🏆 Backdrop Build v6 Finalist.

</details>

<details open>
<summary><b>ReeF</b> &nbsp;·&nbsp; Ex-CEO, <i>acquired</i> &nbsp;·&nbsp; <i>Apr 2022 – Aug 2024</i></summary>
<br>

Anime collecting and battling Discord game. **$15K ARR, 5M+ interactions**, acquired in August 2024.

</details>

<details>
<summary><b>Freelance</b> &nbsp;·&nbsp; Software Engineer &nbsp;·&nbsp; <i>Oct 2019 – Apr 2023</i></summary>
<br>

Node.js applications, Discord bots, automation and open-source work.

</details>

<br>

## ▸ hackathons

| | Event | Project | When | Result |
|:-:|---|---|---|---|
| 🏆 | Backdrop Build v4 | CosLynx | Jun 2024 | Finalist · AI MVP generator |
| 🏆 | Backdrop Build v6 | CosLynx | Aug 2024 | Finalist · YC application cycle |
| ⚡ | NYC Code Quest | Sentinel | Jul 2026 | #3 in the 8-hour live security round |
| ⚡ | OpenAI Codex Hackathon | Intent Canvas / Revenue Rescue | Aug 2026 | Top 60 of 2,000+ applicants, Bengaluru |
| ⚡ | Razorpay AI Buildathon | PayScope | Aug 2026 | Autonomous payment-operations agent |

<br>

## ▸ journey

```text
* 2026 Oct ── Agent Flow v1.2.5: 14 install targets, npm package, ~2.8K installs
* 2026 Oct ── MiroHedge: Connected Drift research program, paper-only
* 2026 Sep ── Keystroke-LLM: NumPy Transformer + physical keyboard inference
* 2026 Aug ── B.Sc. Cybersecurity started @ Dayananda Sagar University
* 2026 Aug ── PayScope: autonomous payment-ops agent
* 2026 Aug ── Intent Canvas: Codex Hackathon, Top 60
* 2026 Jul ── Sentinel: NYC Code Quest live round, #3
* 2026 Apr ── Canopy @ Founders, Inc.: autonomous multi-agent trading
* 2026 Jan ── IBM AI Engineering Professional Certificate
│
* 2025 May ── IdolChat.app: AI character game
│
* 2024 Aug ── ReeF ACQUIRED · Backdrop Build v6 Finalist
* 2024 Jun ── Backdrop Build v4 Finalist: CosLynx
* 2024 May ── CosLynx.com founded
│
* 2022 Apr ── ReeF founded: anime battle Discord game
* 2021 ──── Uchiha Bot → 500K+ interactions
* 2019 ──── first commit. Node.js. never stopped.
```

<br>

## ▸ stack

<div align="center">

[![Stack](https://skillicons.dev/icons?i=ts,js,py,java,c,cpp,react,nextjs,nodejs,express,vite,tailwind,prisma,aws,gcp,docker,kubernetes,vercel,githubactions,supabase,postgres,mongodb,redis,sqlite,jest,vitest,playwright,sentry&perline=14)](https://skillicons.dev)

</div>

<details>
<summary><b>full list</b></summary>

```sh
LANGUAGES=( TypeScript JavaScript Python SQL Java C C++ )

FRAMEWORKS=( React.js Next.js "React Native" Expo "Node.js" "Express.js"
             Vite "Tailwind CSS" Prisma Zod LangChain
             "Hugging Face Transformers" PyTorch NumPy )

INFRA=( AWS GCP Docker Kubernetes Vercel "GitHub Actions" Supabase )

DATABASES=( PostgreSQL MongoDB Redis SQLite LibSQL TursoDB )

TOOLS=( Jest Vitest Playwright Sentry JWT bcryptjs WebSockets Sharp Helmet
        hidapi "Payment APIs" "LLM APIs" SSE Nodemailer )
```

</details>

<br>

## ▸ certifications

**IBM AI Engineering Professional Certificate** &nbsp;·&nbsp; Issued January 2026 &nbsp;·&nbsp; Credential ID `7P0EYJX1P5NN`

<br>

<div align="center">

## ▸ connect

```bash
$ ./connect.sh
```

**Open to:** AI Systems · Agent Infrastructure · Full-Stack AI · LLM · Security · Research Systems · Founding Engineer roles + collabs

[![LinkedIn](https://img.shields.io/badge/linkedin.com/in/drix10-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/drix10)
[![Email](https://img.shields.io/badge/ggdrishtant@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ggdrishtant@gmail.com)

*`EOF`*

</div>
