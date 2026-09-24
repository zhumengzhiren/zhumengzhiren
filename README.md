# Hi, I'm Yuanfan Chen

I work on ML systems, efficient and scalable serving. At Character.AI, I work on inference optimization for production LLM serving, mostly KV-cache offloading and kernel work on AMD GPUs. At Cornell Tech, my research focused on efficient LLM serving.

I spend a lot of time thinking about batching, KV caches, and the scheduling decisions that affect latency and throughput. I'm also interested in multimodal inference. Before this, I worked on distributed-database infrastructure at Tencent and DPU benchmarking at UofT.

[Website](https://zhumengzhiren.github.io/) · [LinkedIn](https://www.linkedin.com/in/yuanfan-chen-97b1a8280/) · [Email](mailto:yuanfan0504@gmail.com)

## Open Source

- **[LMCache](https://github.com/LMCache/LMCache)** — KV-cache hit observability for the multi-process lookup path: revived and landed L1/L2 hit attribution and early-exit reasons on the lookup event and request span ([merged PR #4734](https://github.com/LMCache/LMCache/pull/4734)), then added the Prometheus counters that aggregate them per model ([merged PR #4962](https://github.com/LMCache/LMCache/pull/4962)).
- **[vLLM](https://github.com/vllm-project/vllm)** — added `gelu_tanh` to the AITER fp8 fused-MoE backend for Gemma-4-style models and fixed a silent correctness bug: padded fp8 expert weights were allocated uninitialized, so pad rows leaked into the quant scale and layer output ([PR #55251](https://github.com/vllm-project/vllm/pull/55251), approved, in review).
- **[AITER](https://github.com/ROCm/aiter)** — proposed the gfx942 unified-attention prefill config fix for Gemma-4 head-512 layers ([PR #5649](https://github.com/ROCm/aiter/pull/5649)); the maintainers' dtype-split follow-up ([PR #5650](https://github.com/ROCm/aiter/pull/5650)) benchmarks against it and carries my end-to-end MI325X vLLM serving validation.
- **[sglang-omni](https://github.com/sgl-project/sglang-omni)** — built the CUDA IPC weight export/import library that lets data-parallel replicas on the same GPU share model weights via MPS ([merged PR #1124](https://github.com/sgl-project/sglang-omni/pull/1124)).
- **[sglang-omni](https://github.com/sgl-project/sglang-omni)** — Restage: replaces the manual placement grid for multi-stage pipelines with a one-GPU calibration and a capacity model that ranks residency shapes; co-developed the method, integration in review ([PR #2134](https://github.com/sgl-project/sglang-omni/pull/2134)).

## Experience

- **Character.AI — ML Infra Engineer, Inference Optimization:** Production LLM serving (vLLM + LMCache); hierarchical KV-cache offloading (prefix-cache hit 70% → 90%) and kernel optimization.
- **Tencent — AI Infrastructure Engineer:** Admission control and fault-tolerant recovery for distributed databases.
- **Cornell Tech — Research Assistant:** Tail-aware LLM scheduling and serving simulation.
- **UofT Far Data Lab — Research Assistant:** DPU benchmarking for cloud data processing.

## Publications

- **Beyond Prediction: Tail-Aware Scheduling for LLM Inference** — Yueying Li, Yuanfan Chen, Jiayang Chen, Esha Choukse, Haoran Qiu, G. Edward Suh, Rodrigo Fonseca, Ziv Scully, Udit Gupta · *ICML 2026* · [arXiv](https://arxiv.org/abs/2606.18431) · [Project Website](https://yl3469.github.io/uniboost-icml26/)
- **Making Sense of DPU Performance for Cloud Data Processing: Experiment, Analysis & Benchmark** — Jiasheng Hu, Chihan Cui, Yuanfan Chen, Philip A. Bernstein, Jialin Li, Qizhen Zhang · *arXiv, 2025* · [arXiv](https://arxiv.org/abs/2504.05536)

## Education

- **Cornell University** — M.Eng. in Computer Science
- **University of Toronto** — B.Sc. in Computer Science, High Distinction
