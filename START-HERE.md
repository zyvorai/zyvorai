# Start here

Pick the sentence that sounds like your week. Each path lists what to try first, with links to public repos or the product page where the repo is private.

| I want to... | Start with | Then add |
|--------------|-----------|----------|
| **Leave a proprietary hypervisor** | [Scout](https://github.com/zyvorai/scout) to find blockers, [Transiva](https://github.com/zyvorai/zyvor-transiva) to export | [h2kvm](https://github.com/zyvorai/zyvor-h2kvm) to convert, [GuestKit](https://github.com/zyvorai/zyvor-guestkit) to inspect and repair, [Chimera](https://github.com/zyvorai/chimera) to test without a real vSphere |
| **Run VMs on Kubernetes without five consoles** | [Kairon](https://github.com/zyvorai/zyvor-kairon) with [FluxVM](https://github.com/zyvorai/zyvor-fluxvm) | [Veyron](https://github.com/zyvorai/veyron), [Zorvia](https://github.com/zyvorai/zyvor-zorvia), [Zeus OS](https://github.com/zyvorai/zeus-os), [Haven](https://github.com/zyvorai/zyvor-haven) for identity |
| **Deploy one workload to Podman, Kubernetes or KubeVirt** | [Aether](https://github.com/zyvorai/Aether) | [Kairon](https://github.com/zyvorai/zyvor-kairon) and [FluxVM](https://github.com/zyvorai/zyvor-fluxvm) for VMs |
| **Build a private cloud on Linux** | [Zyvor Fabric](https://github.com/zyvorai/zyvorai-fabric) or [Machina](https://github.com/zyvorai/zyvor-machina) | [Atlas](https://github.com/zyvorai/zyvor-atlas) for storage, [Axiom](https://zyvor.dev/axiom) for day-2 ops, [HyperCluster](https://github.com/zyvorai/hypercluster) for clusters |
| **Run VMs and local models on my Mac** | [Velora](https://github.com/zyvorai/velora/releases/latest) (`.pkg` / `.dmg`) | [FluxVM](https://github.com/zyvorai/zyvor-fluxvm) via `brew install zyvorai/tap/fluxvm`, [Macora](https://github.com/zyvorai/zyvor-macora) and [Nivora](https://github.com/zyvorai/zyvor-nivora) to see the network |
| **Schedule jobs across a fleet of Macs** | [Gryvia for Apple](https://github.com/zyvorai/zyvor-gryvia-apple) ([live demo](https://zyvorai.github.io/zyvor-gryvia-apple/demo/), simulated fleet) | Velora on each Mac |
| **See and control what my network is doing** | [Netra](https://github.com/zyvorai/zyvor-netra) (any CNI), [Paqtra](https://github.com/zyvorai/zyvor-paqtra) (Cilium) | [Rivora](https://github.com/zyvorai/zyvor-rivora) for load balancing, [Shukra](https://github.com/zyvorai/zyvor-shukra) for runtime security, [PacketWolf](https://zyvor.dev/packetwolf) |
| **Schedule GPUs and serve models** | [Gryvia](https://github.com/zyvorai/zyvor-gryvia) | [Zyntra](https://github.com/zyvorai/zyvor-zyntra), [Nuvora](https://github.com/zyvorai/zyvor-nuvora), [Janus](https://github.com/zyvorai/janus) to simulate without GPUs, [Forge](https://zyvor.dev/forge) |
| **Run an offline-first edge** | [Nodra](https://github.com/zyvorai/nodra), [Fleet](https://github.com/zyvorai/zyvorai-fleet) | [device-agent](https://github.com/zyvorai/zyvor-device-agent), [ota](https://github.com/zyvorai/ota), [Zyvor Relay](https://zyvor.dev/zyvor-relay) |
| **Know what a release will break** | [Kairo](https://github.com/zyvorai/kairo), [KubeFlight](https://github.com/zyvorai/zyvor-kubeflight) | [Argus](https://github.com/zyvorai/zyvorai-argus), [Verixa](https://github.com/zyvorai/verixa), [Kavira](https://github.com/zyvorai/kavira) |

## Not sure?

- Browse the full catalog in [PRODUCTS.md](PRODUCTS.md) or the repo map in [ORG.md](ORG.md).
- [Book a demo with engineering](https://zyvor.dev/schedule) or write to **sales@zyvor.dev**.

Licenses vary by product: Apache-2.0 where marked, source-available (BSL / BUSL) for Velora, Gryvia for Apple and Nivora. Check each repo.
