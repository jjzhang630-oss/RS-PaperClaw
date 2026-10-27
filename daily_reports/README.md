# Daily Reports

最近三天日报（最新在前）：

# [20261025](./202610/20261025.md)
## 📌 今日概况

今日共检索候选论文 5 篇；关键词+LLM 智能匹配遥感交叉论文 1 篇；最终纳入日报 1 篇。

今日仅一篇论文，聚焦多用户对地观测卫星调度的加权公平性问题。该研究将公平性从传统单目标优化中独立出来，引入加权机制以平衡不同用户需求，反映了卫星资源分配从效率优先向兼顾公平的精细化方向演进。由于样本单一，趋势判断受限，但可见调度研究正关注多利益相关方场景下的分配正义。

## ✨ 今日亮点

- 提出多用户对地观测卫星调度中的加权公平性建模方法
- 将公平性作为独立优化目标，区别于传统效率导向调度
- 机构合作体现法国在卫星调度与多智能体公平分配领域的积累

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261025] Weighted Fairness in Multi-User Earth Observation Satellite Scheduling | Lucet Maxime, Benabbou Nawal, Beynier Aurélie, Maudet Nicolas, Picard Gauthier | LIP6, CNRS, Sorbonne Université, Paris, France；ONERA, DTIS, Université de Toulouse, Toulouse, France | 针对多用户对地观测卫星调度，提出加权公平性框架，在资源分配中兼顾不同用户权重与公平性。 | [#1572](https://github.com/thinson/RS-PaperClaw/issues/1572) |

## 🔎 观察

- 该研究将公平性引入卫星调度，暗示多用户共享星座场景下分配正义正成为独立研究维度。
- 仅单篇论文且偏理论建模，尚难判断加权公平性在真实星座规模下的计算可行性与收益。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261025", "source": "oai", "checked_at": "2026-10-27T10:04:17+00:00", "source_complete": true, "candidate_count": 5, "paper_count": 1} -->

---

# [20261024](./202610/20261024.md)
## 📌 今日概况

今日共检索候选论文 5 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日研究趋势呈现多模态与高效计算并进。少样本遥感场景分类关注方向不变性，通过组件池化与非负分解提升泛化；指代分割引入跨尺度稀疏注意力，强化视觉语言对齐与多尺度特征融合；SAR成像则聚焦开源实现，在CPU、GPU与TPU上追求高吞吐高保真。整体体现遥感AI向轻量化、跨模态与硬件适配方向发展。

## ✨ 今日亮点

- 少样本场景分类利用组件池化实现方向不变性
- 指代分割采用跨尺度稀疏注意力增强多尺度融合
- SAR成像开源实现覆盖CPU、GPU与TPU加速

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261024] Component Pooling Trained Across Orientations for Few-Shot Remote Sensing Scene Classification | Yan Bingchen, Guo Wenheng, Zhou Yuye | School of Computer Science and Information Security；Guilin University of Electronic Technology, Guilin, 541004, China；School of Information Engineering；Institute of Disaster Prevention, Langfang, 065201, China；School of Computing & Technology；Asia Pacific University of Technology & Innovation, Kuala Lumpur, 57000, Malaysia | 提出跨方向训练的组件池化方法，结合非负分解提升少样本遥感场景分类性能。 | [#1568](https://github.com/thinson/RS-PaperClaw/issues/1568) |
| [20261024] Cross-Scale Sparse Attention for Referring Segmentation in Remote Sensing | Li Yuxi, Si Lu, Liao Xia, Shen Yidong, Wei Zheng, Zhang Jun, Yuan Xin | aWestlake Institute for Advanced Study, Hangzhou, Zhejiang, China；bSchool of Engineering, Westlake University, Hangzhou, Zhejiang, China；cBeijing National Research Center for Information Science and Technology (BNRist), Tsinghua；University, Beijing, China；dSchool of Computer Science, Beijing University of Posts and Telecommunications, Beijing, China；eDepartment of Automation, Tsinghua University, Beijing, China | 设计跨尺度稀疏注意力机制，用于遥感指代分割中的视觉语言对齐与多尺度特征融合。 | [#1569](https://github.com/thinson/RS-PaperClaw/issues/1569) |
| [20261024] FastSAR: High-Throughput, High-Fidelity Open-Source SAR Image Formation on CPUs, GPUs and TPUs | Singerman Paul, Braun Tom | Penn State University | 发布FastSAR开源SAR成像框架，在CPU、GPU和TPU上实现高吞吐高保真处理。 | [#1570](https://github.com/thinson/RS-PaperClaw/issues/1570) |

## 🔎 观察

- 少样本分类与指代分割均强调多尺度与方向适应性，反映遥感视觉任务对几何变换的持续关注。
- SAR成像开源框架适配多种硬件，表明遥感数据处理正重视可复现性与计算效率的平衡。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261024", "source": "oai", "checked_at": "2026-10-27T10:00:58+00:00", "source_complete": true, "candidate_count": 5, "paper_count": 3} -->

---

# [20261023](./202610/20261023.md)
## 📌 今日概况

今日共检索候选论文 11 篇；关键词+LLM 智能匹配遥感交叉论文 6 篇；最终纳入日报 6 篇。

今日论文总体呈现出遥感与AI交叉深化趋势。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261023] DS-BiCA-Net: Pair-Preserving Cross-Temporal Modeling for Remote Sensing Change Captioning | Zhang Licheng, Akhtar Naveed, Lam Siew-Kei | School of Computing and Information Systems, the University of Melbourne, Victoria, Australia. (；Nanyang Technological University, Singapore | 聚焦Remote Sensing、State-Space Model，给出可复现的模型与评测方案。 | [#1561](https://github.com/thinson/RS-PaperClaw/issues/1561) |
| [20261023] OlmoEarth v1.3: Embeddings | Tseng Gabriel, Bastani Favyen, Patrick Alan Johnson, Zhang Yawen, Wolters Piper, Shah Ando, Sablon Hadrien, Redmon Joseph, DeHaven Heather, Ratner Rachel, Levy Sasha, Steward Jordan, Midgley Katrina, Howe Andrew, Pitelka Hunter, Schmitt Ted | Allen Institute for AI | 聚焦Remote Sensing、Earth Observation，给出可复现的模型与评测方案。 | [#1562](https://github.com/thinson/RS-PaperClaw/issues/1562) |
| [20261023] GeoLEON-CLIP: Graph-Anchored Multimodal Contrastive Learning for Geographic Region Representation | Malek Radoslaw, Soltysiak Szymon, Kawala-Sterniuk Aleksandra, Szymanski Piotr | Wroc aw University of Science and Technology Department of Artificial Intelligence Wroc aw Poland；Wrocław University of Science and Technology Department of Artificial Intelligence Wrocław Poland | 聚焦Graph-Anchored Contrastive Learning、Multimodal Geographic Representation，给出可复现的模型与评测方案。 | [#1563](https://github.com/thinson/RS-PaperClaw/issues/1563) |
| [20261023] Reuse, Don't Retrain: Efficient, Modality-Versatile Geospatial Foundation Models through Feature Distillation | Hamon Mario, Adorni Pierre, Pham Minh-Tan | Université Bretagne Sud, UMR 6074 | 聚焦Vision Transformers、Multispectral Imagery，给出可复现的模型与评测方案。 | [#1564](https://github.com/thinson/RS-PaperClaw/issues/1564) |
| [20261023] SCDM-HTD: Spectral-Wise Conditional Diffusion Model for Hyperspectral Target Detection | Shen Dunbin, Kong Wenfeng, Liu Jianjun, Ma Xiaorui, Wang Hongyu | School of Information and Communication Engineering, Dalian University of Technology, Dalian, China (；School of Artificial Intelligence and Computer Science, Jiangnan University, Wuxi, China ( | 聚焦Hyperspectral Target Detection、Spectral-Wise Conditional Diffusion Model，给出可复现的模型与评测方案。 | [#1565](https://github.com/thinson/RS-PaperClaw/issues/1565) |
| [20261023] LoCA: Enabling Multi-Modality in Geospatial Location Encoders | Koromilas Panagiotis, Vali Eleanna, Antonopoulos Diogenis, Saka Eleni, Christofis Dimitris, Nikolaos Ioannis Bountos, Klemmer Konstantin, Papoutsis Ioannis, Panagakis Yannis, Mihalis A. Nicolaou | University of Athens；The Cyprus Institute；Archimedes, Athena Research Center；National Technical University of Athens；Harokopio University；University College London；University of Cyprus | 聚焦Multimodal Learning、Contrastive Learning，给出可复现的模型与评测方案。 | [#1566](https://github.com/thinson/RS-PaperClaw/issues/1566) |

## 🔎 观察

- 基础模型与遥感任务结合持续增强，评测与推理能力成为关键。
- 多数工作关注算法有效性与泛化，而非硬件实现。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261023", "source": "oai", "checked_at": "2026-10-26T10:25:09+00:00", "source_complete": true, "candidate_count": 11, "paper_count": 6} -->

---
