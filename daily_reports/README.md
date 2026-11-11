# Daily Reports

最近三天日报（最新在前）：

# [20261110](./202611/20261110.md)
## 📌 今日概况

今日共检索候选论文 21 篇；关键词+LLM 智能匹配遥感交叉论文 2 篇；最终纳入日报 2 篇。

今日遥感AI研究呈现两个互补方向：一是自监督学习在跨传感器检索中的应用，RS-JEPA结合联合嵌入预测架构与扫描路径视图，并引入Vision Mamba处理跨传感器差异；二是面向应急监测的超轻量模型设计，picoEmergencyNet通过注意力增强和深度可分离空洞卷积实现航空图像分类。两篇工作分别从表征学习和模型效率切入，反映遥感领域对跨模态泛化与边缘部署的双重关注。

## ✨ 今日亮点

- RS-JEPA利用扫描路径视图构建自监督预训练，提升跨传感器图像检索性能。
- picoEmergencyNet以超小参数量实现应急监测航空图像分类，兼顾精度与效率。
- 两篇工作分别聚焦自监督跨模态表征与轻量化部署，体现遥感AI实用化趋势。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261110] RS-JEPA: Remote Sensing Joint-Embedding Predictive Architecture with Scan-Path Views for Cross-Sensor Image Retrieval | Rachamalla Tanishq, Kaushik Srishti, Muhammad Attique Khan, Camps-Valls Gustau, Swalpa Kumar Roy | Prince Mohammad Bin Fahd University, Al Khobar, Saudi Arabia；Universitat de València, Valencia, Spain；Tezpur University, Assam, India | 提出RS-JEPA，利用扫描路径视图和Vision Mamba进行自监督预训练，实现跨传感器遥感图像检索。 | [#79](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/79) |
| [20261110] picoEmergencyNet : Attention-Enhanced Ultra-Small Deep Learning Model for Aerial Image Classification in Emergency Monitoring | Kyrkou Christos | KIOS Research and Innovation Center of Excellence；University of Cyprus | 设计picoEmergencyNet，采用注意力增强和深度可分离空洞卷积的超轻量CNN，用于应急监测航空图像分类。 | [#80](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/80) |

## 🔎 观察

- 跨传感器检索与超轻量模型分别对应遥感数据异构性和边缘计算约束，表明研究正从单一精度导向转向场景适配。
- 自监督预训练与极简网络设计并行发展，暗示未来遥感AI可能更注重预训练表征的迁移性与模型部署的可行性。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261110", "source": "api", "checked_at": "2026-11-11T15:59:28+00:00", "source_complete": true, "candidate_count": 21, "paper_count": 2} -->

---

# [20261107](./202611/20261107.md)
## 📌 今日概况

今日共检索候选论文 8 篇；关键词+LLM 智能匹配遥感交叉论文 0 篇；最终纳入日报 0 篇。

当日未检索到符合条件并纳入日报的论文。

## 🔎 观察

- 已在元数据公开后重新核查，确认当日没有符合遥感与 AI / 计算机视觉范围的论文。
- 此为已复核的无匹配结果，无论文处理失败。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261107", "source": "api", "checked_at": "2026-11-11T15:58:38+00:00", "source_complete": true, "candidate_count": 8, "paper_count": 0} -->

---

# [20261106](./202611/20261106.md)
## 📌 今日概况

今日共检索候选论文 11 篇；关键词+LLM 智能匹配遥感交叉论文 5 篇；最终纳入日报 5 篇。

今日研究覆盖超分辨率地形模型辅助GEDI定位校正、无人机浅水图像零样本评估与恢复、无人机视觉畜牧检测、高光谱目标检测系统瓶颈量化，以及免训练多模态大模型超高分遥感证据获取。整体呈现两大趋势：一是面向具体遥感任务（如GEDI定位、高光谱检测）的系统级误差与性能分析受到关注；二是无人机与多模态大模型结合，推动零样本、免训练方法在复杂场景中的实用化。

## ✨ 今日亮点

- 超分DTM在波束级与机载LiDAR校正一致，但足迹级不一致
- 零样本基准评估统一多模态模型浅水无人机图像恢复能力
- 免训练GeoJeV用空间概率实现超高分遥感高效证据获取

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261106] Super-resolved digital terrain models for GEDI geolocation correction: agreement with airborne LiDAR DTM-based corrections at the beam level, not the footprint level | Yuda Natsuki, Shirota Shinichiro | Hitotsubashi University, 2-1 Naka, Kunitachi, Tokyo 186-8601, Japan | 评估超分DTM用于GEDI定位校正，发现与机载LiDAR校正仅在波束级一致，足迹级不一致。 | [#72](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/72) |
| [20261106] Zero-Shot Benchmarking of Unified Multimodal Models for Shallow-Water UAV Image Distortion Assessment and Restoration | Scilla Dario, Omar A. Lopez, Rosso Mattia, Johansen Kasper, Matthew F. McCabe | and Livability Initiative, King Abdullah University of Science and Technology；Abdullah University of Science and Technology, Thuwal 23955-6900, Saudi | 对统一多模态模型进行零样本基准测试，评估浅水无人机图像畸变评估与恢复性能。 | [#73](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/73) |
| [20261106] UAV-Based Computer Vision for Cattle Detection and Feed Bunk Spatial Analysis | Pedro Oliveira Torrente, Diego Giaretta de Paulo, Lucas Pascotti Valem, Yan Jianglong, Everton Castelão Tetila, Jayme Garcia Arnal Barbedo, Zhao Liang | Institute of Mathematics and Computer Science (ICMC), University of São Paulo (USP), São Carlos - SP, Brazil；the Federal University of Grande Dourados (UFGD), Dourados - MS, Brazil；the Faculty of Philosophy, Sciences and Letters at Ribeir ao Preto (FFCLRP); University of São Paulo (USP), Ribeir ao Preto - SP, Brazil | 利用无人机计算机视觉检测牛只并分析饲喂槽空间分布，服务精准畜牧管理。 | [#74](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/74) |
| [20261106] Quantifying System-Level Performance Bottlenecks in Hyperspectral Target Detection | Cañas Chase, John P. Kerekes | Imaging Science, Rochester Institute of Technology, Rochester, NY, 14623 | 量化高光谱目标检测的系统级性能瓶颈，通过敏感性分析与ROC曲线识别关键限制因素。 | [#75](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/75) |
| [20261106] GeoJeV: Unified Spatial Probability for Training-Free Efficient Evidence Acquisition in Ultra-High-Resolution Remote Sensing | Niu Xinyi, Chen Lingfeng, Zhang Jiehua, Hu Panhe, Liu Li, Liu Zhen, Liu Yongxiang | College of Electronic Science and Technology, National University of Defense Technology, Changsha, Hunan, China | 提出免训练GeoJeV框架，以统一空间概率实现超高分遥感区域级证据高效获取。 | [#76](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/76) |

## 🔎 观察

- 超分DTM辅助GEDI校正的尺度依赖表明，数据产品验证需明确波束与足迹层级差异。
- 免训练多模态方法在超高分遥感中兴起，降低标注依赖但需关注空间概率可靠性。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261106", "source": "api", "checked_at": "2026-11-09T16:04:38+00:00", "source_complete": true, "candidate_count": 11, "paper_count": 5} -->

---
