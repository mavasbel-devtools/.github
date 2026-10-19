# Developer Tools & Autonomous Agent Ecosystem

High-performance developer tooling, AI coding-agent plugins, Model Context Protocol (MCP) servers, and local-first workflow infrastructure developed by [Marco Vásquez Beltrán](https://github.com/mavasbel).

[![Architecture](https://img.shields.io/badge/Architecture-Hexagonal_%2F_Ports_%26_Adapters-blue?style=flat-square)](#engineering-principles)
[![Design](https://img.shields.io/badge/Design-Strict_SOLID-059669?style=flat-square)](#engineering-principles)
[![Local-First](https://img.shields.io/badge/Privacy-Local--First_%26_Zero--Telemetry-7c3aed?style=flat-square)](#engineering-principles)

---

### 🛠️ Repositories & Tooling Landscape

#### Open Source & Platform Contributions

* [**opencode**](https://github.com/mavasbel-devtools/opencode) — Maintained fork of [anomalyco/opencode](https://github.com/anomalyco/opencode), incorporating specialized upstream contributions, enhanced plugin lifecycles, and agent execution harnesses.

#### Private Agent Tooling Ecosystem

The organization maintains an integrated suite of private developer infrastructure designed for high-assurance local execution:

* **OpenCode Agent Plugins:**
  Modular plugins for autonomous coding environments, featuring zero-overhead authentication relays, token budget optimizers, and deterministic context checkpointers.
* **Model Context Protocol (MCP) Servers:**
  High-throughput realtime desktop and messaging protocol adapters bridging agents with communication channels and secure local services.
* **Account & Proxy Infrastructure:**
  Credential isolation, quota management, and rate-limiting proxies for multi-model developer environments.

---

### 📐 Engineering Principles

All tooling developed within this organization adheres to strict engineering invariants:

1. **Hexagonal Architecture (Ports & Adapters):** Complete separation of pure domain logic from inbound drivers (CLI, API) and outbound infrastructure adapters.
2. **Construction & Composition Inversion:** Zero direct instantiation in business logic; all dependencies are wired at composition entry points.
3. **Local-First & Zero Telemetry:** Tooling executes locally with verified boundaries, keeping developer context private and secure.
4. **Deterministic Testing:** 100% measured coverage requirements for core domain abstractions and end-to-end integration contracts.

---

> [!NOTE]
> This organization is independent and is not officially affiliated with OpenCode, model providers, or third-party messaging platforms.
