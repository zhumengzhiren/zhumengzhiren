<h1 align="center">Hi, I'm Yuanfan Chen</h1>

<p align="center">
  <strong>I make large-scale LLM & multimodal inference fast — in production and on paper.</strong>
</p>

<p align="center">
  <a href="https://zhumengzhiren.github.io/">Website</a> ·
  <a href="https://www.linkedin.com/in/yuanfan-chen-97b1a8280/">LinkedIn</a> ·
  <a href="mailto:yuanfan0504@gmail.com">Email</a>
</p>

## About Me

I'm an ML systems engineer and researcher focused on the performance of
large-scale model inference — LLMs today, and increasingly multimodal
models. On the engineering side: serving performance for Character.AI's
production LLM clusters (AMD GPUs at scale) and distributed-database
infrastructure at Tencent. On the research side: tail-aware LLM
scheduling at Cornell Tech (ICML 2026) and DPU benchmarking at UofT's
Far Data Lab (arXiv 2025). The two feed each other: production
bottlenecks become research questions, and research results ship.

## What I Work On

- LLM inference performance: batching, KV-cache behavior, scheduling, serving efficiency
- Multimodal model serving: inference efficiency for vision-language and generative-media workloads
- Distributed scheduling — tail-latency-aware, at production scale
- Hardware-aware optimization: GPU (CUDA/ROCm) and DPU systems
- The load-bearing plumbing: admission control, fault tolerance, capacity planning

## Open Source

- **[sglang-omni](https://github.com/sgl-project/sglang-omni)** — built the CUDA IPC weight export/import library at the core of same-GPU data-parallel weight sharing ([#1124](https://github.com/sgl-project/sglang-omni/pull/1124), merged): multiple DP replicas share one copy of model weights on a single GPU via MPS

## Experience

- **Character.AI — AI Infrastructure** · Serving performance for production LLM fleets; capacity and efficiency analysis across multi-hundred-GPU clusters
- **Tencent — AI Infrastructure Engineer** · Distributed database internals: admission control, fault-tolerant cluster recovery
- **Cornell Tech — Research Assistant** · Tail-aware scheduling for LLM inference and high-fidelity serving simulation (→ ICML 2026)
- **UofT Far Data Lab — Research Assistant** · DPU performance benchmarking for cloud data processing (→ arXiv 2025)

## Publications

- **Beyond Prediction: Tail-Aware Scheduling for LLM Inference** —
  Yueying Li, **Yuanfan Chen**, Jiayang Chen, Esha Choukse, Haoran Qiu, G. Edward Suh, Rodrigo Fonseca, Ziv Scully, Udit Gupta ·
  *ICML 2026* · [arXiv](https://arxiv.org/abs/2606.18431) · [Project Website](https://yl3469.github.io/uniboost-icml26/)
- **Making Sense of DPU Performance for Cloud Data Processing: Experiment, Analysis & Benchmark** —
  Jiasheng Hu, Chihan Cui, **Yuanfan Chen**, Philip A. Bernstein, Jialin Li, Qizhen Zhang ·
  *arXiv, 2025* · [arXiv](https://arxiv.org/abs/2504.05536)

## Education

- **Cornell University** — M.Eng. in Computer Science
- **University of Toronto** — B.Sc. in Computer Science, High Distinction
