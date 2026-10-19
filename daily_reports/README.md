# Daily Reports

最近三天日报（最新在前）：

# [20261015](./202610/20261015.md)
## 📌 今日概况

今日共检索候选论文 16 篇；关键词+LLM 智能匹配遥感交叉论文 8 篇；最终纳入日报 8 篇。

今日论文总体呈现出遥感与AI交叉深化趋势。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261015] Spectral-Spatial Interpretation | Ma Haotian, Yang Ruqi, Townsend Philip | Department of Computer Sciences；Department of Forest and Wildlife Ecology；University of Wisconsin--Madison | 聚焦Shapley Value、Spectral-Spatial Interpretation，给出可复现的模型与评测方案。 | [#1492](https://github.com/thinson/RS-PaperClaw/issues/1492) |
| [20261015] Monotone Piecewise-Linear Harmonization of Multitemporal Multispectral Surface Reflectance With Unsupervised Deep Multiview Pseudoinvariant Features Learning | Lino Garda Denaro, Lin Chia-Hsiang | the Research Center for Geoinformatics, National Research and Innovation Agency (BRIN), Cibinong, Indonesia；Department of Electrical Engineering, National Cheng Kung University (NCKU), Tainan, Taiwan. (；Department of Electrical Engineering, National Cheng Kung University (NCKU), Tainan, Taiwan (R.O.C.) ( | 聚焦Unsupervised Learning、Multitemporal Remote Sensing，给出可复现的模型与评测方案。 | [#1493](https://github.com/thinson/RS-PaperClaw/issues/1493) |
| [20261015] A large-scale climate-aware satellite image dataset for domain adaptive land-cover semantic segmentation | Liu Songlin, Chen Linwei, Zhang Li, Hu Jun, Fu Ying | School of Remote Sensing Information Engineering, Wuhan University, 430079, Wuhan, Hubei, China；State Key Laboratory of Geo-information Engineering, 710054, Xi’an, Shaanxi, China；Advanced Research Institute of Multidisciplinary Science, Beijing Institute of Technology, 100081, Beijing, China；School of Computer Science and Technology, Beijing Institute of Technology, 100081, Beijing, China；School of Electronics and Communication Engineering, Sun Yat-sen University, 510006, Guangzhou, Guangdong, China | 聚焦Remote Sensing、Domain Adaptation，给出可复现的模型与评测方案。 | [#1494](https://github.com/thinson/RS-PaperClaw/issues/1494) |
| [20261015] Digital Typhoon Dataset V3: Benchmarking for Multi-spectral Extension and Analyzing Systematic Bias in Intensity Regression | Kitamoto Asanobu, Victor Le Louarn, Falczuk Noelia, Ngoc Anh Tong, Veleva Anja | National Institute of Informatics, Japan；Typhoon Science and Technology Research Center, Yokohama National University, Japan；University of Artois, France；University of Buenos Aires, Argentina；Hanoi University of Science and Technology, Vietnam；RWTH Aachen University, Germany | 聚焦Machine Learning、Benchmarking，给出可复现的模型与评测方案。 | [#1495](https://github.com/thinson/RS-PaperClaw/issues/1495) |
| [20261015] Self-Calibrated Subspace Robust PCA for Parameter-Free Removal of Mixed Noise and Line Stripes in Hyperspectral Images | Wang Wenzhe | Qingdao Preschool Education College, Qingdao, China ( | 聚焦Hyperspectral Image Denoising、Mixed Noise Removal，给出可复现的模型与评测方案。 | [#1496](https://github.com/thinson/RS-PaperClaw/issues/1496) |
| [20261015] Data-Efficient ConvNeXt Pretraining for High-Resolution Sentinel-1 GRD SAR Representation Learning | Natsume Yuki, Yun Sang-Ho, Chai Kiat Yeo | College of Computing and Data Science, Nanyang Technological University, Singapore；Earth Observatory of Singapore, Nanyang Technological University, Singapore；Asian School of the Environment, Nanyang Technological University, Singapore；School of Electrical and Electronic Engineering, Nanyang Technological University, Singapore | 聚焦ConvNeXt、Sentinel-1 GRD，给出可复现的模型与评测方案。 | [#1497](https://github.com/thinson/RS-PaperClaw/issues/1497) |
| [20261015] ISW-Agent: Integrating LLM-Driven Dialogue with n8n Workflow for Internal Solitary Wave Remote Sensing Image Processing | Zhang Hao, Liu Hengrui, Sun Lina, Meng Junmin | First Institute of Oceanography, Ministry of Natural Resources | 聚焦Remote Sensing、Large Language Model，给出可复现的模型与评测方案。 | [#1500](https://github.com/thinson/RS-PaperClaw/issues/1500) |
| [20261015] AI-Driven Disaster Response and Displacement Monitoring | Al-Emadi Noora, Imran Muhammad, Yang Yin, Weber Ingmar, Lashi Fabjan, Rigodanza Gaia, Hajzmanova Ivana, Ofli Ferda | Qatar Computing Research Institute, Hamad Bin Khalifa University, Qatar；College of Science and Engineering, Hamad Bin Khalifa University, Qatar；Saarland University, Germany；United Nations Development Programme, Austria；Internal Displacement Monitoring Centre, Switzerland | 聚焦Satellite Imagery、Disaster Response，给出可复现的模型与评测方案。 | [#1502](https://github.com/thinson/RS-PaperClaw/issues/1502) |

## 🔎 观察

- 基础模型与遥感任务结合持续增强，评测与推理能力成为关键。
- 多数工作关注算法有效性与泛化，而非硬件实现。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261015", "source": "api", "checked_at": "2026-10-19T10:01:13+00:00", "source_complete": true, "candidate_count": 16, "paper_count": 8} -->

---

# [20261014](./202610/20261014.md)
## 📌 今日概况

今日共检索候选论文 5 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日三篇论文集中体现高光谱成像与三维重建、视觉语言动作模型及SLAM的交叉融合。核心趋势是将高光谱从传统分类任务拓展至解混、跨模态token迁移与回环检测等新场景，并普遍借助高斯泼溅或冻结接口降低计算成本。研究多面向行星探测与机器人自主感知，强调光谱信息在几何与语义理解中的互补价值。

## ✨ 今日亮点

- 高光谱与3D高斯泼溅结合，实现统一解混与材质丰度估计
- 冻结VLA接口下进行高光谱token迁移，降低训练开销
- 高光谱辅助SLAM回环检测，服务行星探测自主导航

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261014] Spectral World Renderer: Unified 3D Hyperspectral Unmixing | Lee Chia-Ming, Hsiao Yu-Jou, Chang Ming-Ching, Li Xin, Liu Yu-Lun, Hsu Chih-Chung | University at Albany, State University of New York；National Yang Ming Chiao Tung University；National Cheng Kung University | 提出光谱世界渲染器，用3D高斯泼溅统一高光谱解混与材质丰度估计。 | [#1488](https://github.com/thinson/RS-PaperClaw/issues/1488) |
| [20261014] SPECTRA-VLA: Base-Fine Hyperspectral Token Transfer at Frozen Vision-Language-Action Interfaces | Hsu Chih-Chung | National Yang Ming Chiao Tung University, Taiwan ( | 在冻结视觉语言动作接口中迁移高光谱token，实现基-细光谱残差学习。 | [#1489](https://github.com/thinson/RS-PaperClaw/issues/1489) |
| [20261014] HyperLoop: Hyperspectral-Assisted Loop Closure Detection in 3D-SLAM for Planetary Exploration | Bhalla Annie, Rotondi Dennis, Giubilato Riccardo, Kai O. Arras, Stuerzl Wolfgang | Institute for Artificial Intelligence (AI), University of Stuttgart, Universitätsstraße 32；German Aerospace Center (DLR), Institute of Robotics and Mechatronics；Moon-Mars Outdoor Test Site (MMOTS) of the German Aerospace Center (DLR), comprising synchronized RGB-D and hyperspectral；c𝑘 𝑘-th cluster centre (RGB or spectral codebook) BoSW Bag-of-Spectral-Words；𝑎𝑖 Nearest-neighbour cluster assignment DLR German Aerospace Center | 利用高光谱与RGB-D融合，为行星探测3D-SLAM提供回环检测新方法。 | [#1490](https://github.com/thinson/RS-PaperClaw/issues/1490) |

## 🔎 观察

- 高光谱正从分类走向解混与跨模态迁移，与3D高斯泼溅、VLA和SLAM深度耦合。
- 多篇工作强调冻结主干或降低训练成本，反映星载与机器人端算力受限的现实约束。

---

Powered by OpenClaw🦞

---

# [20261013](./202610/20261013.md)
## 📌 今日概况

今日共检索候选论文 17 篇；关键词+LLM 智能匹配遥感交叉论文 8 篇；最终纳入日报 8 篇。

今日研究聚焦遥感基础模型的数据构建与智能体可靠性。一方面，STRATA-S12和MajorTOM等开放多传感器、多时相预训练语料被提出，支撑自监督学习；另一方面，Omni-RS统一多任务理解与生成，ReDiS和Hallucination-aware方法提升多模态推理的忠实性。同时，行为自监控与可信智能体框架强调自主对地观测中的可靠性，递归自改进则探索任务自动化新范式。

## ✨ 今日亮点

- 多传感器多时相预训练语料成为基础模型关键支撑
- 遥感多模态推理向忠实性与自进化方向演进
- 智能体自主对地观测强调可信与行为监控

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261013] Deficit-Driven Stratified Acquisition for Building STRATA-S12: An Open SAR-Optical Corpus for Self-Supervised Learning | Sanchez-Leon Christian, Chen Dongming, Wang Dongqi | Software College, Northeastern University | 构建按缺陷分层采集的SAR-光学开放语料STRATA-S12，服务自监督学习。 | [#1479](https://github.com/thinson/RS-PaperClaw/issues/1479) |
| [20261013] Omni-RS: Unifying Multi-Task Understanding and Generation in Remote Sensing | Pan Yin. Shuai Yang, Liu Yuanhao, Tang Datao, Li Jialin, Wang Hao, Liu Pei, Li Kaiyu, Zhao Cong, Cao Xiangyong | Xi'an Jiaotong University | Omni-RS统一遥感多任务理解与生成，基于多模态大模型框架。 | [#1480](https://github.com/thinson/RS-PaperClaw/issues/1480) |
| [20261013] Hallucination-aware Faithful Reasoning in Remote Sensing | Liu Yi, Zhang Jing, Feng Xiang, Tian Xiaoyu, Guo Haonan, Wang Di, Wang Zengmao, Du Bo | School of Computer Science, Chongqing University | 提出幻觉感知的忠实推理方法，提升遥感多模态大模型可靠性。 | [#1481](https://github.com/thinson/RS-PaperClaw/issues/1481) |
| [20261013] ReDiS: Reasoning-Diagnosis Self-Evolution for Multimodal Reasoning in Remote Sensing | Liu Yi, Jiang Wentao, Ni Shuo, Luo Zhiming, Wang Di, Wang Zengmao, Zhang Jing, Du Bo | School of Computer Science, Wuhan University；Zhongguancun Academy；National Key Laboratory of Science and Technology on Space-Born Intelligent Information Processing；Beijing Institute of Technology | ReDiS通过推理-诊断自进化增强遥感多模态推理与视觉定位。 | [#1482](https://github.com/thinson/RS-PaperClaw/issues/1482) |
| [20261013] Behavioural self-monitoring for autonomous earth observation agents: The attribute reliability monitor (ARM) | Alejandro D. Mousist | Thales Alenia Space España | 面向自主对地观测智能体，提出属性可靠性监控器实现行为自监控。 | [#1483](https://github.com/thinson/RS-PaperClaw/issues/1483) |
| [20261013] MajorTOM:Elliot Pretrain, A Multi-Sensor, Multi-Temporal Pretraining Dataset for Earth Observation | Carmen Oliver Huidobro, Czerkawski Mikolaj, Monsalvez-Pozo Kevin, Aybar Cesar, Camps-Valls Gustau, Oscar J. Pellicer-Valero | Universitat de València, Valencia, Spain | 发布MajorTOM多传感器多时相对地观测预训练数据集，支撑基础模型。 | [#1484](https://github.com/thinson/RS-PaperClaw/issues/1484) |
| [20261013] Trust Before Autonomy: Rethinking Agentic Remote Sensing for Crisis Response | Angelidis Georgios, Psiris Aggelos, Evangelatos Spyridon, Lagkas Thomas, Sarigiannidis Panagiotis, Varlamis Iraklis, Georgios Th. Papadopoulos | Harokopio University of Athens；Dimocritus University of Thrace；University of Western Macedonia | 反思危机响应中智能体遥感，强调自主前需建立信任机制。 | [#1485](https://github.com/thinson/RS-PaperClaw/issues/1485) |
| [20261013] The Last Remote Sensing Model Built by Humans? Casting Any Earth Observation Task as Recursive Self-Improvement | Zhao Sijie, Zhou Zeqi, Qi Heli, Fu Xuanchao, Zheng Zhuo, Xia Junshi, Wang Junjue, Xuan Weihao, Yokoya Naoto | University of Tokyo；Stanford University；Yokoya-Lab-UTokyo/RSI4 EO | 将任意对地观测任务转化为递归自改进，探索编码智能体自动化。 | [#1486](https://github.com/thinson/RS-PaperClaw/issues/1486) |

## 🔎 观察

- 预训练语料从单传感器向多传感器多时相演进，数据分层与缺陷驱动采集受关注。
- 遥感大模型研究正从性能提升转向可信、忠实与自主智能体的可靠性保障。

---

Powered by OpenClaw🦞

---
