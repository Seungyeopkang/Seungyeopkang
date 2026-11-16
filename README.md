<h2 align="center">Seungyeop Kang · 강승엽</h2>

<p align="center">
  <b>Efficient Deep Learning</b> — model compression · neural architecture search · on-device inference
</p>

<p align="center">
  <a href="https://seungyeopkang.github.io"><img src="https://img.shields.io/badge/Homepage-2B59C3?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="mailto:a01073553545@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://fuzzy-wildebeest-406.notion.site/Seungyeop-Kang-bb873d4932e08374abde8101f85f3227?source=copy_link"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white" /></a>
  <a href="https://doi.org/10.3390/electronics15153408"><img src="https://img.shields.io/badge/Publication-Electronics%202026-4B6CB7?style=flat-square" /></a>
</p>

I make neural networks cheaper to run without losing accuracy. I search for efficient architectures, prune them, and measure the gains on real devices. I also test whether the cheap signals we search with can actually be trusted.

- 🎓 B.S. Artificial Intelligence, Kyonggi University (2027) → M.S., AutoML Lab, Chung-Ang University (2027–)
- 🔬 Now: joint pruning × quantization × low-rank compression for on-device LLMs

## Research

Full publication list: [seungyeopkang.github.io](https://seungyeopkang.github.io)

| Work | Status | Highlights |
| --- | --- | --- |
| **EEM-NAS**: Budgeted fixed-proxy search for zero-shot NAS | *Electronics* 2026 (SCIE), 1st author | 93 wins / 3 ties / 0 losses over 96 paired comparisons, under 100 proxy evaluations · [code](https://github.com/Seungyeopkang/eem-nas) |
| **Post-search optimization for DARTS-style architectures** | Manuscript in final preparation (EAAI), 1st author | ImageNet **FLOPs −27.2%** at −0.28 pp Top-1. Latency measured on iPhone (CoreML) and Exynos (ONNX Runtime) |
| **Size-aware zero-cost NAS proxies** | Under review, 1st author | Audits whether proxy signals survive once model size is controlled. Covers 24 proxies and 6 benchmark families |
| **When does proxy optimization beat random?** | Manuscript | Shows proxy-optimized selection can underperform random selection · [code](https://github.com/Seungyeopkang/zero-cost-proxy-endpoints) |

## Projects

| Project | What | Key result |
| --- | --- | --- |
| [EfficientViT-Optimization](https://github.com/Seungyeopkang/EfficientViT-Optimization) | Parallelized cascaded attention + FlashAttention | Inference latency **−24.9%** (63.9 → 48.0 ms) |
| [Industrial-Safety-Pipeline](https://github.com/Seungyeopkang/Industrial-Safety-Pipeline) | PPE detection → selective VLM verification → regulation-grounded RAG | Only **27.9%** of detections routed to the VLM. 22/22 regression tests pass |
| [smart-glass-project](https://github.com/Seungyeopkang/smart-glass-project) | Multi-pass VLM visual memory and grounded QA (AI & team lead, 6 members) | Team-led system → KIIT 2026 paper |
| [infant_safety_monitor](https://github.com/Seungyeopkang/infant_safety_monitor) | Pose-based fall detection + cry recognition (AI & team lead) | Event-level fusion with evidence clips → KIIT 2025 paper |

## Stack

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
  <img src="https://img.shields.io/badge/Core%20ML-000000?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

**Honors:** Outstanding Paper Award (Silver), KIIT 2026 · Gold, AWS DeepRacer League (Kyonggi Univ.) · Silver, Kyonggi Univ. Capstone Design 2025


**Notes:** [Paper Study](https://github.com/Seungyeopkang/Paper_Study), reading notes on NAS, pruning, and efficient models · [LLM Study](https://github.com/Seungyeopkang/llm_study), a 21-day hands-on log covering quantization, QLoRA, data curation, and SFT
