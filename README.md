<h1 align="center">Hi there, I'm Jiajie Li</h1>

<h3 align="center">
  AI Infra Engineer | vLLM-Omni Contributor | RL-Kernel Core Contributor
</h3>

<p align="center">
  <em>Graduate student at Xi'an Jiaotong University | Building efficient LLM serving and RL post-training infrastructure.</em>
</p>

### About Me

- **Currently working on:** open-source contributions to [vLLM-Omni](https://github.com/vllm-project/vllm-omni), focusing on efficient omni-modality model inference and serving in the vLLM ecosystem.
- **Core contributor to:** **RL-Kernel / Kernel-Align**, where I build infrastructure for faster and more reliable RL training loops, from rollout execution to kernel-level validation.
- **Open-source focus:** vLLM-style rollout, DeepSpeed training workers, Ray-based worker orchestration, weight synchronization, asynchronous rollout/training pipelines, and RL-shaped CUDA kernel optimization.
- **Research interests:** AI infrastructure, GRPO/RLHF systems, multimodal serving, high-performance CUDA kernels, and AI4S/PINN applications.
- **Writing:** I regularly share thoughts and engineering notes on my [personal blog](https://inaniloquentee.github.io).
- **How to reach me:** inani_@stu.xjtu.edu.cn / 3051000145@qq.com

---

### Selected RL-Kernel Work

- **vLLM rollout integration:** implemented lazy vLLM sampler construction, shared-prefix caching for GRPO candidate generation, grouped outputs, and stable normalized rollout schemas.
- **Real runtime validation:** built WSL2 CUDA validation paths for real vLLM smoke tests and steady-state prefix-cache benchmarking.
- **DeepSpeed training workers:** added lazy DeepSpeed initialization, rollout-payload training, explicit weight-version publishing, and CUDA/NCCL smoke validation.
- **Ray actor orchestration:** implemented Ray actor management for rollout and training workers, including health checks, cleanup, and Ray + DeepSpeed actor smoke tests.
- **Overlap pipeline:** built an asynchronous pipeline where vLLM-style rollout can prepare the next iteration while DeepSpeed-style training processes the current one.
- **Weight synchronization:** designed versioned low-copy and shared-memory bridge contracts with explicit publish/import/ack/release lifecycle handling.
- **RL kernel foundations:** created deterministic RL-shaped batch fixtures, PyTorch reference operators, benchmark adapters, and loss-step tests covering logprob, policy ratio, KL, masking, and objective drift.
- **Native kernel optimization:** worked on fused selected-logprob CUDA paths for GRPO-style workloads, backed by RL-shaped benchmark and profiling evidence.

---

### Tech Stack & Tools

<p>
  <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/-vLLM-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/-DeepSpeed-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/-Ray-028CF0?style=flat-square" />
  <img src="https://img.shields.io/badge/-LLM_Infra-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

---

### GitHub Metrics

<div align="center">
  <img src="/github-metrics.svg" alt="Metrics" />
</div>

---

### Contributions & Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=inaniloquentee&theme=transparent&hide_border=true" alt="Activity Graph" width="100%"/>
</div>
