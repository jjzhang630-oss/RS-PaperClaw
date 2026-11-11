# Daily Reports

最近三天日报（最新在前）：

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

# [20261105](./202611/20261105.md)
## 📌 今日概况

今日共检索候选论文 14 篇；关键词+LLM 智能匹配遥感交叉论文 6 篇；最终纳入日报 6 篇。

今日研究覆盖热带气旋临近预报、全国尺度树种制图、开放词汇分割、地理基础模型在高分辨率影像上的评测、跨视角三维重建以及空间物理边界检测。整体趋势显示，深度学习继续向多模态融合与开放场景扩展，同时针对基础模型在遥感领域的适用性开展系统性基准测试。应用导向明显，涵盖气象灾害、森林生态与空间天气。

## ✨ 今日亮点

- 热带气旋风场与强度临近预报利用静止卫星影像和神经网络实现。
- 瑞士全国尺度树种组成制图融合高分辨率航空影像与多模态数据。
- TerraMesh-Masks推动地球观测开放词汇分割与多模态数据集构建。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261105] Nowcasting of Tropical Cyclone Wind Fields and Intensity from Geostationary Imagery | Donike Simon, Nath Pritthijit, Radin Cristina, Avenas Arthur, Cartuyvels Ruben, Diaz Emiliano, William K. Jones, Jungbluth Anna | Earth Systems Lab；University of Valencia；University of Cambridge；Max Planck Institute for Marine Microbiology, Bremen, Germany；Imperial College London | 基于静止卫星影像与神经网络，开展热带气旋风场和强度的临近预报研究。 | [#65](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/65) |
| [20261105] National-scale mapping of tree species composition in Switzerland from high-resolution aerial imagery and multimodal data | Zhou Yixin, Ferrari Luca, Verena C. Griess, Rehush Nataliia, Schindler Konrad, Beloiu Mirela | ETH Swiss Geo Lab；Ecosystem Ecology Group, Swiss Federal Research Institute WSL | 利用高分辨率航空影像与多模态数据，实现瑞士全国尺度树种组成制图。 | [#66](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/66) |
| [20261105] TerraMesh-Masks: Open-Vocabulary Segmentation for Earth Observation | Blumenstiel Benedikt, Devimeux Hugues, Jakubik Johannes, Schindler Konrad | IBM Research | 提出TerraMesh-Masks，面向地球观测的开放词汇分割与多模态数据集。 | [#67](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/67) |
| [20261105] When GeoFMs Meet VHR: Benchmarking Foundation Models on Very High Resolution Earth Observation Imagery | Kshitij Raj Sharma, Adorni Pierre, Pham Minh-Tan, Tiede Dirk, Lefèvre Sébastien | Universit\'e Bretagne Sud, IRISA, France；University of Salzburg, Department of Geoinformatics, Austria；UiT The Arctic University of Norway, Troms, Norway | 系统评测地理基础模型在甚高分辨率地球观测影像上的迁移与预训练表现。 | [#68](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/68) |
| [20261105] Georeferenced Cross-View 3D Reconstruction from Ground and Satellite Images | David G. Shatwell, Shah Mubarak | Institute of Artificial Intelligence, University of Central Florida；only the local scene geometry, but also localizing every camera center and 3 D | 从地面与卫星影像进行地理参考的跨视角三维重建，并估计相机位姿。 | [#69](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/69) |
| [20261105] MP-DualNet: A Dual-Branch Deep Learning Approach for Magnetopause Boundary Detection Using Simulated SXI Images | Zhong Cheng, Yang Zhongwei, Sun Tianran, Huang Chengyan, Liu Jiajia, Guo Jingnan, Wang Yuming, Wang Chi | National Key Laboratory of Deep Space Exploration/School of Earth and Space Sciences, University of；State Key Laboratory of Solar Activity and Space Weather, National Space Science Center, Chinese；Academy of Sciences, Beijing 100190, China；CAS Center for Excellence in Comparative Planetology/CAS Key Laboratory of Geospace；Environment/Mengcheng National Geophysical Observatory, University of Science and Technology of | 利用模拟SXI图像与双分支网络，检测磁层顶边界以服务SMILE任务。 | [#70](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/70) |

## 🔎 观察

- 基础模型评测与开放词汇分割同日出现，反映遥感社区正从模型构建转向适用性验证与开放场景适配。
- 多模态数据融合成为高频手段，覆盖森林制图与三维重建，显示单一影像模态的局限正被系统性弥补。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261105", "source": "api", "checked_at": "2026-11-06T16:06:35+00:00", "source_complete": true, "candidate_count": 14, "paper_count": 6} -->

---
