# Daily Reports

最近三天日报（最新在前）：

# [20261103](./202611/20261103.md)
## 📌 今日概况

今日共检索候选论文 12 篇；关键词+LLM 智能匹配遥感交叉论文 9 篇；最终纳入日报 9 篇。

今日研究呈现多模态融合与基础模型驱动的趋势。遥感视觉任务从监督分割转向免训练、零样本范式，如光伏模块制图与热带作物分割基准。水文与灾害领域强调嵌入表示与多智能体推理，结合地球观测嵌入、流域自监督学习及LLM调度。在线高精地图构建探索卫星先验与相机融合的鲁棒性。整体上，研究更注重可扩展性、跨域泛化与物理约束嵌入。

## ✨ 今日亮点

- 免训练视觉基础模型用于多视角无人机光伏制图，实现零样本高保真映射。
- 流域自监督嵌入Basin2Vec支持可扩展水文建模与径流预测。
- LLM辅助自适应启发式搜索优化敏捷地球观测卫星调度。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261103] PLANTEUR: A Crop-Type Segmentation Benchmark for Tropical Regions | Wolters Piper, Tseng Gabriel, Bastani Favyen, Redmon Joseph, Zhang Yawen, Sablon Hadrien, Shah Ando | Allen Institute for AI | 构建热带地区作物类型分割基准，融合Sentinel-1/2多源卫星影像评估模型泛化性。 | [#47](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/47) |
| [20261103] Fusing Earth observation embeddings and spaceborne terrain with meteorological forcing for flood peak depth prediction from high-water marks | Zhou Wen, Wang Shaowen, Lall Upmanu, Merwade Venkatesh, Ye Dingqi | Department of Geography and Geographic Information Science；CyberGIS Center for Advanced Digital and Spatial Studies, and；Siebel School of Computing and Data Science；University of Illinois Urbana--Champaign, Urbana, IL, USA；School of Complex Adaptive Systems, College of Global Futures；Arizona State University, Tempe, AZ, USA；Lyles School of Civil and Construction Engineering；Purdue University, West Lafayette, IN, USA | 融合地球观测嵌入、星载地形与气象强迫，从高水位标记预测洪水峰值深度。 | [#48](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/48) |
| [20261103] Basin2Vec: Learning Basin-Centric Embeddings for Scalable Hydrological Modeling | Talha Muhammad, Liu Xiaofeng, Yang Yuan, Tan Pang-Ning, A. Pouyan Nejadhashemi | Michigan State University；University of Michigan；University of California, San Diego | 提出Basin2Vec自监督学习流域中心嵌入，支撑可扩展水文建模与径流预测。 | [#49](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/49) |
| [20261103] High-fidelity training-free photovoltaic module mapping from multi-view UAV imagery | Duana WenHao, Chena Qi, Zhang Penglei, Deng Ruizhe, Guo Zhiling, Zhang Haoran, Chen Yuntian | aSchool of Geography and Information Engineering, China University of Geosciences；bNingbo Institute of Digital Twin, Eastern Institute of；cZhejiang Key Laboratory of Industrial Intelligence and Digital Twin, Eastern Institute of；dDepartment of Building Environment and Energy Engineering, The Hong Kong；Polytechnic University, Kowloon, Hong Kong, China；eSchool of Urban Planning and Design, Peking University, Shenzhen, 518055, China | 基于多视角无人机影像与视觉基础模型，免训练实现高保真光伏模块零样本制图。 | [#50](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/50) |
| [20261103] GeoFaham: Domain-Specialized Multi-Agent Geospatial Analytics for Disaster Response | Muhammad Sohail Danish, Gilles Q. Hacheme, Zaytar Akram, Satej S. Soman, Becker-Reshef Inbal, Juan Lavista Ferres, Khan Salman, Girmaw Abebe Tadesse | AI for Good Lab；Microsoft AI for Good Lab；Mohamed bin Zayed University of Artificial Intelligence | 面向灾害响应构建领域专用多智能体地理空间分析框架，集成LLM与空间数据工作流。 | [#51](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/51) |
| [20261103] Using GeoAI and machine learning tools for consistent high-resolution land cover mapping based on time-series NAIP imagery | Liu Jie, Tang Xusheng, Wang Chao, Yan Zhengxiao, Dai Yuchen, Zhang Qi, Song Conghe | Department of Geography and Environment, University；Department of City and Regional Planning, University；Department of Geography, Hong Kong Baptist University；Department of Earth, Marine and Environmental Sciences；University of North Carolina at Chapel Hill, Chapel Hill | 利用GeoAI与机器学习工具，基于时序NAIP影像实现一致的高分辨率土地覆盖制图。 | [#52](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/52) |
| [20261103] Large Language Model-Assisted Adaptive Heuristic Search for Agile Earth Observation Satellite Scheduling | Wang He, Liu Yeye, Li Ruijie, Jiang Xuemei, Wu Junyu, Lining Liu Zhuoqi Man, Li Tao, Song Yanjie | College of Intelligent Science and Engineering, Harbin Engineering University, Harbin, China (；School of Electrical and Control Engineering, North University of China, Taiyuan, China (；School of Unmanned Aerial Vehicle Industry, Chengdu Aeronautic Polytechnic University, Chengdu, China (xue-；State Key Laboratory-Robot Research Institute, HIT, Harbin, Heilongjiang,, China (；School of Information Science and Tech- nology, Dalian Maritime University, Dalian, China ( | 采用大语言模型辅助自适应启发式搜索，求解敏捷地球观测卫星调度问题。 | [#53](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/53) |
| [20261103] ReSMap: Recasting Satellite Priors for Robust and Accurate Online HD Map Construction | Kim Kyungmin, Lee Sumin, Jeong Sungoh, Lim DoHyun, Park Seonghyun, Hwang Soonmin | Department of Automotive Engineering (Automotive-Computer Convergence)；Department of Computer Science；Department of Electrical Engineering；Department of Automotive Engineering；Hanyang University, Seoul, South Korea | 重铸卫星先验用于鲁棒准确的在线高精地图构建，融合相机与卫星数据提升感知冗余。 | [#54](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/54) |
| [20261103] OSGR: Observation-Support Graph Reasoning for Earth Observation Question Answering | Yu Dazhou, Wang Zerong, Bao Riyang, Li Longxiang, Liu Yang, Zhao Liang | Emory University；Georgia State University | 提出观测支持图推理框架，结合关系条件定位与时空约束回答地球观测问题。 | [#55](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/55) |

## 🔎 观察

- 免训练与零样本范式在遥感视觉任务中兴起，降低对标注数据依赖并提升跨域部署灵活性。
- 水文与灾害研究正从纯物理模型转向嵌入表示与LLM智能体，强调可扩展推理与多源约束融合。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261103", "source": "api", "checked_at": "2026-11-04T16:04:49+00:00", "source_complete": true, "candidate_count": 12, "paper_count": 9} -->

---

# [20261102](./202611/20261102.md)
## 📌 今日概况

今日共检索候选论文 14 篇；关键词+LLM 智能匹配遥感交叉论文 9 篇；最终纳入日报 9 篇。

今日论文聚焦遥感领域多类学习范式与任务适配。域泛化、类增量学习与测试时训练被用于提升跨域与动态场景下的分割和分类鲁棒性；视觉语言模型与决策模型结合，推动对地观测从感知走向可解释决策；多源融合与低层融合-高层语义衔接成为分类与理解的关键路径；扩散模型和水下图像复原拓展了无人机浅水测绘能力；超分辨率在作物表型中的保真度评估受到关注。整体呈现从单一任务模型向跨域、跨模态、跨层级协同与决策化演进的趋势。

## ✨ 今日亮点

- 域泛化与类增量学习并行推进，提升遥感模型跨域与动态场景适应性。
- 视觉语言模型与决策模型结合，推动对地观测从感知走向可解释决策。
- 多源融合与低层-高层语义衔接成为遥感分类与理解的关键路径。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261102] ASCoR: Asymmetric Semantic-Spatial Learning for Remote Sensing Domain Generalization | Wang Zitong, Lyu Shuchang, Li Meng, Wang Qiang, Cheng Guangliang, Shi Zhenwei | Beihang University；University of Science and Technology Beijing；University of Liverpool；Guangdong Electronic Information Engineering Research Institute, University of Electronic Science and Technology of China | 提出非对称语义-空间学习框架，面向遥感域泛化分割，兼顾语义与空间特征对齐。 | [#37](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/37) |
| [20261102] EO-Jev: Decision Model for Earth Observation | Mohamed Atef Abouelhadid, Diaa Addeen Abuhani, Muhammad Akhtar Munir, Fahad Shahbaz Khan, Khan Salman | Mohamed Bin Zayed University of Artificial Intelligence；Massachusetts Institute of Technology；Australian National University；Linköping University Sweden | 构建对地观测决策模型，结合视觉语言模型与低秩微调，强调校准与决策可靠性。 | [#38](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/38) |
| [20261102] HyperFlow: Class-Incremental Semantic Change Detection via Hyperbolic Flow | Béchaz Manon, Buecher Léo, Dalsasso Emanuele, Tomoiaga Ciprian, Jayet Patrick, Detyniecki Marcin, Chapel Laetitia, Drumetz Lucas, Courty Nicolas, Tuia Devis | EPFL, Switzerland; 2 Universit´e de Bretagne Sud, France; 3 IRISA, France 4 INRIA, France；AXA GDAI Research, Switzerland; 6 Institut Agro Rennes-Angers, France 7 Lab-STICC | 利用双曲空间流建模类增量语义变化检测，关注地类转移的层次结构。 | [#39](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/39) |
| [20261102] KAUSTics-Net: Diffusion-Based Through-Water UAV Restoration with a Semi-Synthetic Dataset | Scilla Dario, Omar A. Lopez, Johansen Kasper, Brian O. Nieuwenhuis, Matthew F. McCabe | and Livability Initiative, King Abdullah University of Science and Technology；Red Sea Research Center, Biological and Environmental Science and；Engineering Division, King Abdullah University of Science and Technology | 基于扩散模型与半合成数据集，实现无人机穿水影像复原以支持浅水测绘。 | [#40](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/40) |
| [20261102] Cross-Layer Refinement and Frequency-aware Fusion Network for Multi-Source Remote Sensing Image Classification | Xiao Wenhan, Gong Chuanzheng, Gao Feng, Dong Junyu, Du Qian | State Key Laboratory of Physical Oceanography, Ocean University of China, Qingdao, China；Department of Electrical and Computer Engineering, Mississippi State University, Starkville, MS USA. and elevation information [4] | 设计跨层细化与频率感知融合网络，用于多源遥感图像分类。 | [#41](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/41) |
| [20261102] Shared-Pattern Collaborative Network for Multi-Source Remote Sensing Data Classification | Yang Chenfang, Gong Chuanzheng, Gao Feng, Dong Junyu, Du Qian | State Key Laboratory of Physical Oceanography, Ocean University of China, Qingdao, China. (；Department of Electrical and Computer Engineering, Mississippi State University, Starkville, MS USA | 提出共享模式协同网络，通过跨模态学习与特征融合实现多源遥感分类。 | [#42](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/42) |
| [20261102] Bridging Low-Level Image Fusion and High-Level Semantic Understanding | Dong Guangyuan, Shen Lingdong, Zhang Xudong, Jing Haodong, Wang Haoyu, Li Zihao, Ying Zonghao, Song Ziyu, Liu Shenghao, Luo Jiachen, Zhang Hao | Peking University；Xi'an Jiaotong University；Nankai University；Institute of Automation, Chinese Academy of Sciences | 衔接低层图像融合与高层语义理解，借助视觉语言模型与对比学习增强融合语义性。 | [#43](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/43) |
| [20261102] Performance evaluation of super-resolution techniques for characterization and phenotyping of commodity crops using multispectral imagery | Karukayil Abhiram, João F. C. Mota, Vásquez-Guevara Mateo, Arevalo-Ramirez Tito, Fernando Auat Cheein | School of Engineering and Physical Sciences, Heriot-Watt University, Edinburgh, UK；Department of Electrical Engineering, Department of Mechanical Engineering and Metallurgy, School of Engineering, Faculty of；School of Mathematical and Computer Sciences, Heriot-Watt University, Edinburgh, UK；Harper Adams University, England, UK | 评估多光谱超分辨率对作物表征与表型的影响，关注光谱保真度。 | [#44](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/44) |
| [20261102] Spectral-spatial vision test-time training for hyperspectral image classification | Zhao Xiang | College of Mathematical Sciences, Harbin Engineering University | 将视觉测试时训练引入高光谱分类，以自监督与谱空表征提升泛化能力。 | [#45](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/45) |

## 🔎 观察

- 域泛化、类增量与测试时训练集中出现，反映遥感模型正从静态封闭场景转向动态开放环境。
- 多源融合论文强调跨层与跨模态协同，表明单一模态或单层特征已难满足复杂分类需求。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261102", "source": "api", "checked_at": "2026-11-03T16:12:45+00:00", "source_complete": true, "candidate_count": 14, "paper_count": 9} -->

---

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
