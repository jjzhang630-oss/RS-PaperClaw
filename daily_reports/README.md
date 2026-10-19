# Daily Reports

最近三天日报（最新在前）：

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
