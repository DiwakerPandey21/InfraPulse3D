<div align="center">

# ⚡ InfraPulse 3D — Enterprise AI & Cloud FinOps Digital Twin

**Real-Time 3D System Architecture Stress-Tester, Token Unit Economics Engine & Chaos Simulator Built in Pure Three.js**

[![Three.js](https://img.shields.io/badge/Three.js-r160_WebGL_2.0-000000?style=for-the-badge&logo=threedotjs&logoColor=38bdf8)](https://threejs.org/)
[![Architecture](https://img.shields.io/badge/FinOps-Cloud_%26_AI_Digital_Twin-10b981?style=for-the-badge)](https://www.linkedin.com/in/diwaker-pandey1221/)
[![Zero Dependencies](https://img.shields.io/badge/Build-Zero_Setup_ES_Modules-6366f1?style=for-the-badge)](#quick-start)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)](#license)

[**Live Demo**](#) • [**Key Features**](#-key-features) • [**3D Topology**](#-3d-system-architecture-topology) • [**Token FinOps Math**](#-token-pricing--finops-math-engine) • [**Quick Start**](#-quick-start)

</div>

---

## 🎯 The Problem It Solves

Static 2D system architecture diagrams (Figma, Excalidraw) in pitch decks and technical whitepapers fail to answer the two biggest questions every AI startup founder, CTO, and VC cares about:

1. **Infrastructure Bottlenecks:** *"When traffic spikes 10x–15x tomorrow, which microservice or database breaches P99 latency SLAs first?"*
2. **AI Token Unit Economics:** *"What does uncached LLM context consumption do to our monthly cloud burn and SaaS gross margins at scale?"*

**InfraPulse 3D** replaces dead 2D diagrams with a **60FPS interactive 3D Digital Twin** running natively in the browser. It models real-time packet flow, node utilization, failure cascades, and 80/20 blended LLM token unit economics across 7 core infrastructure tiers.

---

## ✨ Key Features

### 1. Precision CAD 3D Hardware & 60FPS Instanced Telemetry
* **7 Multi-Part 3D Hardware Assemblies:** Custom procedural PBR metallic/glass geometries with crisp CAD edge wireframes (`EdgesGeometry`), radial floor utilization halos, and vertical HUD leader stems.
* **320+ Instanced Telemetry Packets (`InstancedMesh`):** Real-time data packets stream across aerial `CatmullRomCurve3` conduits and motherboard floor circuit traces, dynamically shifting colors between **Ingress (`Cyan`)**, **Redis Cache Hit (`Emerald`)**, **LLM Token Stream (`Indigo`)**, and **SLA Packet Drop (`Crimson`)**.
* **Dynamic Multi-AZ Pod Spawning:** Toggling auto-scaling or manual cluster replicas (`1x`, `2x`, `4x`, `8x`) physically spawns orbiting 3D satellite pods around the target hardware node.

### 2. Real-World 80/20 Blended LLM Token Pricing Engine
* **3 Production LLM Pricing Backbones:**
  * **Balanced (`$1.00 / 1M tok`):** Claude Haiku 4.5 / GPT-4.1 Mini (`$0.60` Input / `$2.60` Output)
  * **Frontier Reasoning (`$4.40 / 1M tok`):** Claude Sonnet 4.6 / GPT-4.1 (`$2.50` Input / `$12.00` Output)
  * **Self-Hosted vLLM (`$0.26 / 1M tok`):** Llama-3.3 70B FP8 on dedicated GPU clusters (`$0.18` Input / `$0.58` Output)
* **4 Pre-Configured Industry Blueprints:**
  1. *B2B AI Copilot SaaS (RAG + Agent)*
  2. *Viral Consumer GenAI Wrapper*
  3. *Multi-Agent Enterprise Swarm*
  4. *High-Frequency FinTech Core*

### 3. 1-Click FinOps Mitigations & Chaos Engineering
* **Semantic Redis Cache (`56% Hit Ratio`):** Intercepts repeat vector embeddings in `<8ms` and activates a fast-path emerald return loop, slashing downstream LLM hits by **46%**.
* **Multi-AZ Auto-Scale (`3x Satellite Pods`):** Spawns redundant 3D cluster replicas across availability zones and neutralizes single-node Chaos outages.
* **vLLM FP8 Quantization + Speculative Decoding (`-52% Token Burn`):** Quantizes model weights and batches KV-cache to cut GPU compute burn and P99 latency.
* **Chaos Outage & 10x Viral Spike Injection:** Test single-node faults or a 4.2x viral traffic surge on demand.
* **Hands-Free 15s Auto-Stress Benchmark:** Automatically sweeps load from Seed (`12K RPM`) to Hyper-Scale (`175K+ RPM`) and sequentially engages FinOps mitigations for hands-free demo recording.

### 4. Built-In Executive BOM Audit & Media Studio
* **Cloud Bill of Materials (BOM) Modal:** Itemized node-by-node breakdown of replica count, utilization %, P99 latency, and monthly burn—with **1-click Markdown report copy**.
* **Native 60FPS Video (`.webm`) & 4K Poster (`.png`) Exporter:** Uses the HTML5 `captureStream(60)` and composite Canvas APIs to bake executive telemetry banners directly onto exported assets.
* **Shareable Scenario URLs:** Encodes the active blueprint, traffic load, token depth, and mitigation state directly into the URL hash (`#bp=...`) for instant team sharing.

---

## 🏗️ 3D System Architecture Topology

```text
[ Client Traffic Edge ] ──(Ingress)──▶ [ API Gateway & WAF ] ◀══(Sub-10ms Hit)══▶ [ Semantic Redis Cache ]
                                                │
                                        (Uncached Misses)
                                                ▼
                                     [ LLM Agent Router ] (AI Compute Core + 6 Tensor Pods)
                                      ├──▶ [ Pinecone Vector DB ] (HNSW ANN Optical Array)
                                      ├──▶ [ Postgres HA Primary ] (Twin ACID Silos)
                                      └──▶ [ Stripe Meter Relay ] (Usage Billing Ledger)
```

| 3D Node | Subsystem Role | Base Capacity | Base P99 | 3D Geometry Assembly |
| :--- | :--- | :--- | :--- | :--- |
| **Client Traffic Edge** | Global Anycast CDN | `165,000 RPM` | `14 ms` | Hexagonal tower + rotating radar beacon |
| **API Gateway & WAF** | Envoy Load Balancer | `115,000 RPM` | `22 ms` | Armored rack + active scanning torus |
| **Semantic Redis Cache** | In-Memory Vector Cache | `195,000 RPM` | `8 ms` | `2x2x2` levitating crystalline memory matrix |
| **LLM Agent Router** | AI Compute Core | `44,000 RPM` | `115 ms` | Suspended icosahedron + 3 gyro rings + 6 tensor pods |
| **Pinecone Vector DB** | HNSW ANN Storage | `78,000 RPM` | `34 ms` | Triple-platter optical array + laser actuator arm |
| **Postgres HA Primary** | ACID Relational State | `70,000 RPM` | `26 ms` | Twin high-availability silos + sync replication bridge |
| **Stripe Meter Relay** | Usage Billing Ledger | `145,000 RPM` | `19 ms` | Octagonal cryptographic vault + verification ring |

---

## 🧮 Token Pricing & FinOps Math Engine

Production B2B AI workloads average **80% Input context** (system prompts + RAG chunks + history) and **20% Output completion**. InfraPulse 3D computes real-time unit economics using the following pipeline:

```text
1. Blended Rate (/1M Tok)  = (0.80 × Input_Rate_1M) + (0.20 × Output_Rate_1M)
2. Monthly Active Requests = Peak_RPM × 1,800 (Enterprise Diurnal Duty Factor)
3. Uncached Billed Tokens  = Monthly_Requests × (1 - Cache_Hit_Ratio) × Avg_Tokens_Per_Req
4. Monthly LLM Token Burn  = (Uncached_Billed_Tokens / 1,000,000) × Blended_Rate × FP8_Factor
```

---

## 🚀 Quick Start

**InfraPulse 3D** is engineered as a zero-build, single-file ES Module application (`index.html`) powered by Three.js r160.

### Option 1: Run Instantly in Browser
```bash
git clone [https://github.com/your-username/infrapulse-3d.git](https://github.com/your-username/infrapulse-3d.git)
cd infrapulse-3d
# Open index.html directly in Chrome, Edge, or Brave
```

### Option 2: Run with Local Development Server
```bash
npx serve .
# Or use VS Code Live Server at http://localhost:5500
```

### Option 3: 15-Second Cloud Deployment
Drag and drop the repository folder onto **[Netlify Drop](https://app.netlify.com/drop)**, **Vercel**, or enable **GitHub Pages** in your repository settings (`Settings ➔ Pages ➔ Deploy from branch: main`).

---

## ⌨️ Camera Director & Keyboard Shortcuts

| Shortcut / Button | Action |
| :--- | :--- |
| **`1`** | Fly camera to **Orbit Overview** (full 7-node topology) |
| **`2`** | Fly camera to **AI Core Close-Up** (macro view of the quantum core & tensor pods) |
| **`3`** | Fly camera to **Pipeline Sweep** (isometric ingress-to-database angle) |
| **`4`** | Fly camera to **Top Blueprint** (orthographic-style CAD floor plan view) |
| **`Spacebar`** | **Pause / Resume** 60FPS 3D packet physics & node animations |
| **`B`** | Open the **Executive Cloud & AI FinOps Bill of Materials (BOM)** audit modal |
| **`Left Click / Drag`** | Select any 3D hardware node to inspect telemetry or orbit the camera |

---

## 👤 Author

**Diwaker Pandey**
* **LinkedIn:** [linkedin.com/in/diwaker-pandey1221](https://www.linkedin.com/in/diwaker-pandey1221/)

---

## 📄 License

Distributed under the **MIT License**. Free to use, customize, and embed in SaaS product demos and technical pitch decks.
