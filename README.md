# ZyvorAI

**Infrastructure software for teams leaving proprietary virtualization — and for teams building what comes next.**

[zyvor.dev](https://zyvor.dev) · [Products](https://zyvor.dev/products) · [Compare](https://zyvor.dev/compare) · [Pricing](https://zyvor.dev/pricing) · [Talk to an engineer](https://zyvor.dev/schedule)

This repository is the **marketing and product narrative** for ZyvorAI Labs: what we sell, who it is for, and how the suite fits together. The live site is the source of truth for pages and trials; this repo is the GitHub-facing story.

---

## Why Zyvor

| Pressure | What we sell |
|----------|----------------|
| Hypervisor / HCI exit | Discover → export → convert → deploy onto KVM / KubeVirt without a forklift rewrite |
| Cloud repatriation | Bring workloads back to private Kubernetes with a control plane you own |
| Day-2 ops debt | One suite for VMs, apps, storage intent, GPU fabric, bare metal, and reliability |
| Edge / air-gap | On-prem first products — not “cloud required to run the control plane” |

**Brand promise:** open, production-proven foundations (KVM, KubeVirt, Kubernetes) with commercial products that are operator-ready — manuals, trials, and support — not slideware.

---

## The suite (from [zyvor.dev/products](https://zyvor.dev/products))

### Migrate — get off proprietary hypervisors

| Product | One-line sell | Site |
|---------|----------------|------|
| **HyperSDK Platform** | Multi-cloud VM migration control plane — discover, export, orchestrate | [zyvor.dev/hypersdk](https://zyvor.dev/hypersdk) |
| **hyper2kvm** | Any hypervisor disk → boot-ready KVM, faster than legacy converters | [zyvor.dev/hyper2kvm](https://zyvor.dev/hyper2kvm) |
| **GuestKit** | Inspect and repair VM disks without booting the guest | [zyvor.dev/guestkit](https://zyvor.dev/guestkit) |

### Run — Kubernetes & VM management

| Product | One-line sell | Site |
|---------|----------------|------|
| **Zeus OS** | Visual infrastructure operating system | [zyvor.dev/zeus-os](https://zyvor.dev/zeus-os) |
| **Hermes** | Application operating layer for Kubernetes — every app, one door | [zyvor.dev/hermes](https://zyvor.dev/hermes) |
| **Veyron** | Declarative KubeVirt VM templates & blueprints | [zyvor.dev/veyron](https://zyvor.dev/veyron) |
| **Machina** | Cloud-native libvirt / KVM host management | [zyvor.dev/machina](https://zyvor.dev/machina) |
| **Zyvor Fabric** | Full-featured VM management on Ephemera — no libvirt tax | [zyvor.dev/zyvor-fabric](https://zyvor.dev/zyvor-fabric) |
| **Ephemera** | Disposable compute — QEMU, Cloud Hypervisor, Firecracker | [zyvor.dev/ephemera](https://zyvor.dev/ephemera) |

### Operate — infrastructure depth

| Product | One-line sell | Site |
|---------|----------------|------|
| **Aether** | Deploy once; move across Podman, Kubernetes, KubeVirt, bare metal | [zyvor.dev/aether](https://zyvor.dev/aether) |
| **Ragnarok** | Confidential computing & disposable-VM fabric for KubeVirt | [zyvor.dev/ragnarok](https://zyvor.dev/ragnarok) |
| **Atlas** | Storage control plane — request intent, not pool internals | [zyvor.dev/atlas](https://zyvor.dev/atlas) |
| **PacketWolf** | Every connection in the cluster — down to the process | [zyvor.dev/packetwolf](https://zyvor.dev/packetwolf) |
| **Forge** | GPU & AI infrastructure fabric for Kubernetes | [zyvor.dev/forge](https://zyvor.dev/forge) |
| **IronWolf** | Bare-metal lifecycle on Kubernetes (Metal3 + policy) | [zyvor.dev/ironwolf](https://zyvor.dev/ironwolf) |
| **Zyvor Relay** | Accept → Notify → Ack → Act → Verify — on-prem reliability control plane | [zyvor.dev/zyvor-relay](https://zyvor.dev/zyvor-relay) |

### Scale & compliance

| Product | One-line sell | Site |
|---------|----------------|------|
| **HyperCluster** | Kubernetes lifecycle for bare metal and private cloud | [zyvor.dev/hypercluster](https://zyvor.dev/hypercluster) |
| **ZySign** | macOS DSC toolkit for MCA21 V3 eFiling | [zyvor.dev/zysign](https://zyvor.dev/zysign) |

### Community Edition (Apache-2.0)

| Product | One-line sell | GitHub |
|---------|----------------|--------|
| **netevd** | Netlink-first network event daemon | [zyvorai/netevd](https://github.com/zyvorai/netevd) |
| **netctl** | Async Linux network CLI | [zyvorai/netctl](https://github.com/zyvorai/netctl) |
| **cloud-netconfig** | Cloud metadata → secondary IPs & routes | [zyvorai/cloud-netconfig](https://github.com/zyvorai/cloud-netconfig) |
| **Zyvor Janus** | GPU cluster simulator for Forge R&D | [zyvorai/janus](https://github.com/zyvorai/janus) |
| **Zyvor Argus** | Autonomous software assurance (Playwright + Mission Control) | [zyvorai/argus](https://github.com/zyvorai/argus) |

Also open / public engineering surfaces: [zyvorai/hypersdk](https://github.com/zyvorai/hypersdk), [zyvorai/hyper2kvm](https://github.com/zyvorai/hyper2kvm), [zyvorai/guestkit](https://github.com/zyvorai/guestkit), [zyvorai/ephemera](https://github.com/zyvorai/ephemera).

---

## Buy paths (same as the website)

| Intent | Link |
|--------|------|
| **Schedule a demo** | [zyvor.dev/schedule](https://zyvor.dev/schedule) |
| **Trial hub** | [zyvor.dev/trial](https://zyvor.dev/trial) |
| **Contact sales** | [zyvor.dev/contact?intent=sales](https://zyvor.dev/contact?intent=sales) |
| **Hypervisor exit** | [zyvor.dev/hypervisor-exit](https://zyvor.dev/hypervisor-exit) |
| **Cloud repatriation** | [zyvor.dev/cloud-repatriation](https://zyvor.dev/cloud-repatriation) |
| **Partners** | [zyvor.dev/partners](https://zyvor.dev/partners) |
| **Pricing** | [zyvor.dev/pricing](https://zyvor.dev/pricing) |

Email: [sales@zyvor.dev](mailto:sales@zyvor.dev) · [info@zyvor.dev](mailto:info@zyvor.dev)

---

## How to use this repo

| Doc | Purpose |
|-----|---------|
| [PRODUCTS.md](PRODUCTS.md) | Full catalog with pitches and CTAs |
| [WHY-ZYVOR.md](WHY-ZYVOR.md) | Positioning for buyers and partners |
| [CONTACT.md](CONTACT.md) | Sales / trial / partner routing |
| [ORG.md](ORG.md) | GitHub org map (`zyvorai/*` repos) |

The marketing **website** codebase is private: [zyvorai/hypersdk-web](https://github.com/zyvorai/hypersdk-web) (deploys to [zyvor.dev](https://zyvor.dev)).

---

## Company

**ZyvorAI Labs Private Limited**  
Site: [zyvor.dev](https://zyvor.dev) · GitHub org: [github.com/zyvorai](https://github.com/zyvorai)

© 2026 ZyvorAI Labs Private Limited. All rights reserved.
