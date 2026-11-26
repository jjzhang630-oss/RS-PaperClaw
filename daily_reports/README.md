# Daily Reports

最近三天日报（最新在前）：

# [20261123](./202611/20261123.md)
## 📌 今日概况

今日共检索候选论文 20 篇；关键词+LLM 智能匹配遥感交叉论文 1 篇；最终纳入日报 1 篇。

今日候选论文聚焦高光谱图像分类的模型轻量化与可靠性提升。KGLP-Net将卡尔曼滤波引入全局-局部学习框架，用于不确定性感知融合，并结合Group Fisher剪枝降低模型冗余。该工作体现了遥感AI领域对分类精度、计算效率与预测可靠性三者协同优化的关注，也反映出剪枝与滤波理论在遥感任务中的交叉应用趋势。

## ✨ 今日亮点

- 提出KGLP-Net，融合卡尔曼可靠全局-局部学习与Group Fisher剪枝。
- 面向高光谱图像分类，兼顾不确定性感知融合与模型压缩。
- 由西安邮电大学与英国斯塔福德郡大学合作完成。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261123] KGLP-Net: Kalman-Reliable Global--Local Learning With Group Fisher Pruning for Hyperspectral Image Classification | Deng Wenshuai, Xie Wen, Abdel Hamid Soliman, Zhao Qianzheng | School of Communications and Information Engineering, Xi'an University of Posts and Telecommunications, Xi'an, China (；School of Digital, Technology, Innovation, and Business, University of Staffordshire, Stoke-on-Trent ST4 2 DE, U.K. ( | 提出KGLP-Net，用卡尔曼滤波实现可靠全局-局部融合，并以Group Fisher剪枝压缩高光谱分类模型。 | [#100](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/100) |

## 🔎 观察

- 卡尔曼滤波被用于融合可靠性建模，说明不确定性感知正从后处理走向网络内嵌设计。
- Group Fisher剪枝与全局-局部学习结合，反映遥感模型在精度与效率间寻求结构化平衡。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261123", "source": "api", "checked_at": "2026-11-24T15:58:37+00:00", "source_complete": true, "candidate_count": 20, "paper_count": 1} -->

---

# [20261121](./202611/20261121.md)
## 📌 今日概况

今日共检索候选论文 7 篇；关键词+LLM 智能匹配遥感交叉论文 1 篇；最终纳入日报 1 篇。

今日候选论文聚焦无人机RGB-T微小行人检测中的模态质量失衡与空间错位问题，提出模态质量引导的协同优化框架，属于多模态融合与遥感目标检测交叉方向。研究强调根据模态质量动态调整融合策略，而非简单拼接，反映出多模态遥感检测正从固定融合向质量感知自适应融合演进。

## ✨ 今日亮点

- 针对无人机RGB-T微小行人检测，关注模态质量失衡与空间错位双重挑战。
- 提出模态质量引导的协同优化框架，实现质量感知的自适应多模态融合。
- 面向遥感微小目标场景，强调融合策略需随模态可靠性动态调整。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261121] MQCODet: Modality Quality-Guided Collaborative Optimization for UAV-Based RGB-T Tiny Pedestrian Detection | Li Hui, Ma Jianbo, Luo Hui, Qi Guanglin, Wang Zhixing, Zuo Haorui, Zhang Jianlin | aState Key Laboratory of Optical Field Manipulation Science and Technology, Institute of；Optics and Electronics, Chinese Academy of Sciences, Chengdu 610209, China；bSchool of Electronic, Electrical and Communication Engineering, University of Chinese；Academy of Sciences, Beijing 100049, China | 提出MQCODet，以模态质量引导协同优化，应对无人机RGB-T微小行人检测中的质量失衡与空间错位。 | [#102](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/102) |

## 🔎 观察

- 多模态遥感检测正从静态融合转向质量感知的动态协同，模态可靠性评估成为融合设计的关键前置环节。
- 无人机RGB-T微小目标检测需同时处理模态质量差异与空间对齐误差，单一融合策略难以兼顾两类退化。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261121", "source": "api", "checked_at": "2026-11-26T02:22:18+00:00", "source_complete": true, "candidate_count": 7, "paper_count": 1} -->

---

# [20261120](./202611/20261120.md)
## 📌 今日概况

今日共检索候选论文 17 篇；关键词+LLM 智能匹配遥感交叉论文 1 篇；最终纳入日报 1 篇。

今日仅一篇论文，聚焦无人机实时高光谱异常检测，面向荒野搜救场景。研究将高光谱成像与机载边缘计算结合，强调在无人机端直接处理数据以降低延迟，摆脱对地面站回传的依赖。该工作体现了遥感AI向实时化、边缘化发展的趋势，尤其关注应急响应中的低延迟需求。由于样本单一，尚难判断整体领域动向，但可视为高光谱异常检测从离线分析向在线部署转型的一个具体案例。

## ✨ 今日亮点

- 面向荒野搜救的无人机实时高光谱异常检测系统
- 强调机载边缘计算，减少对地面站回传的依赖
- 将高光谱异常检测从离线分析推向在线部署

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261120] Real-Time On-Drone Hyperspectral Anomaly Detection for Wilderness Search and Rescue | Liu Jacqueline, Kyere Gyabaah, Liu Chengyan, Chiu Kenneth, Marie Lynn, Church, Gleason Sean, Boubin Jayson | School of Computing, Binghamton University, Binghamton, NY USA ( | 提出无人机端实时高光谱异常检测方法，用于荒野搜救中快速发现异常目标，依托机载计算实现低延迟处理。 | [#98](https://github.com/jjzhang630-oss/RS-PaperClaw/issues/98) |

## 🔎 观察

- 该研究将高光谱异常检测与无人机边缘计算结合，反映遥感AI从离线处理向实时机载部署的转型趋势。
- 单一搜救场景论文难以代表整体动向，但凸显应急响应中对低延迟、轻量化算法的迫切需求。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261120", "source": "api", "checked_at": "2026-11-24T15:56:49+00:00", "source_complete": true, "candidate_count": 17, "paper_count": 1} -->

---
