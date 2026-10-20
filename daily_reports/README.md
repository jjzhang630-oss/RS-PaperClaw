# Daily Reports

最近三天日报（最新在前）：

# [20261018](./202610/20261018.md)
## 📌 今日概况

今日共检索候选论文 9 篇；关键词+LLM 智能匹配遥感交叉论文 4 篇；最终纳入日报 4 篇。

今日研究聚焦遥感数据重建与表征学习：多高度无人机图像超分辨引入物理采样距离条件，MODIS时序重建利用土地覆盖先验，AlphaEarth嵌入分析揭示粗粒化下的稀疏性，SAR场景理解则探索冻结专家对齐以降低标注依赖。整体呈现从物理约束、先验引导到标签高效学习的多元路径。

## ✨ 今日亮点

- 多高度无人机超分辨引入物理地面采样距离条件，提升跨高度泛化。
- 土地覆盖引导的两阶段网络用于MODIS反射率时序重建，填补数据缺口。
- 冻结专家对齐实现标签高效SAR场景理解，降低标注需求。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261018] MultiAltitudeSR: Multi-Altitude Agricultural UAV Image Super-Resolution via Physical Ground Sampling Distance Conditioning | Jiang Xintong, Tian Yu, Liu Yixue, Hoyos-Villegas Valerio, Adamchuk Viacheslav, Sun Shangpeng | Department of Bioresource Engineering, McGill University；Michigan State University | 提出多高度农业无人机图像超分辨方法，以物理地面采样距离为条件提升跨高度重建效果。 | [#1539](https://github.com/thinson/RS-PaperClaw/issues/1539) |
| [20261018] LC-TSRNet: A Land-Cover-Guided Two-Stage Network for Annual MODIS Surface Reflectance Time Series Reconstruction | Zhang Wenjuan, Ma Xuesong, Li Zhen, Wang Meixiang, Yi Caimeng, Pan Jie, Su Nan, Zhang Bing | State Key Laboratory of Remote Sensing and Digital Earth, Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China (；the Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China；the Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China (；School of Artificial Intelligence, Xidian University, Xi'an, China (；College of Information and Communication Engineering, Harbin Engineering University, Harbin, China；the Key Laboratory of Advanced Marine Communication and Information Technology, Ministry of Industry and Information Technology, Harbin Engineering University, Harbin, China (；State Key Laboratory of Remote Sensing and Digital Earth, Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China | 设计土地覆盖引导的两阶段网络，重建年度MODIS地表反射率时序并填补数据缺口。 | [#1540](https://github.com/thinson/RS-PaperClaw/issues/1540) |
| [20261018] Emergent Sparsity: How Many Effective Variables Survive Coarse-Graining in AlphaEarth Embeddings? | Hirn Johannes | Image Processing Laboratory (IPL), Universitat de València | 分析AlphaEarth嵌入在粗粒化下的有效维度，揭示涌现稀疏性现象。 | [#1541](https://github.com/thinson/RS-PaperClaw/issues/1541) |
| [20261018] Preserving the Manifold: Frozen Expert Alignment for Label-Efficient SAR Scene Understanding | Eli A. Underwood, I. Taylor McKechnie, Leslie M. Collins | Duke University | 利用冻结专家对齐的视觉语言模型，实现标签高效的SAR场景理解。 | [#1542](https://github.com/thinson/RS-PaperClaw/issues/1542) |

## 🔎 观察

- 物理先验与辅助信息正成为遥感重建与超分辨的重要约束，有助于提升跨条件泛化。
- 标签高效学习在SAR等标注稀缺场景受关注，冻结专家对齐提供可行路径。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261018", "source": "oai", "checked_at": "2026-10-20T09:38:19+00:00", "source_complete": true, "candidate_count": 9, "paper_count": 4} -->

---

# [20261017](./202610/20261017.md)
## 📌 今日概况

今日共检索候选论文 5 篇；关键词+LLM 智能匹配遥感交叉论文 2 篇；最终纳入日报 2 篇。

今日研究聚焦遥感观测与跟踪中的建模与增强问题。一篇面向多光谱无人机多目标跟踪，提出光谱感知候选增强以改进扩散式MOT；另一篇利用稀疏条件依赖建模遥感观测系统，通过稀疏高斯图模型与贝叶斯推断刻画高光谱辐亮度变量关系。整体呈现从任务级跟踪优化到观测系统统计建模的双向推进。

## ✨ 今日亮点

- 多光谱无人机跟踪引入光谱感知候选增强，服务扩散式多目标跟踪。
- 遥感观测系统用稀疏高斯图模型刻画变量间条件依赖结构。
- 两篇工作分别从任务算法与统计建模切入，体现遥感AI方法多样性。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261017] Spectral-Aware Proposal Enhancement for Diffusion-Based Multispectral UAV Multi-Object Tracking | Lin Xu, Xu Tingfa, Li Tianhao, Qin Haolin, Gao Huawei, Xing Jichuan, Li Jianan | Beijing Institute of Technology, Beijing, China；Beijing Institute of Technology Chongqing Innovation Center, Chongqing, China | 面向多光谱无人机多目标跟踪，提出光谱感知候选增强以改进扩散式MOT流程。 | [#1536](https://github.com/thinson/RS-PaperClaw/issues/1536) |
| [20261017] Exploiting sparse conditional dependence in remote sensing observing systems | Kelvin M. Leung, Susiluoto Jouni, Eckert Regina, Marzouk Youssef | Massachusetts Institute of Technology ( )；NASA Jet Propulsion Laboratory；Massachusetts Institute of Technology | 利用稀疏条件依赖与稀疏高斯图模型，对遥感观测系统高光谱辐亮度进行贝叶斯建模。 | [#1537](https://github.com/thinson/RS-PaperClaw/issues/1537) |

## 🔎 观察

- 多光谱跟踪开始将光谱信息嵌入候选生成阶段，而非仅作后处理融合。
- 遥感观测系统研究强调变量依赖结构建模，统计推断与任务算法呈互补趋势。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261017", "source": "oai", "checked_at": "2026-10-20T09:36:22+00:00", "source_complete": true, "candidate_count": 5, "paper_count": 2} -->

---

# [20261016](./202610/20261016.md)
## 📌 今日概况

今日共检索候选论文 16 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日三篇论文聚焦遥感图像分割的增强与推理能力提升。ShadowCast提出动态上下文感知阴影增强，缓解数据稀缺与域偏移；GeoReason融合多模态大模型与自回归生成，试图兼顾逻辑推理与空间保真；FloodVLM-Pix构建语言引导的像素级洪水理解基准与模型。整体趋势显示，研究正从单一分割精度转向数据增强策略、推理可解释性与灾害场景专用基准的协同推进。

## ✨ 今日亮点

- 阴影增强从静态离线走向动态上下文感知，提升分割鲁棒性。
- 多模态大模型与自回归生成结合，探索推理与空间保真平衡。
- 洪水理解引入语言引导像素级基准，推动灾害遥感精细化。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261016] ShadowCast: On-the-Fly Context-Aware Shadow Augmentation for Remote Sensing Image Segmentation | Kim Yechan, Yoon Dongho, Joo Jongmin, Park JongHyun, Jeon Moongu | Gwangju Institute of Science and Technology (GIST), 123 Cheomdangwagi-ro, Buk-gu, Jeonnam-Gwangju,, Korea (；AI Laboratory, LIG Defense\&Aerospace, 333 Pangyo-ro, Bundang-gu, Seongnam-si, Gyeonggi-do,, Korea ( | 提出ShadowCast，在线生成上下文感知阴影增强，提升遥感分割对阴影干扰的鲁棒性。 | [#1504](https://github.com/thinson/RS-PaperClaw/issues/1504) |
| [20261016] GeoReason: Bridging Logical Reasoning and Spatial Fidelity in Remote Sensing Segmentation | Fan Cheng, Wu Han, Luo Tingzhang, Dong Minjing, Tang Yehui, Guo Jianyuan | City University of Hong Kong；School of Computer Science, Peking University | 提出GeoReason，结合多模态大模型与自回归生成，兼顾逻辑推理与空间保真分割。 | [#1505](https://github.com/thinson/RS-PaperClaw/issues/1505) |
| [20261016] FloodVLM-Pix: Language-Guided Pixel-Level Flood Understanding | Zhang Chengyang, Wang Zhihao, Long Zhiyu, Wang Xueqian, Yao Quanming, Wu Wei, Li Gang | Tsinghua University；National Disaster Reduction Center | 构建FloodVLM-Pix基准与模型，实现语言引导的像素级洪水理解与分割。 | [#1506](https://github.com/thinson/RS-PaperClaw/issues/1506) |

## 🔎 观察

- 数据增强正从固定策略转向样本自适应生成，阴影等干扰因素被显式建模。
- 遥感分割研究开始强调推理可解释性与空间精度并重，而非单纯追求指标提升。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261016", "source": "api", "checked_at": "2026-10-19T09:47:02+00:00", "source_complete": true, "candidate_count": 16, "paper_count": 3} -->

---
