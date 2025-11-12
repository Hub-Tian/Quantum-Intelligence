<!-- 
   ===============================================
   README for "New AI for Quantum Computing"
   ===============================================
-->

<h1 align="center">
  🧠 New AI for Quantum Computing <br/> From Quantum Optimization to Quantum Intelligence
</h1>

<p align="center">
  <!-- 1) Awesome Badge -->
  <a href="https://awesome.re" target="_blank">
    <img src="https://awesome.re/badge.svg" alt="Awesome Badge"/>
  </a>
  
  <!-- 2) Maintain Status Badge -->
  <img src="https://img.shields.io/badge/Maintain-Active-8A2BE2?style=flat-square&logo=github&logoColor=white" alt="Maintain Badge"/>

  <!-- 3) PR's Welcome Badge -->
  <a href="http://makeapullrequest.com" target="_blank">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat" alt="PR's Welcome"/>
  </a>

  <!-- 4) Visitor Badge -->
  <a href="https://github.com/Hub-Tian/Quantum-Intelligence" target="_blank">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=Hub-Tian.Quantum-Intelligence&left_color=%239146DE&right_color=%23E6C82D" alt="Visitor Badge"/>
  </a>
</p>

<p align="center">
  <strong>Toward a curated, living repository for Quantum Computing, Quantum Optimization, and Quantum AI.</strong>
</p>

<hr/>

# 🏡 About
This repository accompanies the paper  
<strong>“New AI for Quantum Computing: From Quantum Optimization to Quantum Intelligence”</strong> (under submission to <em>IEEE/CAA Journal of Automatica Sinica (JAS)</em>).

It is a companion, <em>awesome-style</em> resource that curates taxonomies, representative systems, and references spanning:
- **Quantum Computing Systems** (QPU hardware & hybrid architectures)  
- **Quantum Optimization** (VQE/QAOA, annealing, hybrid solvers)  
- **Quantum AI (QAI)** ()

> If you find it useful, please star ⭐ this repo and consider a [citation](#citation).

---

## 🔔 News
- **[2025-11-20]** Repository initialized with structure, tables, and placeholders.
- **[TBA]** Camera-ready materials and extended references will be added after acceptance.

---

## 📑 Table of Contents
- [Overview](#-overview)
- [Curated Tables](#-curated-tables)
  - [Quantum Computing Systems](#quantum-computing-systems)
  - [Quantum Optimization](#quantum-optimization)
  - [Quantum AI (QAI)](#quantum-ai-qai)
- [Star History](#-star-history)
- [Contributors](#-contributors)
- [Citation](#-citation)
- [License](#-license)

---

## 🌌 Overview
Quantum computing has entered a stage of **hybrid intelligence**, in which **CPU–GPU–QPU** resources are woven into unified computational fabrics for near–real-time quantum–classical workflows. Beyond pure algorithm execution, the field is rapidly moving toward **learning-capable, self-optimizing quantum systems**—from **quantum optimization** to **quantum intelligence**.

This repository tracks that evolution with structured categories, clean tables, and high-quality references (to be filled), serving as a living index for researchers and practitioners.

---

## 📚 Curated Tables

### Quantum Computing Systems
| Title / System | Type | Venue / Year | Key Specs / Notes | Refs |
|---|---|---|---|---|
| IBM Condor | Superconducting QPU | — | 1,121 qubits; roadmap node |  |
| Google Sycamore | Superconducting QPU | Nature 2019 | 53 qubits; supremacy experiments |  |
| Quantinuum H-Series | Ion-trap QPU | — | High-fidelity gates |  |
| IonQ Forte | Ion-trap QPU | — | Advanced optical addressing |  |
| PsiQuantum Omega | Photonic QPU | Nature 2025 | Manufacturable photonics platform |  |
| Microsoft Majorana-1 | Topological (proto) | — | Toward Majorana zero modes |  |
| PSNC Hybrid Cluster | Hybrid system | — | Multi-user, multi-QPU/GPU/CPU |  |
| IBM Q-Centric SC | Hybrid fabric | — | Qiskit Runtime; near-real-time |  |
| NVIDIA CUDA-Q & NVQLink | SW + Interconnect | — | 400 Gb/s; < 4 μs latency |  |

### Quantum Optimization
| Method / Benchmark | Class | Venue / Year | Notes (problem class / scale) | Refs |
|---|---|---|---|---|
| VQE family | Variational | — | Chemistry / materials |  |
| QAOA variants | Variational | — | Combinatorial optimization |  |
| Quantum annealing | Annealing | — | Ising/QUBO; industrial cases |  |
| Tensorized QML | QML | — | TN circuits, efficiency |  |
| Hybrid solvers | Hybrid | — | CPU–GPU–QPU pipelines |  |

### Quantum AI (QAI)
| System / Idea | Category | Venue / Year | Notes (LLM–QPU, agents, runtime) | Refs |
|---|---|---|---|---|
| LLM-driven QPU orchestration | Agentic runtime | — | Scheduling, prompting, CoT |  |
| AI-assisted QEC / calibration | Control | — | Feedback/stability |  |
| Quantum-enhanced learning | QML/Agent | — | Variational policies |  |
| Foundation models for circuits | FM | — | Tokenization/encoding |  |

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Hub-Tian/Quantum-Intelligence&type=Date)](https://star-history.com/#Hub-Tian/Quantum-Intelligence&Date)

---

## 👥 Contributors

- **Yonglin Tian**
- **Fei Lin**
- **Xinyu Liu**


For questions, contact **Yonglin Tian** (<yonglin.tian@ia.ac.cn>) or **Fei Lin** (<feilin@ieee.org>).  
*If you would like to contribute, please open an Issue or Pull Request.*

---

## Citation

If you find this repository useful, please consider citing this paper:

```bibtex
@misc{tian2025uavsmeetllmsoverviews,
      title={UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility}, 
      author={Yonglin Tian and Fei Lin and Yiduo Li and Tengchao Zhang and Qiyao Zhang and Xuan Fu and Jun Huang and Xingyuan Dai and Yutong Wang and Chunwei Tian and Bai Li and Yisheng Lv and Levente Kovács and Fei-Yue Wang},
      year={2025},
      eprint={2501.02341},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2501.02341}, 
}
```
 
---

## License

This project is licensed under the [MIT License](LICENSE).
