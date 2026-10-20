# Daily Reports

最近三天日报（最新在前）：

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

# [20261015](./202610/20261015.md)
## 📌 今日概况

今日共检索候选论文 16 篇；关键词+LLM 智能匹配遥感交叉论文 8 篇；最终纳入日报 8 篇。

今日研究覆盖可解释性、多时相协调、域适应数据集、基准评测、高光谱去噪、SAR自监督预训练、LLM工作流与灾害响应等方向。整体趋势显示：遥感AI正从单一模型性能转向数据质量、跨域泛化与系统级集成；多光谱与SAR数据的高效利用、无监督/自监督方法受到持续关注；同时，面向实际应用的自动化流程与灾害监测成为新的研究热点。

## ✨ 今日亮点

- 可解释性方法引入Shapley值进行光谱-空间全网格归因，提升多光谱数据通道相关性分析。
- 多时相反射率协调采用无监督深度多视图伪不变特征学习，实现单调分段线性协调。
- 发布气候感知大规模卫星图像数据集，推动土地覆盖语义分割的域适应研究。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261015] Spectral-Spatial Interpretation | Ma Haotian, Yang Ruqi, Townsend Philip | Department of Computer Sciences；Department of Forest and Wildlife Ecology；University of Wisconsin--Madison | 提出基于Shapley值的光谱-空间全网格归因方法，用于多光谱数据通道相关性解释。 | [#1492](https://github.com/thinson/RS-PaperClaw/issues/1492) |
| [20261015] Monotone Piecewise-Linear Harmonization of Multitemporal Multispectral Surface Reflectance With Unsupervised Deep Multiview Pseudoinvariant Features Learning | Lino Garda Denaro, Lin Chia-Hsiang | the Research Center for Geoinformatics, National Research and Innovation Agency (BRIN), Cibinong, Indonesia；Department of Electrical Engineering, National Cheng Kung University (NCKU), Tainan, Taiwan. (；Department of Electrical Engineering, National Cheng Kung University (NCKU), Tainan, Taiwan (R.O.C.) ( | 利用无监督深度多视图伪不变特征学习，实现多时相多光谱地表反射率单调分段线性协调。 | [#1493](https://github.com/thinson/RS-PaperClaw/issues/1493) |
| [20261015] A large-scale climate-aware satellite image dataset for domain adaptive land-cover semantic segmentation | Liu Songlin, Chen Linwei, Zhang Li, Hu Jun, Fu Ying | School of Remote Sensing Information Engineering, Wuhan University, 430079, Wuhan, Hubei, China；State Key Laboratory of Geo-information Engineering, 710054, Xi’an, Shaanxi, China；Advanced Research Institute of Multidisciplinary Science, Beijing Institute of Technology, 100081, Beijing, China；School of Computer Science and Technology, Beijing Institute of Technology, 100081, Beijing, China；School of Electronics and Communication Engineering, Sun Yat-sen University, 510006, Guangzhou, Guangdong, China | 构建气候感知大规模卫星图像数据集，支持土地覆盖语义分割的域适应基准评测。 | [#1494](https://github.com/thinson/RS-PaperClaw/issues/1494) |
| [20261015] Digital Typhoon Dataset V3: Benchmarking for Multi-spectral Extension and Analyzing Systematic Bias in Intensity Regression | Kitamoto Asanobu, Victor Le Louarn, Falczuk Noelia, Ngoc Anh Tong, Veleva Anja | National Institute of Informatics, Japan；Typhoon Science and Technology Research Center, Yokohama National University, Japan；University of Artois, France；University of Buenos Aires, Argentina；Hanoi University of Science and Technology, Vietnam；RWTH Aachen University, Germany | 发布Digital Typhoon数据集V3，扩展多光谱基准并分析强度回归中的系统性偏差。 | [#1495](https://github.com/thinson/RS-PaperClaw/issues/1495) |
| [20261015] Self-Calibrated Subspace Robust PCA for Parameter-Free Removal of Mixed Noise and Line Stripes in Hyperspectral Images | Wang Wenzhe | Qingdao Preschool Education College, Qingdao, China ( | 提出自校准子空间鲁棒PCA方法，实现高光谱图像混合噪声与线状条纹的无参数去除。 | [#1496](https://github.com/thinson/RS-PaperClaw/issues/1496) |
| [20261015] Data-Efficient ConvNeXt Pretraining for High-Resolution Sentinel-1 GRD SAR Representation Learning | Natsume Yuki, Yun Sang-Ho, Chai Kiat Yeo | College of Computing and Data Science, Nanyang Technological University, Singapore；Earth Observatory of Singapore, Nanyang Technological University, Singapore；Asian School of the Environment, Nanyang Technological University, Singapore；School of Electrical and Electronic Engineering, Nanyang Technological University, Singapore | 面向Sentinel-1 GRD SAR数据，采用数据高效ConvNeXt自监督预训练进行表示学习。 | [#1497](https://github.com/thinson/RS-PaperClaw/issues/1497) |
| [20261015] ISW-Agent: Integrating LLM-Driven Dialogue with n8n Workflow for Internal Solitary Wave Remote Sensing Image Processing | Zhang Hao, Liu Hengrui, Sun Lina, Meng Junmin | First Institute of Oceanography, Ministry of Natural Resources | 集成LLM对话与n8n工作流，构建内孤立波遥感图像处理自动化代理系统。 | [#1500](https://github.com/thinson/RS-PaperClaw/issues/1500) |
| [20261015] AI-Driven Disaster Response and Displacement Monitoring | Al-Emadi Noora, Imran Muhammad, Yang Yin, Weber Ingmar, Lashi Fabjan, Rigodanza Gaia, Hajzmanova Ivana, Ofli Ferda | Qatar Computing Research Institute, Hamad Bin Khalifa University, Qatar；College of Science and Engineering, Hamad Bin Khalifa University, Qatar；Saarland University, Germany；United Nations Development Programme, Austria；Internal Displacement Monitoring Centre, Switzerland | 利用卫星影像与机器学习开展灾害响应和人口流离失所监测的AI驱动应用研究。 | [#1502](https://github.com/thinson/RS-PaperClaw/issues/1502) |

## 🔎 观察

- 可解释性与数据协调方法并进，反映遥感AI正从精度导向转向可信与可复用导向。
- 自监督预训练与无监督域适应成为应对标注稀缺和跨域差异的主流技术路径。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261015", "source": "api", "checked_at": "2026-10-19T10:01:13+00:00", "source_complete": true, "candidate_count": 16, "paper_count": 8} -->

---
