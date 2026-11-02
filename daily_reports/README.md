# Daily Reports

最近三天日报（最新在前）：

# [20261029](./202610/20261029.md)
## 📌 今日概况

今日共检索候选论文 13 篇；关键词+LLM 智能匹配遥感交叉论文 4 篇；最终纳入日报 4 篇。

今日研究呈现两条主线：一是深度学习与因果推断、神经科学解释方法结合，提升热带气旋快速增强预警的可解释性，并系统剖析地球观测嵌入的表征机制；二是量子启发计算与量子测量设计进入遥感领域，分别用于多模态高分辨率伪标签生成和无人机高光谱小目标检测。整体趋势显示，遥感AI正从单纯精度提升转向物理约束、可解释性与新型计算范式的融合，尤其关注标签稀缺与弱小目标场景。

## ✨ 今日亮点

- 因果先验约束深度学习用于西北太平洋热带气旋快速增强预警，强调可解释性。
- 借鉴计算神经科学解析地球观测嵌入，提升AlphaEarth等模型的可解释性。
- 量子启发卷积网络与量子测量设计分别服务伪标签生成和高光谱小目标检测。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261029] Causal-prior-constrained deep learning for rapid-intensification warning of western North Pacific tropical cyclones | Li Xinrui, Jin Yijun, Dong Yifan, Shu Shoujuan | Department of Atmospheric Sciences, School of Earth Sciences, Zhejiang University, Hangzhou, 310058, China；School of Mathematical Sciences, Zhejiang University, Hangzhou, 310058, China | 提出因果先验约束深度学习方法，用于西北太平洋热带气旋快速增强预警，兼顾预测性能与因果可解释性。 | [#16](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/16) |
| [20261029] NeurEO: dissecting Earth observation embeddings with computational neuroscience | Thijs L van der Plas, Jacob JW Bakermans, Ioannis N Athanasiadis | Wageningen University \& Research, NL；University College London, UK | 借鉴计算神经科学工具剖析地球观测嵌入，评估AlphaEarth等模型在土地覆盖任务中的表征结构。 | [#17](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/17) |
| [20261029] Quantum-Inspired Convolutional Networks for High-Resolution Pseudo-Label Generation from Multimodal Earth Observation Data | Singh Abhishek, Cuozzo Giovanni, Jacob Alexander, Notarnicola Claudia | Institute for Earth Observation, Eurac Research, Bolzano, Italy | 引入量子启发卷积网络，从多模态地球观测数据生成高分辨率伪标签，服务土地覆盖制图。 | [#18](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/18) |
| [20261029] Beyond Direct Imaging: Quantum Measurement Design for Small-Target Detection in UAV Hyperspectral Sensing | Qian Qipeng, Jin Jialiang, Wang Shihao, Qian Yuntao | College of Artificial Intelligence, Zhejiang University, Hangzhou, China；Department of Computer Science, Whiting School of Engineering, Johns Hopkins University, Baltimore, MD, USA (；Department of Mathematics, University of Wisconsin-Madison, Madison, WI, USA (；College of Artificial Intelligence, Zhejiang University, Hangzhou, China ( | 面向无人机高光谱小目标检测，设计量子测量方案替代直接成像，探索空间模式测量新路径。 | [#19](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/19) |

## 🔎 观察

- 因果推断与神经科学解释方法正被引入遥感深度学习，反映领域对模型可信度和物理一致性的需求上升。
- 量子启发与量子测量类工作尚处探索阶段，短期更可能作为标签生成和弱小目标检测的补充手段。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261029", "source": "api", "checked_at": "2026-11-02T03:05:07+00:00", "source_complete": true, "candidate_count": 13, "paper_count": 4} -->

---

# [20261028](./202610/20261028.md)
## 📌 今日概况

今日共检索候选论文 6 篇；关键词+LLM 智能匹配遥感交叉论文 2 篇；最终纳入日报 2 篇。

今日两篇论文分别从统计建模与深度学习两个路径推进遥感数据分析。第一篇针对大湖区高维水陆转换问题，提出贝叶斯差异模型处理多项数据，强调不确定性量化与高维结构建模。第二篇聚焦超高分辨率影像建筑损毁评估，诊断深度模型中的邻域捷径问题，并设计建筑证据插件以提升灾后响应可靠性。整体趋势显示，遥感AI正从单纯精度提升转向模型可解释性、偏差诊断与统计严谨性，尤其关注复杂时空数据与灾害场景下的稳健决策支持。

## ✨ 今日亮点

- 贝叶斯差异模型用于高维多项数据，量化水陆转换不确定性。
- 诊断建筑损毁评估中的邻域捷径，提出证据插件抑制偏差。
- 两研究均强调模型可靠性，而非仅追求精度指标提升。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261028] An Analysis of High-Dimensional Land-Water Transitions in the Great Lakes via a Bayesian Discrepancy Model for Multinomial Data | Lee Seulki, Jonathan R. Bradley | Department of Statistics and Data Science, University of Missouri | 提出贝叶斯差异模型分析大湖区高维水陆转换，处理多项数据并量化不确定性。 | [#13](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/13) |
| [20261028] Neighbourhood shortcuts in building damage assessment from very-high-resolution satellite imagery: diagnosis and a building-evidence plug-in | Guo JianChong, Wan YuTing, Li Kefan, Ma AiLong, Zhong YanFei | State Key Laboratory of Information Engineering in Surveying, Mapping, and Remote Sensing；Wuhan University, 430079, China | 诊断超高分辨率影像建筑损毁评估中的邻域捷径，设计建筑证据插件提升可靠性。 | [#14](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/14) |

## 🔎 观察

- 遥感AI研究正从精度导向转向偏差诊断与不确定性量化，强调模型可信度。
- 灾害评估场景中，深度模型易受邻域捷径影响，需引入结构化证据约束。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261028", "source": "api", "checked_at": "2026-11-02T03:02:32+00:00", "source_complete": true, "candidate_count": 6, "paper_count": 2} -->

---

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
