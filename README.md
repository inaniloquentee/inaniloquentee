<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=280&section=header&text=Takumi&fontSize=80&animation=fadeIn&fontAlignY=35&desc=XJTU%20%7C%20vLLM-Omni%20Contributor%20%7C%20RL%20Systems%20Engineer&descAlignY=60&descAlign=50" width="100%"/>
</div>

<h3 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=0F4C81&center=true&vCenter=true&width=650&lines=Graduate+Student+%40+XJTU;Contributing+to+vLLM-Omni;Building+Vime+RL+Infrastructure;CUDA+%2B+ROCm+Systems+Engineering" alt="Typing SVG" />
  </a>
</h3>

<div align="center">

[![](https://img.shields.io/badge/Email-inani__%40stu.xjtu.edu.cn-red?style=flat-square&logo=gmail)](mailto:inani_@stu.xjtu.edu.cn)
[![](https://img.shields.io/badge/Location-Xi'an%2C%20China-blue?style=flat-square&logo=google-maps)]()
[![](https://img.shields.io/badge/GitHub-inaniloquentee-181717?style=flat-square&logo=github)](https://github.com/inaniloquentee)

</div>

---

### 👨‍💻 **About Me**

I am a graduate student at **Xi'an Jiaotong University (XJTU)**, focusing on **AI infrastructure**, **LLM serving**, and **RL post-training systems**.

I enjoy turning systems ideas into practical open-source implementations: efficient rollout execution, distributed training workflows, weight synchronization, and cross-platform GPU optimization for GRPO-style workloads.

* 🔭 **Currently contributing to:** [**vLLM-Omni**](https://github.com/vllm-project/vllm-omni), a framework for efficient omni-modality model inference and serving.
* 🚀 **Main work:** Leading Vime framework research, fork-roadmap planning, and PR delivery across CUDA and ROCm; integrating Vime with [**RL-Kernel**](https://github.com/RL-Align/RL-Kernel) for reproducible RL training and rollout.
* 🔬 **Research interests:** Efficient inference, distributed attention, GRPO/RLHF systems, linear-logp providers, and cross-platform GPU performance.

---

### 🚀 **Current Focus: Open Source**

| **Project** | **Focus** | **Status** |
| :--- | :--- | :---: |
| [**vLLM-Omni**](https://github.com/vllm-project/vllm-omni) | Efficient omni-modality model inference and serving in the vLLM ecosystem | 🔥 **Contributing** |
| [**Vime**](https://github.com/vllm-project/vime) | RL framework integration, roadmap planning, and end-to-end training/rollout validation | ⚡ **Lead contributor** |
| [**RL-Kernel**](https://github.com/RL-Align/RL-Kernel) | GPU kernels and strict runtime validation consumed by Vime on CUDA and ROCm | 🤝 **Contributor** |

---

### 🧩 **Selected Systems Work**

| **Area** | **Selected Work** |
| :--- | :--- |
| **Vime framework and delivery** | Framework investigation, fork-version roadmap planning, upstream PR delivery, and reproducible experiment documentation ([PR #409](https://github.com/RL-Align/RL-Kernel/pull/409), [PR #287](https://github.com/RL-Align/RL-Kernel/pull/287)) |
| **CUDA + ROCm integration** | Led the Vime provider boundary for linear log-probabilities on both GPU stacks, preserving Vime's loss semantics and native fallback ([CUDA PR #424](https://github.com/vllm-project/vime/pull/424), [ROCm PR #423](https://github.com/vllm-project/vime/pull/423)) |
| **Distributed Attention** | Developed and validated paged/CP attention paths, including FlashInfer RoPE-fused attention, CP drift checks, and bitwise ROCm schedules ([PR #279](https://github.com/RL-Align/RL-Kernel/pull/279), [PR #284](https://github.com/RL-Align/RL-Kernel/pull/284), [PR #319](https://github.com/RL-Align/RL-Kernel/pull/319), [PR #394](https://github.com/RL-Align/RL-Kernel/pull/394)) |
| **Deterministic runtime and performance** | CUDA Graph capture, tensor-parallel all-reduce optimization, strict runtime modes, and cross-configuration kernel validation ([PR #344](https://github.com/RL-Align/RL-Kernel/pull/344), [PR #360](https://github.com/RL-Align/RL-Kernel/pull/360), [PR #365](https://github.com/RL-Align/RL-Kernel/pull/365), [PR #367](https://github.com/RL-Align/RL-Kernel/pull/367)) |
| **End-to-end RL validation** | Ran matched native/provider train-rollout consistency experiments, TP/CP ablations, bitwise checks, throughput profiling, and performance tuning on Qwen3 workloads ([PR #377](https://github.com/RL-Align/RL-Kernel/pull/377), [PR #388](https://github.com/RL-Align/RL-Kernel/pull/388), [PR #400](https://github.com/RL-Align/RL-Kernel/pull/400), [PR #403](https://github.com/RL-Align/RL-Kernel/pull/403)) |
| **Linear-logp experiments and integration** | Designed the structured provider contract, TP vocabulary partition handling, autograd checks, and technical write-ups for portable log-probability execution ([PR #336](https://github.com/RL-Align/RL-Kernel/pull/336), [PR #352](https://github.com/RL-Align/RL-Kernel/pull/352), [PR #338](https://github.com/RL-Align/RL-Kernel/pull/338)) |

---

### 🛠️ **Tech Stack**

<div align="center">

| **Languages & Core** | **AI Infrastructure** | **Distributed & Tooling** |
|:---:|:---:|:---:|
| ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) <br> ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) <br> ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white) | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) <br> ![vLLM](https://img.shields.io/badge/vLLM-111827?style=for-the-badge) <br> ![DeepSpeed](https://img.shields.io/badge/DeepSpeed-2563EB?style=for-the-badge) | ![Ray](https://img.shields.io/badge/Ray-028CF0?style=for-the-badge&logo=ray&logoColor=white) <br> ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) <br> ![Git](https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white) |

</div>

---

### 📊 **GitHub Analytics**

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=inaniloquentee&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="400" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=inaniloquentee&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="400" />
      </td>
    </tr>
  </table>

  <br>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=inaniloquentee&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" width="800" />

  <br>
  <br>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=inaniloquentee&theme=tokyo-night&hide_border=true" alt="Activity Graph" width="100%"/>
</div>

---

<div align="center">
  <sub><i>Building efficient systems, one kernel and one iteration at a time.</i></sub>
</div>
