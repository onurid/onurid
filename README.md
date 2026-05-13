# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# github.com/onurid  →  onurid/onurid/README.md
# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Onur Yaşar

**Software Architect · ICF Professional Coach · Antalya, Turkey**

I have been building software systems since 2017. Identity infrastructure, distributed systems and open ecosystems are my core technical focus.

Since June 2024, I also work as an ICF-accredited professional coach — integrating a systems-thinking discipline with coaching competencies to support individuals in clarity, decision-making and sustainable potential.

---

### What I'm building

**[Rymory](https://rymory.org)** — Open identity infrastructure for the open web.
Federation-ready identity layer · AGPL v3 · Built since 2017.

**[Lemoras](https://lemoras.com)** — Application ecosystem powered by Rymory identity.
Notes · Drive · Planner · Passwords · One account, many services.

---

### Other initiatives

- **LuminaCore** — AI-powered real-time energy consumption analysis
- **Ignis Ritual** — Mindfulness ritual experience for modern life
- **Awakening to Reality** — Book project at the intersection of AI and human consciousness *(upcoming)*

---

### Writing

Published in **uWords Magazine** (Issue 11, Oct 2024) — *"Awakening to Reality"*
A piece on social and individual boundaries of reality, forming the foundation of my coaching approach.

---

### Reach me

- 🌐 [onuryasar.org](https://onuryasar.org)
- 🌐 [rymory.org](https://rymory.org)
- 📧 onxorg@proton.me
- 🐦 [@onuryasarorg](https://x.com/onuryasarorg)

---

*"The greatest show in the universe begins the moment you discover your own mind."*


# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# github.com/rymory  →  .github/profile/README.md
# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Rymory

**Open identity infrastructure for the open web.**

Rymory is a federation-ready identity layer — born from real production infrastructure built since 2017. One account, any application, any ecosystem.

Designed for interoperable applications, distributed systems and modern digital trust.
No single company controls the protocol. Governance is open by design.

---

### Repositories

| Repo | Description |
|---|---|
| [rymory-core](https://github.com/rymory/rymory-core) | Identity backend — authenticate, account, role, project (Go) |
| [rymory-gateway](https://github.com/rymory/rymory-gateway) | Edge proxy — JWT, cookie, rate limiting, CORS (Go + Cloudflare) |
| [goutils](https://github.com/rymory/goutils) | Shared Go utilities — JWT, DB, response helpers |

---

### Architecture

```
id.rymory.org          ← single sign-on entry point
      │
      ├── notes.lemoras.com
      ├── drive.lemoras.com
      ├── [any third-party app]
      │
account.rymory.org     ← account management
```

---

**License:** AGPL v3 + Commercial Exception
**Trademarks:** "Rymory" registered with TÜRKPATENT
**Author:** [Onur Yaşar](https://onuryasar.org) · onxorg@proton.me

→ [rymory.org](https://rymory.org)


# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# github.com/lemoras  →  .github/profile/README.md
# ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Lemoras

**Application ecosystem powered by [Rymory](https://rymory.org) identity infrastructure.**

One identity. Many applications. Notes, Drive, Planner, Passwords — all connected through a single federated identity layer.

Built since 2017 as a real production system. The identity backbone that powers Lemoras is now open source as [Rymory](https://rymory.org).

---

### Repositories

| Repo | Description |
|---|---|
| [lemoras-ui](https://github.com/lemoras/lemoras-ui) | Reference frontend — AngularJS SPA, multi-template, config-driven |
| [lemoras-modules](https://github.com/lemoras/lemoras-modules) | Application service modules — notes, drive, planner (Go) |
| [workspace](https://github.com/lemoras/workspace) | Deployment orchestration — private |

---

### Ecosystem

```
notes.lemoras.com     ← note-taking
drive.lemoras.com     ← file storage
planner.lemoras.com   ← tasks & planning
passwords.lemoras.com ← credential vault
```

All services authenticate via `id.rymory.org`.

---

**License:** AGPL v3 + Commercial Exception
**Trademarks:** "Lemoras" registered with TÜRKPATENT
**Author:** [Onur Yaşar](https://onuryasar.org) · onxorg@proton.me

→ [lemoras.com](https://lemoras.com)
