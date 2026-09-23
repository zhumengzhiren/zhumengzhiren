# Hi, I'm Yuanfan Chen

I work on ML systems, mostly model inference and serving. At Character.AI, I work on inference optimization for production LLM serving across thousands of GPUs, mostly KV-cache offloading and kernel work on AMD MI325X/MI350. At Cornell Tech, my research focused on efficient LLM serving.

I spend a lot of time thinking about batching, KV caches, and the scheduling decisions that affect latency and throughput. I'm also interested in multimodal inference. Before this, I worked on distributed-database infrastructure at Tencent and DPU benchmarking at UofT.

[Website](https://zhumengzhiren.github.io/) · [LinkedIn](https://www.linkedin.com/in/yuanfan-chen-97b1a8280/) · [Email](mailto:yuanfan0504@gmail.com)

## Open Source

- **[sglang-omni](https://github.com/sgl-project/sglang-omni)** — built the CUDA IPC weight export/import library that lets data-parallel replicas on the same GPU share model weights via MPS ([merged PR #1124](https://github.com/sgl-project/sglang-omni/pull/1124)).

## Experience

- **Character.AI — ML Infra Engineer, Inference Optimization:** Production LLM serving (vLLM + LMCache) for the Gemma, DeepSeek, and GLM model families across thousands of GPUs, including AMD MI325X/MI350; hierarchical KV-cache offloading (prefix-cache hit 70% → 90%) and kernel optimization.
- **Tencent — AI Infrastructure Engineer:** Admission control and fault-tolerant recovery for distributed databases.
- **Cornell Tech — Research Assistant:** Tail-aware LLM scheduling and serving simulation.
- **UofT Far Data Lab — Research Assistant:** DPU benchmarking for cloud data processing.

## Publications

- **Beyond Prediction: Tail-Aware Scheduling for LLM Inference** — Yueying Li, Yuanfan Chen, Jiayang Chen, Esha Choukse, Haoran Qiu, G. Edward Suh, Rodrigo Fonseca, Ziv Scully, Udit Gupta · *ICML 2026* · [arXiv](https://arxiv.org/abs/2606.18431) · [Project Website](https://yl3469.github.io/uniboost-icml26/)
- **Making Sense of DPU Performance for Cloud Data Processing: Experiment, Analysis & Benchmark** — Jiasheng Hu, Chihan Cui, Yuanfan Chen, Philip A. Bernstein, Jialin Li, Qizhen Zhang · *arXiv, 2025* · [arXiv](https://arxiv.org/abs/2504.05536)

## Education

- **Cornell University** — M.Eng. in Computer Science
- **University of Toronto** — B.Sc. in Computer Science, High Distinction
