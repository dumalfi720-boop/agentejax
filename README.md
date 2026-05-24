<p align="center">
  <img src="assets/agentejax-hero.webp" alt="AgenteJAX" width="100%">
</p>

# Agentejax

> Practical course in PT-BR for you to build your own personal AI agent from scratch — in TypeScript, running 24/7 on Telegram, with memory, tools and autonomy. No closed framework, no lock-in, with each line being yours.

**[Access the course →](https://inematds.github.io/agentejax/)**

---

## What is it

An interactive course in the duclub format, divided into **3 tracks / 9 modules / 54 topics**, with:

- 🌱 **Track 1 · Fundamentals** — from scratch to the agent responding on Telegram with memory and tools.
- ⚡ **Track 2 · Agent's Life** — 24/7 communication, streaming, voice, autonomy, reflection and self-generated skills.
- 🛡 **Track 3 · Production** — MCP, approvals, defense against prompt injection, costs, dashboard, hosting and testing.

In addition to the course pages, the landing page has an **interactive picker** where you mark the features you want and download a file`.md`with your personalized blueprint — ready to paste into an AI and request the build.

---

## Why not use Hermes or OpenClaw directly?

There are great ready-made agent frameworks. Honest comparison between the two most popular and the approach of this course:

| Appearance | Hermes | OpenClaw | **Agentejax (this course)** |
|---|---|---|---|
| Language | Python | TypeScript | TypeScript |
| Usage model | You install and use | You install and use | You **learn and build** |
| Initial curve | Low | Low | Average (3 tracks) |
| Who understands the code | Their team | Their team | **You** |
| Deep customization | Fork and maintain | Fork and maintain | Direct to your repo |
| Multi-layer memory | Yes (4 layers) | Yes | Yes (3 layers, T1 M1.2) |
| Self-generated skills | Yes (native) | Yes (registry) | Optional (T2 M2.3) |
| Voice | Yes | Yes (mobile) | Optional (T2 M2.2) |
| Message channels | 15+ | 22+ | Telegram (extensible) |
| Multi-agent | Limited | Yes | Out-of-scope (you add) |
| Native mobile client | No | Yes | Telegram is now mobile |
| Action approvals | Trust levels | By command | By command (T3 M3.1) |
| Lock-in | Their roadmap | Their roadmap | **Zero** |
| License | MIT | MIT | MIT |
| When it makes more sense | I want to run today | I want an ecosystem with a store | **I want to understand and own it** |

### Use Agentejax if

- You want to **understand every line** that runs on your agent
- You will depend on this agent in critical tasks
- Want to change models (Claude / GPT / DeepSeek / Ollama) without pain
- Want to add your own tools (CRM, bank, ERP) without touching third-party code

### Use a ready-made one if

- You just want to test the idea in 1 hour
- Don't want to maintain TypeScript code in the long term
- Need ready-made native mobile integrations
- Not interested in understanding how agents work from the inside

---

## Repository structure```
agentejax/
├── index.html                # Landing page com picker e tabela comparativa
├── curso/
│   └── trilha1/
│       ├── index.html        # Index da Trilha 1 — Fundamentos
│       ├── modulo-1-1.html   # Preparação e Ambiente
│       ├── modulo-1-2.html   # Identidade e Memória
│       └── modulo-1-3.html   # Cérebro e Ferramentas
├── README.md
└── LICENSE
```Tracks 2 and 3 arrive in the next iterations.

---

## Run locally

Fully static website, no build. Just open the`index.html`in the browser, or serve with any HTTP server:```bash
# Python (vem instalado em quase tudo)
python3 -m http.server 8000

# Node (se preferir)
npx serve .

# Depois abre http://localhost:8000
```---

## Publishing to GitHub Pages

1. Settings → Pages
2.Source:`Deploy from a branch`3.Branch:`main`/ folder:`/ (root)`4. Save — in ~1 min the site is up`https://inematds.github.io/agentejax/`---

##Roadmap

- [x] Track 1 · Fundamentals (3 complete modules)
- [x] Landing with interactive picker + blueprint download
- [x] Comparison table Hermes × OpenClaw × Agentejax
- [ ] Track 2 · Agent's Life
- [ ] Track 3 · Production
- [ ] Reference code repository (TypeScript) with each implemented module

---

## License

MIT — do what you want. Fork, copy, sell, adapt.