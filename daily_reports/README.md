# Daily Reports

最近三天日报（最新在前）：

# [20261027](./202610/20261027.md)
## 📌 今日概况

今日共检索候选论文 10 篇；关键词+LLM 智能匹配遥感交叉论文 6 篇；最终纳入日报 6 篇。

今日论文聚焦遥感智能处理的多环节：从卫星条件扩散模型实现无重建新视角合成，到量化自监督SAR-光学编码器的边缘部署；农业遥感方面，地面到卫星知识蒸馏与AlphaEarth嵌入评估共同关注作物分类的时空迁移性；跨模态检索提出交互无关召回与文本引导重排以提升效率；另有BIOMASS辐射稳定性评估。整体呈现模型轻量化、跨域泛化与基础模型表征分析并进的趋势。

## ✨ 今日亮点

- 卫星条件多视角扩散实现无重建新视角合成与场景外推。
- 量化自监督SAR-光学编码器在商用x86硬件上实现边缘推理。
- 地面到卫星知识蒸馏提升作物分类时空偏移下的泛化能力。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261027] GroundControl: Satellite-Conditioned Multi-View Diffusion for Reconstruction-Free Novel View Synthesis | Krishnan Akshay, Turkulainen Matias, Wynn Jamie, Qureshi Zawar, Sayed Mohamed, Garcia-Hernando Guillermo, Vicente Sara, Hays James, Firman Michael, Turmukhambetov Daniyar | Georgia Institute of Technology；Aalto University | 提出卫星条件多视角扩散模型，无需三维重建即可合成新视角并外推场景。 | [#6](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/6) |
| [20261027] Quantized Edge Inference of a Self-Supervised SAR-Optical Encoder on Commodity x86 Hardware | Sanchez-Leon Christian, Chen Dongming | the Software College, Northeastern University, Shenyang, China ( | 对自监督SAR-光学ViT编码器量化，在商用x86硬件上实现边缘推理。 | [#7](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/7) |
| [20261027] Ground-to-Satellite Knowledge Distillation for Crop Classification under Temporal and Geographic Shift | Miranda Miro, Sedona Rocco, Marsocci Valerio, Cavallaro Gabriele, Paris Claudia | Jülich Supercomputing Centre；University of Iceland, Iceland；University of Twente (ITC), the Netherlands | 利用地面数据知识蒸馏训练卫星时序模型，提升作物分类时空迁移性能。 | [#8](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/8) |
| [20261027] Evaluating AlphaEarth Embeddings for Crop Classification: Separability, Temporal Dynamics, and Cross-Regional Transferability | Goyal Priyanka, Sar Maitreyee, Mitra Adway, Sinha Manjira | Department of Artificial Intelligence, Indian Institute of Technology Kharagpur, West Bengal, India；Centre for Atmospheric Sciences, Indian Institute of Technology Delhi, India | 系统评估AlphaEarth嵌入的作物可分性、时序动态与跨区域迁移能力。 | [#9](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/9) |
| [20261027] Efficient Remote Sensing Image-Text Retrieval via Interaction-Free Recall and Text-Guided Reranking | Chen Xi, Chen Xu, Jia Xiamgyang, Wang Wei, Zhang Xu, Shun Zhenyuan | XI CHEN, School of Computer Science, Wuhan University, China；XU CHEN∗, School of Computer Science, Wuhan University, China；XIANGYANG JIA, School of Computer Science, Wuhan University, China；WEI WANG,Beijing Institute for General Artificial Intelligence (BIGAI), China；XU ZHANG, School of Computer Science, Wuhan University, China；ZHENYUAN SUN, School of Computer Science, Wuhan University, China；Institute for General Artificial Intelligence (BIGAI), Beijing, China; Xu Zhang；Science, Wuhan University, Wuhan, China; Zhenyuan Sun；University, Wuhan, China | 提出交互无关召回与文本引导重排，实现高效遥感图像-文本检索。 | [#10](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/10) |
| [20261027] Assessing BIOMASS Radiometric Stability using Permanent Scatterers | Manzoni Marco, Salvaterra Francesco, Claudio Maria Prati, Tebaldini Stefano | 原文作者栏未列出单位 | 利用永久散射体评估BIOMASS P波段SAR辐射稳定性。 | [#11](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/11) |

## 🔎 观察

- 扩散模型与知识蒸馏分别从生成与判别路径缓解遥感标注和视角稀疏问题。
- 边缘量化与高效检索表明遥感AI正从精度优先转向部署效率与实用性平衡。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261027", "source": "api", "checked_at": "2026-10-29T16:59:09+00:00", "source_complete": true, "candidate_count": 10, "paper_count": 6} -->

---

# [20261026](./202610/20261026.md)
## 📌 今日概况

今日共检索候选论文 16 篇；关键词+LLM 智能匹配遥感交叉论文 4 篇；最终纳入日报 4 篇。

今日研究聚焦遥感模型的高效化与跨任务协同。洪水地表水制图评估紧凑基础模型在精度与效率间的平衡；变化检测与图像描述通过选择性跨任务路由实现异构监督下的联合学习；CNN压缩引入蒸馏感知策略以降低部署成本；跨传感器超分辨率则利用视觉自回归建模实现Sentinel-2到1米影像的十倍放大。整体趋势显示，遥感AI正从单一任务精度追求转向多任务协同、模型轻量化与跨模态尺度转换的实用化探索。

## ✨ 今日亮点

- 紧凑基础模型用于洪水地表水制图，兼顾精度与效率。
- 选择性跨任务路由统一变化检测与图像描述，应对异构监督。
- 蒸馏感知压缩与视觉自回归超分分别推进模型轻量化和跨传感器放大。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261026] Accuracy and efficiency of compact foundation models for surface-water mapping during floods | Farajpoor Parastoo, Narimani Mohammadreza | Department of Biological and Agricultural Engineering, University of California, Davis | 评估紧凑基础模型在洪水地表水制图中的精度与效率，基于Sentinel-2和U-Net架构。 | [#1](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/1) |
| [20261026] CoDeRNet: Selective Cross-Task Routing under Heterogeneous Supervision for Change Detection and Captioning | Cho Eunki, Hyeon Bae Kim, Seong Tae Kim | Kyung Hee University, Republic of Korea | 提出CoDeRNet，通过选择性跨任务路由在异构监督下联合进行变化检测与图像描述。 | [#2](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/2) |
| [20261026] DAC-Loop: Distillation-Aware Compression for Remote Sensing CNN | Staedeli Rico, Raichle Lorena, Tzevelekakis Konstantinos, Asefaw Aron, Borth Damian | AIML Lab, School of Computer Science, University of St. Gallen | 提出DAC-Loop，面向遥感CNN的蒸馏感知压缩方法，结合结构化剪枝降低模型复杂度。 | [#3](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/3) |
| [20261026] From Sentinel-2 to 1-m Imagery: Real-World $\times 10$ Cross-Sensor Super-Resolution via Visual Autoregressive Modeling | Chen Tailai, Fu Yuluxin, Deng Jie, Luo Shu, Wu Yanan, Hong Danfeng | College of Information and Electrical Engineering, China Agricultural University, Beijing, China；Institute of Automation, Chinese Academy of Sciences, Beijing, China, and the University of Chinese Academy of Sciences, Beijing, China；the Aerospace Information Research Institute, Chinese Academy of Sciences, Beijing, China, and the University of Chinese Academy of Sciences, Beijing, China；the Beijing Key Laboratory of Precision Forestry, Beijing Forestry University, Beijing, China；School of Automation, Southeast University, Nanjing, China | 利用视觉自回归建模实现Sentinel-2到1米影像的跨传感器十倍超分辨率重建。 | [#4](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/4) |

## 🔎 观察

- 紧凑基础模型与蒸馏感知压缩表明，遥感AI正重视部署效率与精度平衡。
- 跨任务路由和跨传感器超分显示，多任务协同与尺度转换成为提升实用性的关键路径。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261026", "source": "api", "checked_at": "2026-10-28T17:06:11+00:00", "source_complete": true, "candidate_count": 16, "paper_count": 4} -->

---
