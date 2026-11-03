# Daily Reports

最近三天日报（最新在前）：

# [20261101](./202611/20261101.md)
## 📌 今日概况

今日共检索候选论文 8 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日研究聚焦遥感基础模型与多模态问答。三篇论文分别探索地表变化预测的嵌入空间建模、Sentinel-2土地覆盖的非生成式语言问答，以及异构光谱图像的统一基础模型。趋势显示，遥感AI正从单一任务模型转向跨传感器、跨模态的通用表征学习，同时强调预测与问答的可信度与校准性。

## ✨ 今日亮点

- 地表变化预测转向嵌入空间时序建模，提升泛化性。
- Sentinel-2问答采用非生成式校准方法，增强答案可靠性。
- 异构光谱统一基础模型实现跨传感器迁移与多源融合。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261101] Forecasting Earth Surface Change in Embedding Space | Li Jingtao, Jaffer Sadiq, Madhavapeddy Anil, Sousa Pedro, Ortiz Anthony, Gao Kyle, Feng Zhengpeng, Zhong Yanfei, White Kevin, Keshav Srinivasan | Department of Computer Science, University of Cambridge；Microsoft AI for Good Research Lab；Aalto University；Wuhan University | 提出在嵌入空间进行地表变化时序预测，利用基础模型表征提升跨区域泛化能力。 | [#33](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/33) |
| [20261101] EarthJev: Calibrated, Non-Generative Answers to Natural-Language Questions about Sentinel-2 Land Cover | Benfenati Domenico, Antonio Maria Rinaldi, Tommasino Cristian | Department of Electrical Engineering and Information Technology (DIETI), University of Naples Federico II, Via Claudio, 21, Naples, 80125, Italy | 构建EarthJev系统，为Sentinel-2土地覆盖提供校准的非生成式自然语言问答。 | [#34](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/34) |
| [20261101] SpecUltra: A Unified Foundation Model for Heterogeneous Spectral Images | Kong Weili, Liu Baisen, Bi Xiaojun, Pei Jiaming | School of Information and Communication Engineering, Harbin Engineering University, Harbin 150001, China；School of Electronic and Information Engineering, Heilongjiang Institute of Technology, Harbin 150050, China；School of Information Engineering, Minzu University of China, Beijing 100081, China；School of Computer Science, The University of Sydney, Sydney, NSW 2006, Australia | 提出SpecUltra统一基础模型，处理高光谱与多光谱异构图像并支持跨传感器迁移。 | [#35](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/35) |

## 🔎 观察

- 遥感基础模型正从单模态向异构光谱统一建模演进，跨传感器迁移成为关键能力。
- 非生成式问答与嵌入空间预测均强调可信度，反映遥感AI对校准与泛化的重视。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261101", "source": "api", "checked_at": "2026-11-03T16:09:22+00:00", "source_complete": true, "candidate_count": 8, "paper_count": 3} -->

---

# [20261031](./202610/20261031.md)
## 📌 今日概况

今日共检索候选论文 10 篇；关键词+LLM 智能匹配遥感交叉论文 7 篇；最终纳入日报 7 篇。

今日研究呈现多源遥感数据与AI方法深度融合的趋势。城市功能知识迁移关注数据不均下的全局表征学习；边缘-云-太空连续体推理强调能耗感知的分布式部署；跨视角指代推理拓展视觉定位至多视角场景。地球嵌入驱动自适应土地单元划分，微波AI实现全天候北极融池比例反演。UAV高光谱数据集支撑海岸栖息地制图，空间不确定性分析则面向预算受限的高光谱场景检测。整体上，方法创新与数据集构建并重，应用覆盖城市、极地、海岸与农业生态。

## ✨ 今日亮点

- 城市功能知识迁移利用全局表征应对数据不均，提升跨城市泛化能力。
- STLT系统面向边缘-云-太空连续体，实现能耗感知的分布式DNN推理。
- MASSIMAL数据集提供UAV高光谱与地面真值，服务挪威海岸栖息地制图。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261031] Urban functional knowledge transfer through global representations amid uneven data | Liu Junyuan, Wang Xinglei, Dong Guangsheng, Sha Hao, Zeng Zichao, Deng Zhicheng, Feng Jiazhuang, Wang Xiang, Cheng Tao | a SpaceTimeLab, Department of Civil, Environmental and Geomatic Engineering, University；College London, London, WC1 E 6 BT, United Kingdom b State Key Laboratory of Information Engineering in Surveying, Mapping and Remote；Sensing, Wuhan University, Wuhan, 430079, China | 提出基于POI对齐嵌入的全局表征方法，实现数据不均条件下的城市功能知识跨城迁移。 | [#25](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/25) |
| [20261031] STLT: A Novel System for Energy-Aware Distributed Inference in the Edge-Cloud-Space Continuum | Stanisic Andrija, Gravara Milos, Juan Luis Herrera, Nastic Stefan | University of Extremadura Spain | 设计STLT系统，在边缘-云-太空连续体中通过DNN分割实现能耗感知的分布式推理。 | [#26](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/26) |
| [20261031] Grounding Across Views: Cross-View Referring Reasoning for Visual Grounding | Gan Hao, Wang Liuqian, Li Shuang, Gao Yufei, Chao Wentao, Fu Chong, Liu Chengming, Shi Lei | Zhengzhou University, Henan, China | 面向跨视角指代推理，利用视角感知推理与视觉示例实现目标地理定位。 | [#27](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/27) |
| [20261031] Adaptive Land Units from Earth Embeddings | Alonso Albert, Jamal Jokar Arsanjani, Andres R. Masegosa | Department of Computer Science, Aalborg University, Copenhagen, Denmark；Department of Sustainability and Planning, Aalborg University, Copenhagen, Denmark | 基于地球嵌入与贝叶斯层次聚类，无监督生成自适应土地单元以支撑土地利用建模。 | [#28](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/28) |
| [20261031] An all-weather microwave-based AI retrieval of pan-Arctic melt pond fraction | Aparício Sara, Driscoll Simon, Mark R. Drinkwater, Flocco Daniela | aCENSE - Center for Environmental and Sustainability Research & CHANGE - Global Change and；Sustainability Institute, NOVA School of Science and Technology, Universidade Nova de Lisboa, Campus de；bDepartment of Applied Mathematics and Theoretical Physics, University of Cambridge, United Kingdom；dDipartimento di Scienze della Terra, dell’Ambiente e delle Risorse, Università degli Studi di Napoli “Federico；eCoNISMA - Consorzio Nazionale Interuniversitario per le Scienze del Mare, Roma, Italy | 利用微波遥感与XGBoost构建全天候AI模型，反演泛北极海冰融池比例。 | [#29](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/29) |
| [20261031] The MASSIMAL Dataset: UAV Hyperspectral Images and Ground Truth Observations for Coastal Habitat Mapping in Norway | Martin Hansen Skjelvareid, Rinde Eli, Hancke Kasper, Blix Katalin, Galice Guillaume Hoarau, Grometto Nicolo, Maia Røst Kile | ¹UiT The Arctic University of Norway, Hansine Hansens veg 18；²Norwegian Institute for Water Research (NIV A), Sognsveien 72；³Nord University, Universitetsall´een 11 | 发布MASSIMAL数据集，含UAV高光谱影像与地面观测，用于挪威海岸海藻床等栖息地制图。 | [#30](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/30) |
| [20261031] Spatial Uncertainty Analytics for Budget-Limited Inspection of Hyperspectral Scenes | Sharma Ritesh, Motai Yuichi | RITESH SHARMA,Virginia Commonwealth University, USA；YUICHI MOTAI,Virginia Commonwealth University, USA；Authors’ Contact Information: Ritesh Sharma, Virginia Commonwealth University, Richmond, Virginia, USA | 针对预算受限的高光谱场景检测，提出空间不确定性分析与主动学习采样策略。 | [#31](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/31) |

## 🔎 观察

- 城市功能与土地单元研究均强调表征学习与无监督聚类，反映对数据不均和标签稀缺的应对。
- 边缘-太空推理与跨视角定位表明遥感AI正从单源静态分析转向多节点动态协同。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261031", "source": "api", "checked_at": "2026-11-03T16:02:36+00:00", "source_complete": true, "candidate_count": 10, "paper_count": 7} -->

---

# [20261030](./202610/20261030.md)
## 📌 今日概况

今日共检索候选论文 3 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日研究聚焦遥感数据的高效表征与端到端学习。SAR时序作物分类引入物理引导的自监督预训练，结合极化特征与BERT架构提升时序建模能力；高光谱分类提出紧凑布尔对比表示，以二值化方法降低计算复杂度；太阳能潜力评估则探索跳过显式几何建模，直接从卫星影像端到端预测。三篇工作分别从自监督、二值化表征和端到端回归角度，推动遥感任务在标注效率与计算成本上的优化。

## ✨ 今日亮点

- SAR-TS-BERT将物理引导自监督与极化特征结合，用于SAR时序作物分类。
- 光谱Haar二值化器以紧凑布尔对比表示实现轻量高光谱分类。
- 端到端学习直接从卫星影像预测屋顶太阳能潜力，无需显式几何。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261030] SAR-TS-BERT: Physics-Guided Self-Supervised Pre-Training With Polarimetric Features for SAR Time-Series Crop Classification | Wang Jieqiu, Zhang Yuhan, Zheng Bo, Zhang Shaoming | College of Surveying and Geo-Informatics, Tongji University, Shanghai, China ( | 提出物理引导自监督预训练框架SAR-TS-BERT，融合极化特征提升SAR时序作物分类性能。 | [#21](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/21) |
| [20261030] Spectral Haar Binarizer: Compact Boolean Contrast Representations for Hyperspectral Classification | Romaszewski Michał, Głomb Przemysław | Institute of Theoretical and Applied Informatics, Polish Academy of Sciences | 设计光谱Haar二值化器生成紧凑布尔对比表示，用于轻量高光谱分类与特征选择。 | [#22](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/22) |
| [20261030] An Empirical Study on Learning Rooftop Solar Potential from Satellite Imagery Directly Without Explicit Geometry | Lee Joshua | Skyline High School | 实证研究端到端学习直接从卫星影像预测屋顶太阳能潜力，绕过显式几何建模。 | [#23](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/23) |

## 🔎 观察

- 自监督预训练与物理先验结合成为SAR时序分析趋势，有望缓解标注稀缺问题。
- 二值化与端到端方法分别从表征压缩和流程简化降低遥感任务计算与建模成本。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261030", "source": "api", "checked_at": "2026-11-02T03:08:59+00:00", "source_complete": true, "candidate_count": 3, "paper_count": 3} -->

---
