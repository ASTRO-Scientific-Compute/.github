<p align="center"><img src="https://raw.githubusercontent.com/ASTRO-Scientific-Compute/astro-compute/main/assets/astro-hero.svg" alt="ASTRO Scientific Compute — discover, optimize, validate" width="100%"></p>

# Scientific questions. Heterogeneous hardware. Checked answers.

**ASTRO is building a heterogeneous scientific compute fabric that discovers, optimizes, executes and independently validates mathematical workloads across CPUs, GPUs, ray-tracing hardware and AI accelerators.**

From astronomy and physics to biology, chemistry, AI, engineering and realtime workloads, our goal is a unified, self-optimizing research compute network.

**EXPERIMENTAL · Active development · Not production-ready**

[Explore ASTRO →](https://github.com/ASTRO-Scientific-Compute/astro-compute) · [Current status](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/docs/STATUS.md) · [Roadmap](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/docs/ROADMAP.md)

## A compute worker, built around useful science

“MinerNode” means a local compute worker. ASTRO is not classical cryptocurrency mining. Its objective is **more correctly completed mathematical work per second**, measured in each task's natural units.

| Discover | Optimize | Execute | Validate |
|---|---|---|---|
| Establish real device capabilities | Search legal runtime and kernel paths | Match work to suitable hardware | Check the unchanged mathematical contract |

The development project contains experimental local GPU search, bounded Runtime Fusion and RT-compute paths. This first public source preview provides **81 canonical CPU reference primitives, including 66 SPACE entries**, analytic vectors and a complete 94-entry registry inventory. A bounded Linux Vulkan demo now provides four fixed MathSpecs with DIRECT/TILED execution, canonical correctness checks and automatic stop. Unrestricted search distribution and external human review remain open.

## The system we are building

![ASTRO architecture: local implementation and planned network boundaries](https://raw.githubusercontent.com/ASTRO-Scientific-Compute/astro-compute/main/assets/architecture.svg)

The complete **Researcher → Scientist AI → MainNode → heterogeneous workers → independent validation → researcher** loop is **PLANNED / IN DEVELOPMENT**. MainNode and Scientist are not presented as a production service.

## One scientific map, many kinds of hardware

| Science | Direction |
|---|---|
| **SPACE** | Astronomy, catalogs, photometry, transforms, orbital and spatial computation |
| **BIO** | Alignment, contacts and biological numerical workflows |
| **CHEM** | Molecular geometry, distances and spatial analysis |
| **PHYSICS** | Observables, numerical integration and simulation building blocks |
| **SIGNAL** | Filtering, correlation and spectral processing |
| **ENGINEERING** | Sparse/dense math, geometry, simulation and future realtime/game optimization |

The current corpus contains bounded reference primitives; broad applications remain planned compositions. CPU, AMD/NVIDIA/Intel GPU, APU, RT, AI and future mobile/edge roles are determined by demonstrated capabilities, not branding. An older GPU can remain useful for classic compute while other devices handle appropriate tensor work. Cross-vendor deployment is not yet claimed as verified.

## Correctness before performance

Exact contracts keep **zero differing bits**. Bounded-FP contracts keep their own explicit bounds. Code presence, execution, measurement and trust are separate gates. QUICK profiles are not sustained performance claims; independent ownership/network validation is a future network requirement.

Benchmark storage is **run → validate → profile → cleanup**. Real research results remain on the worker until a genuine verified MainNode receipt and the applicable grace period authorize deletion.

## Where we are going

**PLANNED:** universal mathematical composition, a capability-routed research network, Scientist integration, independent validation, Host Runtime Generator, AI/tensor backends and Engineering → Realtime/Game workflows. A separate local game-optimizer prototype exists; automatic engine/shader rewriting and verified game-speedup claims are not part of this release.

## Repositories and participation

- **[astro-compute](https://github.com/ASTRO-Scientific-Compute/astro-compute)** — public reference source, architecture, contracts, status and roadmap.
- **[.github](https://github.com/ASTRO-Scientific-Compute/.github)** — this organization profile.

Start with the [contribution guide](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/CONTRIBUTING.md) or review the [correctness model](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/docs/VALIDATION.md). **Source-available demonstration software. Free to evaluate using the included demo. All other use requires explicit permission from the copyright holder.** Not an open-source or OSI-approved license; [read the license](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/LICENSE). Read the [security policy](https://github.com/ASTRO-Scientific-Compute/astro-compute/blob/main/SECURITY.md) before reporting sensitive issues.
