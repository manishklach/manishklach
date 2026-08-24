<div align="center">

# Manish K L

### AI infrastructure · GPU runtimes · memory systems · Linux

**I build the machinery around models.**

[![Writings](https://img.shields.io/badge/230%2B_technical_essays-111111?style=flat-square&logo=readthedocs&logoColor=white)](https://manishklach.github.io/writings.html)
[![Portfolio](https://img.shields.io/badge/portfolio-111111?style=flat-square&logo=githubpages&logoColor=white)](https://manishklach.github.io/)
[![Patents](https://img.shields.io/badge/68_patents_filed%2Fgranted-111111?style=flat-square)](https://manishklach.github.io/patents.html)

</div>

I design and prototype AI systems from the Linux and storage layers up through GPU kernels and inference control planes. My work focuses on a practical question: **how do we make large-model inference faster, cheaper, and easier to operate?**

The repositories here are executable architecture work—code, benchmarks, simulators, kernel RFCs, hardware interfaces, and production-oriented reference systems.

## Selected systems

| Project | What it explores |
| --- | --- |
| [**Inference Factory Simulator**](https://github.com/manishklach/inference-factory-sim) | Trace-driven LLM serving economics: continuous batching, disaggregated prefill/decode, speculative decoding, MoE balance, tiered KV reuse, GPU cost, and margin. |
| [**ExpertMesh**](https://github.com/manishklach/expertmesh) | A low-cost AMD/ROCm stationary-expert fabric for trillion-parameter sparse MoE inference, with packed-INT4 HIP kernels and activation-only RoCE transport. |
| [**KVSSD Attention**](https://github.com/manishklach/kvssd-attention) | SSD-resident INT2/INT4 KV cache with bounded asynchronous staging and fused CUDA/Triton dequantizing decode attention. |
| [**K3 Inference Platform**](https://github.com/manishklach/k3-inference-platform) | A production-oriented MoE serving control plane: checkpoint release gates, capacity planning, admission, OpenAI-compatible routing, benchmarks, and observability. |
| [**GB300 RL Runtime**](https://github.com/manishklach/gb300-rl-runtime) | A close-to-metal C/CUDA runtime with persistent GPU workers, hugepage KV arenas, command rings, and no per-token CPU orchestration. |
| [**AttnRes Kernel Lab**](https://github.com/manishklach/attnres-kernel-lab) | Fused PyTorch/Triton kernels for routing across model depth and sequence time, including Hydra-2P, KDA, and CADR. |
| [**Linux HBF Control Plane**](https://github.com/manishklach/linux-hbf-control-plane) | An executable Linux memory-tiering RFC with asynchronous range hints, NUMA migration, tracepoints, selftests, and observability. |
| [**OpenFlash Controller Lab**](https://github.com/manishklach/openflash-controller-lab) | An executable NAND-controller architecture spanning FTL, scheduling, queue ABI, QEMU PCI emulation, and a Linux `blk-mq` driver. |

## The stack I work on

```text
model algorithms     fused attention · routing · low precision
serving systems      admission · scheduling · release gates · economics
GPU runtimes         persistent execution · command rings · fast paths
memory systems       HBM/DRAM/NVMe tiering · KV placement · CXL/HBF
host + kernel        Linux MM · block I/O · NUMA · eBPF · observability
hardware interfaces flash controllers · RTL scaffolds · CPU/GPU fabrics
```

## Current research direction

- Treating inference as a **factory**, not a single kernel: utilization, placement, queueing, cost, and operational evidence all matter.
- Moving fewer bytes: stationary experts, compact activations, quantized KV state, semantic reuse, and predictive residency.
- Removing work from the token path: persistent GPU execution, bounded queues, preallocation, and explicit control-plane boundaries.
- Making architecture claims testable through benchmarks, simulators, CI gates, tracepoints, and honest maturity labels.

## More work

- [Linux inference fast path](https://github.com/manishklach/linux-kernel-inference-fastpath) — eBPF, cgroups, NUMA/GPU locality, KV memory policy, and TTFT control.
- [AI host observability](https://github.com/manishklach/ai-host-observability) — Prometheus signals for GPU/RDMA hosts, PCIe, NUMA, memory pressure, IRQs, and kernel events.
- [RL inference scheduler](https://github.com/manishklach/rl-inference-scheduler) — DQN scheduling against FIFO, SJF, and priority baselines.
- [CPUOpt Kernel](https://github.com/manishklach/cpuopt-kernel) — safe, reversible CPU performance profiles across Linux power and thermal backends.
- [MLX Metal Kernels](https://github.com/manishklach/mlx-metal-kernels) — experimental Apple Silicon kernels for attention, decode, and KV-cache primitives.

## Writing and patents

I pair systems code with architecture diagrams, RFC-style documents, and long-form technical writing. The portfolio includes **230+ essays** and a record of **68 patents filed or granted worldwide** across memory, storage, runtimes, and hardware–software interfaces.

[Read the essays](https://manishklach.github.io/writings.html) · [Browse the portfolio](https://manishklach.github.io/) · [View the patent record](https://manishklach.github.io/patents.html) · [Follow on X](https://x.com/OrbitHigher)
