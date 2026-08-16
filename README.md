# Hi, I'm Pankaj 👋

Full-stack developer at **Mobiux Labs**. I build web products end to end — Next.js and React on the
front, Node/Fastify, Django and FastAPI behind them — and I spend most of my spare time building
AI systems and shipping them properly rather than leaving them as demos.

Based in India. Open to remote work.

---

## What I've built

### [Agent-Daemon](https://github.com/pankaj-mahaur/Agent-Daemon) · open source, MIT
A runtime that gives AI coding agents memory and lets several of them work in parallel.

- Agents run in isolated **git worktrees** and coordinate through atomic message files — no server,
  no database, no API key required
- Memory is **SQLite + FTS5** on a reinforce → decay → consolidate lifecycle, served back through an
  **MCP server** with progressive disclosure so recall stays cheap
- Agent transcripts are untrusted input, so injection attempts are quarantined by a **deterministic
  screen** rather than asking a model to police itself
- **301 tests**, GitHub Actions CI on Linux, macOS and Windows
- Adapters for Claude Code, Codex and Cursor

`Node.js · TypeScript · SQLite · MCP · git worktrees`

### [AyurNod](https://ayurnod.in) · live
A health platform I built alone across three surfaces from one npm-workspaces monorepo.

- **Expo/NativeWind** mobile app, **Next.js** website, **Fastify + TypeScript** API, shared types package
- The AI layer falls back across models when one fails, and runs a multi-agent diagnostic pipeline
- A guardian module detects emergencies and interrupts the conversation — the interesting problem in
  health AI isn't the model, it's knowing when to stop it
- Runs on Postgres, Redis and PM2 on a VPS I manage

### [Aurum & Isle](https://aurumisle.com) · live, taking real payments
A store I migrated off Shopify onto self-hosted **Medusa**, and now run myself.

- Next.js storefront against a Medusa API, Postgres 16 and Redis on one VPS I administer
- Cards, UPI, netbanking and wallets — verified with real orders, not test mode
- I own the whole thing: DNS, TLS, deploys, admin

### Genfield · in development
An AI studio with six workspaces — image, video, lip sync, cinema, voice and avatar — orchestrating
around thirty models behind one interface, with your brand kit and history following you between
them. The Cinema workspace models real optical physics per shot instead of showing you a prompt box.
Designed to be self-hosted with your own inference key.

`Next.js · React · TypeScript · Supabase`

### OpenCreator · in development
A serverless-GPU pipeline for lip-synced avatar video — MuseTalk and GPT-SoVITS voice cloning across
RunPod workers, split into web/worker/storage packages.

---

## At work

- **Sole developer on two client platforms** — built on Next.js 16, React 19 and Tailwind v4,
  static-first with a CI check that fails the build if a route stops being prerendered
- Built a **RAG chat** on a client platform: hybrid keyword and semantic retrieval over Typesense and
  OpenAI, streamed over SSE with cited sources, with search clients split by trust boundary so admin
  keys can't reach a browser bundle
- Top contributor on an internal **Django + Celery + Postgres + Redis** platform and its Next.js front end
- Worked on an AI car-buying assistant: **FastAPI** and async SQLAlchemy, OpenAI function calling,
  Gemini for reading VINs from photos, realtime voice over WebRTC

---

## Stack

**Front end** — Next.js (App Router, Server Components), React, React Native + Expo, TypeScript, Tailwind
**Back end** — Node, Fastify, Django, Celery, FastAPI, Postgres, MongoDB, SQLite, Redis, Prisma, Typesense
**AI** — RAG & hybrid search, agent orchestration, MCP servers, model fallback chains, realtime voice, prompt-injection guards
**Platform** — Git, GitHub Actions, Docker, PM2, Nginx, VPS administration, Vercel, Supabase, Payload CMS

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/pankaj-mahaur) · pankajmahaur2003@gmail.com

Outside code: badminton (university gold medal, doubles), photography, and cooking things I haven't
made before.

---

## ⚡️ Fun Fact

Outside coding, I enjoy badminton, photography, and experimenting with cooking.

---

### 💬 Random Dev Quote

![Random Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pankaj-mahaur/pankaj-mahaur/output/pacman-contribution-graph-dark.svg">
 <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pankaj-mahaur/pankaj-mahaur/output/pacman-contribution-graph.svg">
 <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/pankaj-mahaur/pankaj-mahaur/output/pacman-contribution-graph.svg">
</picture>
