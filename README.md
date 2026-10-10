<div align="center">

# Hi, I'm Jesse Hades Hall

**Founder of AngryVibes LLC, building [Shippin.ai](https://shippin.ai).**
I build AI infrastructure you can own: retrieval and reasoning engines, agent runtimes,
identity, and the tools that tie them together. I mostly work in Rust, TypeScript, and Go.

[![Shippin.ai](https://img.shields.io/badge/shippin.ai-visit-0E75B6?style=flat-square&logo=rocket&logoColor=white)](https://shippin.ai)
![Contributions](https://img.shields.io/badge/contributions-1%2C670%2B%20since%202024-2ea44f?style=flat-square)
![Pull requests](https://img.shields.io/badge/pull%20requests-364-8957e5?style=flat-square)
![Repositories](https://img.shields.io/badge/original%20repos-185-f0883e?style=flat-square)

</div>

---

## Highlights

- **Founded AngryVibes LLC** and am building Shippin.ai, a self-owned stack that covers identity, secrets, DNS, hosting, and AI tooling.
- **Built RRO**, a self-contained Rust retrieval-and-reasoning engine that needs no external database, vector store, or model gateway. I benchmarked it on BEIR nfcorpus with a real embedding model (Qwen3-Embedding-4B) and published those measured numbers in place of the earlier synthetic ones.
- **Designed the RRFlow runtime substrate**, which makes agent reasoning observable and enforceable. It uses bi-temporal claims with provenance, a hash-chained runtime cursor, and replayable traces.
- **Run my own local AI lab** on NVIDIA DGX Spark (GB10). It covers llama.cpp builds for Vulkan, CUDA, and CPU, Rust inference with Candle and ONNX Runtime, and GPU-trained, CPU-served ModernBERT models.
- **Ship across the whole stack**: TypeScript web apps, native Rust desktop apps (egui, Tauri, Yew), Go services, and Blender-authored avatars.
- **1,670+ contributions and 364 pull requests since 2024**, across 185 original repositories.

## Featured open source

| Project | What it is | Stack |
|---|---|---|
| [**RRO: Reason Ready Objects**](https://github.com/EonsofStupid/rrobjects) | Embedded, tokio-native retrieval-and-reasoning engine. Combines hybrid ANN + BM25 recall and reranking with a classifier that judges whether what it found is enough to reason on. | Rust |
| [**RRFlow / Vyrm**](https://github.com/rrflow/rrflow) | Runtime substrate for Connectome: bi-temporal claims, atomic typed commits, and hash-chained replay that make an agent's work auditable. | Rust |
| [**Connectome**](https://github.com/EonsofStupid/rrflow-connectome) | Native desktop control surface for RRFlow runtimes, with a query studio, graph and JSON lenses, a data-model designer, and run replay. | Tauri · TypeScript |
| [**Qortek**](https://github.com/EonsofStupid/Qortek) | Public "durable brain" layer: Reason Ready Objects, graph lineage, fork → deliberate → commit → foldback workflows, and vector-recall alignment. | Rust |
| [**qdrantrs-port**](https://github.com/EonsofStupid/qdrantrs-port) | Embeddable Qdrant library for running vector search in-process. A modernized fork of tyrchen/qdrant-lib, updated to Rust 2024 with multi-tenant support and aligned with Qdrant v1.16. | Rust |
| [**Tessera**](https://github.com/EonsofStupid/tessera) | Standalone identity and access platform covering users, orgs, OIDC/OAuth, SAML, federation, sessions, and audit. | Go |
| [**DeepDive**](https://github.com/EonsofStupid/deepdive) | Agent skills that use conversation forking as a design tool, for Claude Code, Codex, and Cursor. Installs with one line. | Shell |
| [**Clyffy Avatar**](https://github.com/EonsofStupid/Clyffy_Avatar) | Blender-authored character pack exported to VRM, with an offline drive contract for local voice. | Python · Blender |

## In development (private)

Products I'm building under Shippin.ai and AngryVibes:

| Product | What it does |
|---|---|
| **Nomen** | Identity provider you own: auth, federation, and seat tokens |
| **Vaultix** | Secrets, certificates, and privileged access management |
| **Willandra** | DNS: zones, records, and an AI specialist |
| **Zuul** | Peer-to-peer MCP mesh service |
| **Chatmaton** | AI kernel with subscription and API-usage metering, shared across my products |
| **Clyffy / ClyffyOS** | AI persona plus a headless Rust inference daemon |
| **DevPulse Labs** | Rust/egui studio for AI-guided content: guides, sessions, video, and image editing |
| **ColdLight** | Design system and visual page builder driven by Style Dictionary |
| **FluxCap** | Live-stream engine for the AngryVibes and Shippin community |

## Tech stack

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![SurrealDB](https://img.shields.io/badge/SurrealDB-FF00A0?style=flat-square&logo=surrealdb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![NVIDIA CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white)

## GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=EonsofStupid&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=github_dark" />
    <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=EonsofStupid&show_icons=true&count_private=true&include_all_commits=true&hide_border=true" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=EonsofStupid&hide_border=true&theme=github-dark-blue" />
    <img height="170" alt="Contribution streak" src="https://streak-stats.demolab.com?user=EonsofStupid&hide_border=true" />
  </picture>
</p>

---

<p align="center"><sub>Most of my work lives in private repos. Find me at <a href="https://shippin.ai">shippin.ai</a>.</sub></p>
