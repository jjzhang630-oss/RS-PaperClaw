# Daily Reports

最近三天日报（最新在前）：

# [20261019](./202610/20261019.md)
## 📌 今日概况

今日共检索候选论文 11 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日研究呈现三条并行脉络：高光谱分类引入随机潜世界建模以预测未来状态，提升表征学习能力；星上AI处理链覆盖从应用开发到嵌入式部署与任务级编排，强调工程化落地；植被指数提取工具则聚焦ROI空间一致性分析，服务精细农业。整体趋势显示遥感AI正从单一模型创新转向系统级部署与领域专用工具开发，兼顾预测性建模与轻量化实现。

## ✨ 今日亮点

- 高光谱分类探索随机潜世界建模，通过预测未来状态增强表征学习。
- 星上AI处理链实现从开发到嵌入式部署及任务级编排的全流程覆盖。
- 植被指数提取工具强调ROI空间一致性，支撑草坪影像精细分析。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261019] See the Future, Classify the Present: Stochastic Latent World Modeling for Hyperspectral Images | Ahmad Muhammad, Vivone Gemine, Hänsch Ronny, Sohaib Ahmed, Mazzara Manuel, Hong Danfeng | the Khanpur Institute of Technology, Khanpur, Pakistan. (；the National Research Council - Institute of Methodologies for Environmental Analysis (CNR-IMAA), Tito, Italy (；Department of SAR Technology, German Aerospace Center (DLR), Germany. (；Institute of Software Development and Engineering, Innopolis University, Innopolis,, Russia. (；School of Automation, Southeast University, Nanjing, China. ( | 提出随机潜世界建模用于高光谱图像分类，通过潜状态预测未来以学习更具判别性的表征。 | [#1544](https://github.com/thinson/RS-PaperClaw/issues/1544) |
| [20261019] A Generic On-Board AI Processing Chain for Earth Observation: From Application Development to Embedded Deployment and Mission-Level Orchestration | Michel-Fran{\c c}ois Foulon, Liz Ramos Medina, Goudemant Thomas, Szywala Clotilde, Robles Virgile, Petitjean Cl{é}ment, Hankache Ad{è}le, Hlimi Omar | Thales Alenia Space；IRT Saint Exupéry；Tarides | 构建通用星上AI处理链，涵盖应用开发、嵌入式部署与任务级编排，并以野火分割为例验证。 | [#1545](https://github.com/thinson/RS-PaperClaw/issues/1545) |
| [20261019] A Flexible ROI Analysis Tool for Spatially Consistent Vegetation Index Extraction from Turfgrass Imagery | Ku Kibon, Thai Thanh Tuan, Ahn Jinhyun | Department of Electrical and Computer Engineering, Iowa State University, Ames, IA 50011, USA；Multimedia Communications Laboratory, University of Information Technology, Ho Chi Minh city 70000, Vietnam；Vietnam National University, Ho Chi Minh city 70000, Vietnam；Department of Management Information Systems, Jeju National University, Jeju 63243, Republic of Korea | 开发灵活ROI分析工具，从草坪影像中提取空间一致的植被指数，支持多光谱图像处理。 | [#1546](https://github.com/thinson/RS-PaperClaw/issues/1546) |

## 🔎 观察

- 高光谱分类开始借鉴世界模型思想，从静态特征提取转向动态潜状态预测，可能提升小样本下的泛化能力。
- 星上AI研究正从算法验证走向部署编排全链路，量化与嵌入式优化成为遥感落地关键环节。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261019", "source": "oai", "checked_at": "2026-10-20T09:42:11+00:00", "source_complete": true, "candidate_count": 11, "paper_count": 3} -->

---

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
