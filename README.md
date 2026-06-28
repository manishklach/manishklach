# Hi, I'm Manish

I build kernel-leaning systems for AI infrastructure, KV-cache orchestration, memory hierarchy control, and low-latency runtime behavior.

Most of my work sits close to the machine: Linux control planes, kernel-facing memory and I/O experiments, CPU scheduling and latency behavior, KV-state movement, and research prototypes that make systems ideas concrete.

## About Me

- I like working on the hard parts of systems for AI: memory placement, I/O paths, scheduler behavior, latency control, and observability.
- I build across the stack, but I naturally gravitate toward Linux, kernel-adjacent interfaces, CPU and memory behavior, and runtime control planes.
- I care about making low-level work legible, so I pair code with diagrams, RFC-style docs, and architecture-driven writeups.

## Current Focus

- KV-cache orchestration and memory residency control
- Linux kernel control planes for inference workloads
- CPU, IRQ, scheduler, and latency-path tuning
- Storage and I/O behavior for decode-critical serving paths
- Systems observability for real AI infrastructure

## Selected Projects

- [kairo-io](https://github.com/manishklach/kairo-io)  
  AI KV-cache-aware Linux block I/O work focused on decode-priority scheduling, placement metadata, NVMe backend mapping, and kernel tracepoint visibility.

- [kv-cpu-driver](https://github.com/manishklach/kv-cpu-driver)  
  A Linux control-plane and hardware-interface scaffold for semantic KV-cache orchestration, with CPU-facing coordination, RTL structure, and FPGA emulation paths.

- [linux-hbf-control-plane](https://github.com/manishklach/linux-hbf-control-plane)  
  An RFC-style Linux exploration of runtime-guided memory placement, prefetch, promotion, and demotion for future CXL/HBF-era inference systems.

- [kernel-dvfs-agentic-latency](https://github.com/manishklach/kernel-dvfs-agentic-latency)  
  A kernel latency control-plane project spanning DVFS, cpuidle, IRQs, scheduler behavior, MM, VFS, I/O, and cgroup budget control for latency-sensitive AI execution.

- [ai-host-observability](https://github.com/manishklach/ai-host-observability)  
  Linux-first host observability for GPU and RDMA systems, built to surface memory pressure, reclaim, PCIe, NUMA, IRQ, and host-side failure signals before they become incidents.

## Writing And Portfolio

- Portfolio: [manishklach.github.io](https://manishklach.github.io/)
- Repositories: [github.com/manishklach](https://github.com/manishklach?tab=repositories)

I regularly publish architecture-driven essays and technical companion material around Linux systems, AI infrastructure, memory-centric design, and runtime control.

## What You’ll Find Here

- Kernel and kernel-adjacent experiments
- KV-cache, memory, CPU, and I/O control-plane ideas
- Systems observability and performance tooling
- RFC-style writeups, architecture notes, and technical docs
- Research prototypes tied to real implementation artifacts

---

If you're into Linux internals, memory systems, KV-cache control, CPU latency paths, or kernel-facing AI infrastructure work, you'll probably find something interesting here.
