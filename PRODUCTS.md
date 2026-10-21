# Products — selling guide

<p align="center">
  <a href="https://zyvor.dev/products"><img src="https://img.shields.io/badge/Live_catalog-zyvor.dev%2Fproducts-f0583a?style=for-the-badge&labelColor=0c1222" alt="Live catalog"/></a>
  <a href="https://zyvor.dev/compare"><img src="https://img.shields.io/badge/Compare-side_by_side-14b8a6?style=for-the-badge&labelColor=0c1222" alt="Compare"/></a>
  <a href="https://zyvor.dev/schedule"><img src="https://img.shields.io/badge/Demo-Book_now-ff8f3f?style=for-the-badge&labelColor=0c1222" alt="Demo"/></a>
</p>

Canonical pages: **[zyvor.dev/products](https://zyvor.dev/products)** · **[zyvor.dev/compare](https://zyvor.dev/compare)**

---

## Migrate

### Transiva
> Enterprise workload mobility & migration control plane — discover, export, orchestrate.

- **Buy when:** Leaving a proprietary hypervisor / HCI; multi-site export; air-gap bundles  
- **CTA:** [Product](https://zyvor.dev/transiva) · [Trial](https://zyvor.dev/contact?intent=trial&product=transiva) · [Demo](https://zyvor.dev/schedule) · [GitHub](https://github.com/zyvorai/zyvor-transiva)

### Scout
> Migration discovery and readiness before migration risk — inventory, blockers, waves, dashboard.

- **CTA:** [Product](https://zyvor.dev/scout) · [GitHub](https://github.com/zyvorai/scout)

### Chimera
> Infrastructure simulation engine — disposable vSphere persona for Transiva export / NFC tests.

- **CTA:** [Product](https://zyvor.dev/chimera) · [GitHub](https://github.com/zyvorai/chimera)

### h2kvm
> Any hypervisor disk → boot-ready KVM — built for throughput.

- **CTA:** [Product](https://zyvor.dev/h2kvm) · [GitHub](https://github.com/zyvorai/zyvor-h2kvm)

### GuestKit
> Inspect and repair VM disks without booting the guest.

- **CTA:** [Product](https://zyvor.dev/guestkit) · [GitHub](https://github.com/zyvorai/zyvor-guestkit)

---

## Apple Silicon

Mac-native products and the Apple path of the stack: FluxVM drives Apple's Virtualization.framework, so the same API runs from a laptop to a Mac fleet.

| Product | Pitch | Open |
|---------|-------|------|
| **Velora** | VMs, models and clusters on your Mac — Debian, Ubuntu and macOS guests in one click, Console & Command over vsock, local MLX models behind an OpenAI-compatible gateway, k3s, FluxVM, Kairon, fleet of Macs. Pre-release 0.4, BSL 1.1, macOS 26+ | [Site](https://zyvor.dev/velora) · [Releases](https://github.com/zyvorai/velora) |
| **Gryvia for Apple** | Your Macs, scheduled — multi-tenant control plane for Apple Silicon fleets: unified-memory-aware admission, quotas, live GPU cores, model workbench, signed provenance (BUSL-1.1, source-available) | [Site](https://zyvor.dev/gryvia) · [Repo](https://github.com/zyvorai/zyvor-gryvia-apple) |
| **Macora** | Your Mac's network, made clear — native SwiftUI app, Rust CLI and TUI, one-click diagnosis; read-only by default, zero dependencies (Apache-2.0) | [Site](https://zyvor.dev/macora) · [Repo](https://github.com/zyvorai/zyvor-macora) |
| **Nivora** | See every connection on your Mac — per-app flows, DNS, routes, VPNs and FluxVM workloads; local-first, observe-first (BUSL-1.1, source-available) | [Site](https://zyvor.dev/nivora) · [Repo](https://github.com/zyvorai/zyvor-nivora) |
| **Vytrix** | Read-only system activity monitor for macOS and Linux — Liquid Glass UI, apps, processes, ports, containers | [Site](https://zyvor.dev/vytrix) · [Repo](https://github.com/zyvorai/zyvor-vytrix) |
| **Solvor** | Drop a file, get answers, nothing leaves the cell — native Mac app for Keep (Apache-2.0) | [Repo](https://github.com/zyvorai/solvor) |
| **Teryon** | Persistent remote shells over plain OpenSSH — TUI, desktop app, agent-aware panes, file browser, MCP server; Rust (Apache-2.0) | [Repo](https://github.com/zyvorai/teryon) |

---

## Run

| Product | Pitch | Open |
|---------|-------|------|
| **Zeus OS** | Visual infrastructure OS for KubeVirt fleets | [Site](https://zyvor.dev/zeus-os) · [Repo](https://github.com/zyvorai/zeus-os) |
| **Veyron** | Real VMs on Kubernetes — one console, API and CLI; Kairon and FluxVM run them straight on KVM, no pod per VM | [Site](https://zyvor.dev/veyron) · [Repo](https://github.com/zyvorai/veyron) |
| **Kryton** | Windows virtualization — one machine API (demo / dockur lab / KubeVirt) | [Site](https://zyvor.dev/kryton) · [Repo](https://github.com/zyvorai/zyvor-kryton) |
| **Iris** | Application operating layer — one door for every app | [Site](https://zyvor.dev/iris) · [Repo](https://github.com/zyvorai/iris) |
| **Haven** | Identity plane — Keycloak + Postgres as one product | [Site](https://zyvor.dev/haven) · [Repo](https://github.com/zyvorai/zyvor-haven) |
| **Machina** | Private cloud on KVM — VMs, browser consoles, fleet HA/DRS and AI ops from three Rust binaries | [Site](https://zyvor.dev/machina) · [Repo](https://github.com/zyvorai/zyvor-machina) |
| **Zorvia** | The control plane for KubeVirt VMs — CLI, TUI and web console on one API (Apache-2.0) | [Site](https://zyvor.dev/zorvia) · [Repo](https://github.com/zyvorai/zyvor-zorvia) |
| **Zyvor Fabric** | Private cloud control plane for Linux — VMs, networking, storage, security; AI workloads (beta); Keep agent workstation (Apache-2.0) | [Site](https://zyvor.dev/zyvor-fabric) · [Repo](https://github.com/zyvorai/zyvorai-fabric) |
| **Kairon** | Kubernetes-native VM orchestration without KubeVirt or libvirt — Kubernetes declares, Kairon orchestrates, FluxVM executes (Apache-2.0) | [Site](https://zyvor.dev/kairon) · [Repo](https://github.com/zyvorai/zyvor-kairon) |
| **FluxVM** | Run real VMs with a real API — one Rust control plane over Firecracker / Cloud Hypervisor / QEMU-KVM / Apple Virtualization.framework, plus an in-tree hypervisor (Apache-2.0) | [Site](https://zyvor.dev/fluxvm) · [Repo](https://github.com/zyvorai/zyvor-fluxvm) |

---

## Operate

| Product | Pitch | Open |
|---------|-------|------|
| **Axiom** | k8s-native private cloud — k3s → production, one console | [Site](https://zyvor.dev/axiom) · [Docs](https://zyvor.dev/docs/axiom) |
| **Ragnarok** | Confidential computing & attestation for KubeVirt | [Site](https://zyvor.dev/ragnarok) |
| **Atlas** | Storage control plane — one API over Ceph, NFS, ZFS and Longhorn, plus Atlas Native (erasure-coded, Raft-backed, NFS/SMB/S3/CSI, two-way DR) | [Site](https://zyvor.dev/atlas) · [Repo](https://github.com/zyvorai/zyvor-atlas) |
| **PacketWolf** | Every connection → the process that made it | [Site](https://zyvor.dev/packetwolf) |
| **Paqtra** | Free Apache-2.0 community edition of PacketWolf — Cilium-native network observability for Kubernetes (Hubble flows, "why denied?" path investigation, drop analytics, service map, policy simulate). Observe-first, read-only toward the datapath; enforcement stays in Cilium CNPs. Choose when Cilium is already your CNI and you want flows, path investigation and policy preview in one place | [Site](https://zyvor.dev/paqtra) · [Repo](https://github.com/zyvorai/zyvor-paqtra) |
| **Forge** | GPU / AI infrastructure OS on Kubernetes | [Site](https://zyvor.dev/forge) |
| **Zynera** | AI infrastructure control plane — private OpenAI-compatible gateway, evaluation-gated model promotion, RAG, federated training, GPU scheduling and cost control | [Site](https://zyvor.dev/zynera) |
| **Netra** | Standalone eBPF network observability and emergency control for Linux/Kubernetes — kernel drop attribution, live capture, leased deny rules that expire on their own; optional Cilium + Hubble enrichment | [Site](https://zyvor.dev/netra) · [Repo](https://github.com/zyvorai/zyvor-netra) |
| **Rivora** | eBPF-native load balancing for every environment (Apache-2.0) | [Site](https://zyvor.dev/rivora) · [Repo](https://github.com/zyvorai/zyvor-rivora) |
| **Shukra** | eBPF runtime intelligence and security for KVM (Apache-2.0) | [Site](https://zyvor.dev/shukra) · [Repo](https://github.com/zyvorai/zyvor-shukra) |
| **Gryvia** | Kubernetes-native GPU platform for large-model training — GPU-aware admission, RDMA/NVLink and parallel-filesystem operators, quotas, metering | [Site](https://zyvor.dev/gryvia) · [Repo](https://github.com/zyvorai/zyvor-gryvia) |
| **Nuvora** | Self-hosted AI application platform — your models, your knowledge, your control | [Site](https://zyvor.dev/nuvora) · [Repo](https://github.com/zyvorai/zyvor-nuvora) |
| **Zyntra** | Decision intelligence for infrastructure — eBPF, GPU and host signals become ranked, explainable, human-approved actions | [Site](https://zyvor.dev/zyntra) · [Repo](https://github.com/zyvorai/zyvor-zyntra) |
| **Duvora** | DPU fleet control plane — plans, isolation, telemetry, incidents, evidence; simulation-first evaluation release (Apache-2.0) | [Site](https://zyvor.dev/duvora) · [Repo](https://github.com/zyvorai/zyvor-duvora) |
| **IronWolf** | Bare-metal lifecycle (Metal3 + enterprise policy) | [Site](https://zyvor.dev/ironwolf) |
| **Zyvor Relay** | Accept → Notify → Ack → Act → Verify | [Site](https://zyvor.dev/zyvor-relay) |

> **Split of roles:** Ragnarok attests confidential / disposable VMs; **Axiom** is the day-2 private-cloud console.

---

## Scale · compliance · community

| Product | Pitch | Open |
|---------|-------|------|
| **HyperCluster** | Kubernetes lifecycle for bare metal / private cloud | [Site](https://zyvor.dev/hypercluster) · [Repo](https://github.com/zyvorai/hypercluster) |
| **ZySign** | macOS DSC for MCA21 V3 | [Site](https://zyvor.dev/zysign) · [Repo](https://github.com/zyvorai/zysign) |
| **Nodra** | Open edge runtime — offline-first MQTT/HTTP, twins, fleet | [Site](https://zyvor.dev/nodra) · [Repo](https://github.com/zyvorai/nodra) |
| **Kairo** | Kubernetes change intelligence — blast radius, SAFE/REVIEW/BLOCK | [Site](https://zyvor.dev/kairo) · [Repo](https://github.com/zyvorai/kairo) |
| **KubeFlight** | Deploy preflight — schedule, RBAC, netpol, evidence | [Site](https://zyvor.dev/kubeflight) · [Repo](https://github.com/zyvorai/zyvor-kubeflight) |
| **netevd / netctl / cloud-netconfig** | Apache-2.0 host networking tools | [netevd](https://github.com/zyvorai/zyvor-netevd) · [netctl](https://github.com/zyvorai/netctl) · [cn](https://github.com/zyvorai/zyvor-cloud-netconfig) |
| **Zyvor Janus** | GPU scheduling simulator | [janus](https://github.com/zyvorai/janus) |
| **Zyvor Argus** | Autonomous QA / Mission Control | [argus](https://github.com/zyvorai/zyvorai-argus) |
| **relay-pubsub / relay-edge** | Relay companions (Pub/Sub gateway + farm domain) | [pubsub](https://github.com/zyvorai/relay-pubsub) · [edge](https://github.com/zyvorai/relay-edge) |

---

## Edge · ops · AI apps

| Product | Pitch | Open |
|---------|-------|------|
| **Fleet** | Offline-first edge site control plane (Apache-2.0) | [Repo](https://github.com/zyvorai/zyvorai-fleet) |
| **device-agent** | Linux hardware edge agent — discovers the box, publishes to Nodra, exposes Fleet-compatible inventory (Apache-2.0) | [Repo](https://github.com/zyvorai/zyvor-device-agent) |
| **ota** | Signed, recoverable device OS updates — RAUC A/B, Ed25519-signed releases (Apache-2.0) | [Repo](https://github.com/zyvorai/ota) |
| **Edge Stack** | Landing page for the 8-product edge line | [Repo](https://github.com/zyvorai/edge-stack) |
| **Zoreon** | Ops chat — Mattermost is the tape; Zoreon is the product (MIT) | [Repo](https://github.com/zyvorai/zoreon) |
| **Yard** | Open asset and operations platform (Apache-2.0) | [Repo](https://github.com/zyvorai/yard) |
| **Verixa** | Stateful AI agent rehearsal and outcome verification — inject failures, verify final state (Apache-2.0) | [Repo](https://github.com/zyvorai/verixa) |
| **Kavira** | Turn an outage into a reproducible test; execution is the verdict (Apache-2.0) | [Repo](https://github.com/zyvorai/kavira) |
| **Aurora** | AI GTM agent platform — grounded RAG, SEO scoring, human-approved publishing | [Repo](https://github.com/zyvorai/aurora) |

---

## Bundle narratives

1. **Hypervisor exit** — Transiva + Scout + Chimera + h2kvm + GuestKit → [program](https://zyvor.dev/hypervisor-exit)  
2. **Private cloud run** — Axiom + Zeus + Veyron + Kairon + FluxVM + Iris + Haven + Kryton + Atlas + Netra  
3. **AI / GPU estate** — Forge + Gryvia + Zynera + Janus (+ IronWolf for metal)  
4. **Edge reliability** — Zyvor Relay + Nodra + Fleet + device-agent + ota  
5. **Assurance** — Argus + Kairo + KubeFlight + Verixa + Kavira on every release train
6. **Apple fleet** — Velora + FluxVM + Gryvia for Apple + Nivora + Macora  

<p align="center">
  <a href="https://zyvor.dev/schedule"><img src="https://img.shields.io/badge/Close_with-Schedule_a_demo-f0583a?style=for-the-badge&labelColor=0c1222" alt="Demo"/></a>
</p>
