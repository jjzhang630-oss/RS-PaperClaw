# Daily Reports

最近三天日报（最新在前）：

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

# [20261104](./202611/20261104.md)
## 📌 今日概况

今日共检索候选论文 16 篇；关键词+LLM 智能匹配遥感交叉论文 7 篇；最终纳入日报 7 篇。

今日研究趋势呈现多模态融合与自监督学习在遥感领域的深化应用。一方面，面向城市管理与规划，细粒度视觉推理基准和生成式土地利用制图受到关注；另一方面，跨模态检索、SAR基础模型及高光谱成分预测等任务持续探索自监督与概率嵌入方法。此外，全色锐化方向出现面向传输与跨传感器实时适应的新框架，强调机载处理与泛化能力。整体上，研究兼顾基础模型构建与下游任务适配，并注重实际部署约束。

## ✨ 今日亮点

- 细粒度视觉推理基准聚焦城市管理，推动多模态大模型在无人机影像上的评估。
- SAR基础模型结合全局与局部语义一致性，提升自监督表征质量。
- 全色锐化研究转向传输导向与跨传感器实时适应，关注机载部署。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261104] Benchmarking Fine-Grained Visual Reasoning for Remote Sensing in Urban Management | Zhang Jiawei, Cai Rizhao, Guan Dayan | School of Electronics and Information Engineering, Harbin Institute of Technology | 构建面向城市管理的遥感细粒度视觉推理基准，基于无人机影像评估多模态大模型。 | [#57](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/57) |
| [20261104] CAPE-JEPA - Cross-modal Adversarial Probabilistic Embedding JEPA | Junghare Aniket, Banerjee Biplab | Biplab Banerjee；Indian Institute of T echnology Bombay | 提出跨模态对抗概率嵌入JEPA，用于遥感跨模态检索，结合概率嵌入与对抗正则化。 | [#58](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/58) |
| [20261104] TOP: Transmission-Oriented Remote Sensing Pansharpening | Cao Zi-Han, Liang Jing-Ze, Wu Shao-Jie, Di Jin-Cheng, Deng Liang-Jian, Vivone Gemine | University of Electronic Science and Technology of China, Chengdu, Sichuan, China (；University of Electronic Science and Technology of China, Chengdu, Sichuan, China；the Multi-Hazard Early Warning Key Laboratory of Sichuan Province, Chengdu, Sichuan, China (；the National Research Council of Italy, Institute of Integrated Methodologies for Earth Observation (CNR-IMIOT), Tito, Italy ( | 提出传输导向的全色锐化方法，面向星上处理优化图像融合的传输效率。 | [#59](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/59) |
| [20261104] XuanJian-DINOSAR: A SAR Foundation Model Based on Global and Local Semantic Consistency | Wu Chunxiao, Huang Huixin, Pan Jialei, Liang Qiang, Wu Tao, Wu Cheng, Huang Long, Li Yuanji, Cheng Qiang, Liu Aifang, Xia Linghao, Zhang Rui | The a uthors are with the Nanjing Institute of Electronic Technology and；National Key Laboratory of Radar Detection and Sensing, Nanjing 210039 | 构建SAR基础模型，基于DINOv2与掩码图像建模，强调全局与局部语义一致性。 | [#60](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/60) |
| [20261104] Many Pixels, One Composition: Self-Supervised Spectra for Specimen-Level Prediction | Tetoula-Tsonga Eleftheria, Arvanitakis George, Giannakas Theodoros | Institute of Communication and Computer Systems | 利用自监督光谱学习进行样本级元素成分预测，基于高光谱成像与注意力回归。 | [#61](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/61) |
| [20261104] Generative AI for urban planning: synthesizing land-use maps with satellite imagery via DualControlNet | Song Qingqi, Chen Yuzhou, Hu Lingqian, Wang Shenhao | Department of Urban and Regional Planning, University of Florida；College of Architecture, Texas A&M University | 利用DualControlNet生成式AI，结合卫星影像合成土地利用图以辅助城市规划。 | [#62](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/62) |
| [20261104] ReTailor: A Residual Feature Tailoring Framework for Real-Time Cross-Sensor Pansharpening Adaptation | Liang Jing-Ze, Xiao Wei-Jie, Cao Zi-Han, Li Yang-Dong, Hu Tian-Yi, Deng Liang-Jian | University of Electronic Science and Technology of China；Multi-Hazard Early Warning Key Laboratory of Sichuan Province | 提出残差特征裁剪框架，实现跨传感器全色锐化的实时自监督适应。 | [#63](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/63) |

## 🔎 观察

- 基础模型与自监督学习正从通用视觉向SAR、高光谱等遥感模态渗透，强调语义一致性。
- 全色锐化研究明显关注部署约束，传输效率与跨传感器实时适应成为新发力点。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261104", "source": "api", "checked_at": "2026-11-06T16:00:53+00:00", "source_complete": true, "candidate_count": 16, "paper_count": 7} -->

---

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
