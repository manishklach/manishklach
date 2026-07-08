<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=manishklach&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true&text_color=e6edf3&title_color=58a6ff&icon_color=79c0ff" />
    <img src="https://github-readme-stats.vercel.app/api?username=manishklach&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true&text_color=1f2328&title_color=0969da&icon_color=0969da" width="49%" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=manishklach&layout=compact&theme=transparent&hide_border=true&text_color=e6edf3&title_color=58a6ff" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=manishklach&layout=compact&theme=transparent&hide_border=true&text_color=1f2328&title_color=0969da" width="37%" />
  </picture>
</p>

<p align="center">
  <a href="https://manishklach.github.io/writings.html"><img src="https://img.shields.io/badge/230%2B_Essays-000?style=flat-square&logo=readthedocs&logoColor=white" /></a>
  <a href="https://github.com/manishklach?tab=repositories"><img src="https://img.shields.io/badge/55_Repositories-000?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://manishklach.github.io/patents.html"><img src="https://img.shields.io/badge/68_Patents_Filed/Granted-000?style=flat-square&logo=documon&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Linux_Kernel-000?style=flat-square&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/CXL/HBM-000?style=flat-square&logo=simpleanalytics&logoColor=white" />
</p>

# Manish K L — AI Infrastructure, Linux Kernel & Memory Systems

I build **kernel-leaning systems for AI infrastructure**: KV-cache orchestration, memory hierarchy control, low-latency runtimes, and patent-backed hardware–software interfaces.

Most of my work sits close to the machine — Linux control planes, kernel-facing memory and I/O experiments, CPU scheduling and latency behavior, KV-state movement, and research prototypes that make systems ideas concrete.

> **230+ technical essays** — deep dives on Linux internals, memory systems, inference runtimes, and AI infrastructure.  
> ➡️ [manishklach.github.io/writings.html](https://manishklach.github.io/writings.html)

---

## Flagship Work

**Kernel & Systems Fast Path**  
[`linux-kernel-inference-fastpath`](https://github.com/manishklach/linux-kernel-inference-fastpath) — Linux kernel and systems fast path for LLM inference: eBPF tracing, runtime hints, cgroups, NUMA/GPU locality, KV-cache memory policies, and TTFT boost.

**Memory Fabric**  
[`flash-sram-dram-inference-fabric`](https://github.com/manishklach/flash-sram-dram-inference-fabric) — Predictive SRAM–DRAM–SSD memory fabric for low-cost AI inference, long-context KV cache tiering, and MoE expert staging.

**CPU Performance Control Plane**  
[`cpuopt-kernel`](https://github.com/manishklach/cpuopt-kernel) — Safe, reversible Linux CPU performance profiles across CPUFreq, intel\_pstate, amd-pstate, cpuidle, thermal, and hwmon backends.

**KV-Cache-Aware I/O**  
[`kairo-io`](https://github.com/manishklach/kairo-io) — AI KV-cache-aware Linux block I/O: decode-priority scheduling, NVMe backend mapping, placement metadata, and kernel tracepoint visibility.

**GPU/RDMA Observability**  
[`ai-host-observability`](https://github.com/manishklach/ai-host-observability) — Linux-first host observability for GPU and RDMA systems: memory pressure, PCIe, NUMA, IRQ, and host-side failure signals before they become incidents.

**KV-CPU Hardware Interface**  
[`kv-cpu-driver`](https://github.com/manishklach/kv-cpu-driver) — Linux control plane, RTL, and FPGA emulation scaffold for semantic KV-cache orchestration. Patent pending (India App No. 202641056309).

**Latency Control Plane**  
[`kernel-dvfs-agentic-latency`](https://github.com/manishklach/kernel-dvfs-agentic-latency) — Kernel latency control plane spanning DVFS, cpuidle, IRQs, scheduler, MM, VFS, I/O, and cgroup budgets for agentic AI.

**Intent-Aware Attention**  
[`intent-attention-kernel`](https://github.com/manishklach/intent-attention-kernel) — Intent-aware KV execution for agentic long-context inference: semantic block selection, dynamic scoring, KV quantization, and speculative prefetch.

---

## Current Focus

- KV-cache orchestration and memory residency control
- Linux kernel control planes for inference workloads
- CPU, IRQ, scheduler, and latency-path tuning
- Storage and I/O behavior for decode-critical serving paths
- Systems observability for real AI infrastructure

---

## About

I work on the hard parts of systems for AI — memory placement, I/O paths, scheduler behavior, latency control, and observability. I build across the stack, but naturally gravitate toward Linux, kernel-adjacent interfaces, CPU and memory behavior, and runtime control planes. I pair code with diagrams, RFC-style docs, and architecture-driven writeups to make low-level work legible.

**55 repositories** across kernel experiments, KV-cache infrastructure, memory systems, network dataplanes, AI runtimes, and performance tooling.

---

## Connect

- **Writings & essays:** [manishklach.github.io/writings.html](https://manishklach.github.io/writings.html)
- **Portfolio:** [manishklach.github.io](https://manishklach.github.io/)
- **Patent record:** [manishklach.github.io/patents.html](https://manishklach.github.io/patents.html)
- **GitHub:** [github.com/manishklach](https://github.com/manishklach?tab=repositories)
- **X:** [@OrbitHigher](https://x.com/OrbitHigher)
