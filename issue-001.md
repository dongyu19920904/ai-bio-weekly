# AI+生命科学周报（第 1 期）：AI正在改写生命科学的剧本

记录每周值得分享的AI+生命科学前沿内容，周五发布。

本周刊[开源](https://github.com/dongyu19920904/ai-bio-weekly)，欢迎[投稿](https://github.com/dongyu19920904/ai-bio-weekly/issues)。

## 封面图

<img src="https://www.nikonsmallworld.com/images/photos/2025/_photo1600/1st-JAN-2025_ZHANG_YOU_e41144_f24896.jpg" width="700" alt="Cancer immunotherapy immune cells attacking tumor">


一只米象甲在米粒上的完美翅展。来自中国昆明的昆虫学家张友用这张照片赢得了2025年尼康显微摄影大赛第一名，他用100多张照片进行焦点叠加，花费两周时间完成。（[via Nikon Small World](https://www.nikonsmallworld.com/galleries/2025-photomicrography-competition/rice-weevil-sitophilus-oryzae-on-a-grain-of-rice)）

## 本期主题：AI终于"看穿"了癌症的隐身衣

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/ad306125-f0ff-422a-8859-3d967de23709.png" width="400" alt="Cancer immunotherapy immune cells attacking tumor">

### 【第一幕】问题：60%的癌症患者被医学"遗忘"了

医学界有个名字叫 **"冷肿瘤"** 的怪物。

在全世界，有**60%的癌症患者**接受了最先进的免疫疗法，但它们对这些患者**无效**。医生的话是："我们看不见。"

这不是医学的失败，而是**生物学的复杂性**。癌细胞学会了一门"隐身术"——它们不再向免疫系统暴露自己的"身份信息"。医学术语称之为**抗原呈递障碍**（Antigen Presentation Deficit）。

想象一下：免疫细胞是警察，而癌细胞是通缉犯。但"冷肿瘤"中的癌细胞学会了伪装，免疫警察看不到它们，自然也就无法追捕。

多年来，科学家一直在摸索如何让这些"隐形"的肿瘤变成 **"热肿瘤"** ——即免疫活跃、容易被识别的肿瘤。但这一直是一个**盲目的试错过程**。

**关键数字**：从发现新靶点到临床试验需要5-10年，成本数十亿美元。时间就是生命，但患者等不起。

---

### 【第二幕】转折：AI用"细胞语言"找到了答案

**2025年10月15日**，一个突破性的发现在Google DeepMind和耶鲁大学的联合研究中诞生。

他们开发的AI模型**Cell2Sentence-Scale 27B**（C2S-Scale）——一个拥有270亿参数的**生物语言基础模型**——完成了一件人类科学家多年未能做到的事：

**它不仅预测了一个新的癌症免疫疗法方案，而且这个预测已经被实验室验证**。

这个模型的创新在于它的**思维方式**。研究团队给它一个非常具体的任务：

> 找一种药物，能够在**特定条件下**增强癌细胞的抗原呈递。

具体来说，这种药物应该：
- 仅在存在**低浓度干扰素信号**的环境中激活
- 在其他条件下保持"沉默"
- 这种**条件依赖性**正是许多小型AI模型无法理解的关键

C2S-Scale分析了超过**4000种药物候选**，在真实患者肿瘤样本和细胞系数据中进行了"虚拟筛选"。结果惊人：

模型鉴定出了**CK2激酶抑制剂西米他塞特**作为候选药物。

**更关键的是，这个发现是完全新颖的**。虽然CK2在免疫调节中有所涉及，但没有文献报道过西米他塞特能够促进抗原呈递。

**AI生成的不是已知知识的复述，而是科学界从未提出过的新假设**。

---

### 【第三幕】验证：从硅基预测到生物现实

预测只有在实验室得到验证才有价值。

耶鲁的研究人员用**未在模型训练中出现过的人类神经内分泌细胞**进行了验证实验。结果令人震撼：

| 处理方案 | 抗原呈递增加 |
|---------|----------|
| 西米他塞特单独使用 | 0%（无效） |
| 低剂量干扰素单独使用 | 低效 |
| **两者结合** | **≈50% 的显著增加** |

这**50%的增幅**意味着什么？

它意味着原本"隐形"的肿瘤突然向免疫系统暴露了**一半的身份信息**——足以让免疫系统发动有效的攻击。

换句话说，**AI的预测被完全证实了**。

---

### 【启示】我们正在目睹什么？

这个突破不只是一个药物发现案例，它揭示了一个更深层的真相：

**随着AI模型的规模增长，它获得的不仅是更强的计算能力，而是涌现出了全新的"思维方式"**——能够理解生物学中的上下文依赖性和条件推理，这正是传统小型模型无法做到的。

如果这个趋势持续，我们可能正在进入一个**生物学发现被AI显著加速的时代**。但前提是：我们能够确保这些AI系统的预测真正被**实验验证**，而不是被盲目相信。

**最后的启示**：  
未来最具威力的不是"**AI替代科学家**"，而是"**AI赋能科学家**"——让人类的直觉和创意，与AI的计算能力完美融合。

这个故事才刚刚开始。

([via Google Blog](https://blog.google/technology/ai/google-gemma-ai-cancer-therapy-discovery/) | [Yale News](https://medicine.yale.edu/news-article/bridging-biology-and-ai-yale-and-googles-collaborative-breakthrough-in-single-cell-analysis/))

---

## 科研动态 · 本周5条快讯

### 1️⃣ 【AI突破】一天内筛选10亿分子：Kantify创造药物发现新纪录

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/f676c412-5a97-42cc-b3cb-6758f42196c4.png" width="400" alt="AI high-throughput drug molecule screening">

比利时生物科技公司Kantify在10月22日宣布了一个里程碑式的突破。其AI平台**Sapian**现已可在**不到24小时内分析10亿个药物分子**。

这意味着什么？**传统的高通量筛选需要270年才能完成同样的工作**。

更令人印象深刻的是，Sapian已经在人类难治性疾病**脂肪肉瘤**（一种罕见癌症）的研究中取得科学验证——发现的新分子展示出优异的体内生物活性。

**⚡ 关键洞察**：AI正在将一个耗时数年的过程压缩成数小时。

([via BioSpace](https://www.biospace.com/press-releases/kantify-reaches-new-milestone-in-ai-driven-drug-discovery-10-billion-molecules-analyzed-per-day-and-a-major-advance-in-a-rare-cancer))

---

### 2️⃣ 【临床挫折】Moderna CMV疫苗Phase 3失败：mRNA技术的第一次重挫

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/2e9a9b70-85e1-4544-bde7-47d13a7e4c0f.png" width="400" alt="mRNA vaccine vial and syringe">

曾被寄予厚望的Moderna细胞巨病毒（CMV）mRNA疫苗在10月21日传来坏消息。

在涉及**7454名育龄女性**的大规模Phase III试验中，**mRNA-1647的有效性仅为6-23%**，远低于预期的防护水平。

虽然该疫苗的**安全性良好**（不良事件多为轻度至中度），但零星的保护效果迫使Moderna放弃这一计划。

**💡 启示**：即使在mRNA技术已被广泛应用的今天，将其从新冠转向其他传染病仍然充满挑战。

([via Clinical Trials Arena](https://www.clinicaltrialsarena.com/news/moderna-scraps-mrna-vaccine-in-congenital-cmv-on-phase-iii-failure/))

---

### 3️⃣ 【平台发布】Genomics推出Mystra：遗传学AI平台重新定义药物靶点

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/48ea4923-682c-4a97-9316-60fec88b8bd0.png" width="400" alt="Genome-wide association study visualization">

在10月15日美国人类遗传学学会（ASHG）2025年年会上，英国科技生物公司Genomics发布了新平台**Mystra**。

这是全球首个"**AI赋能人类遗传学平台**"。其背后的数据库堪称奢华：整合了超过**20,000项全基因组关联研究**和**万亿行数据**。

核心洞察是：有**人类遗传学证据支持的药物靶点临床试验成功率高2.6倍**。

在一个临床试验失败率接近90%的行业里，这个数字足以改变游戏规则。

([via GEN News](https://www.genengnews.com/topics/omics/ai-human-genetics-platform-mystra-debuts-for-drug-discovery-validation/))

---

### 4️⃣ 【意外发现】COVID疫苗能"热化"冷肿瘤：mRNA疫苗的跨界应用

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/6df50210-f6ea-43ae-87ea-58a3ec7be64f.png" width="400" alt="COVID vaccine enhancing cancer immunotherapy">

一个发表在《Nature》的研究在10月22-23日引起学术界关注。

研究显示，在接种COVID-19 mRNA疫苗后100天内开始接受**免疫检查点抑制剂**（ICI，一类癌症免疫疗法）的患者，生存率显著提高。

**具体数据**：
- 非小细胞肺癌患者的3年总体生存率从30.8%提升到**55.7%**（**风险降低49%**）
- 黑色素瘤患者从44.1%提升到**67.6%**

原理是什么？COVID疫苗触发了**大规模的I型干扰素风暴**（24小时内上升280倍），激活了免疫系统。

**🌟 意义**：现成的、便宜的COVID疫苗可能成为"冷肿瘤"转化为"热肿瘤"的一个实用工具。

([via News Medical](https://www.news-medical.net/news/20251023/How-COVID-mRNA-vaccines-may-make-cancer-treatments-more-effective.aspx))

---

### 5️⃣ 【临床进展】AI设计的肺纤维化药物Rentosertib进入Phase IIa并显示疗效

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/95302b14-681a-4794-b156-7ba7c18221c2.png" width="400" alt="Pulmonary fibrosis AI drug treatment">

由Insilico Medicine的生成式AI完全设计的药物**Rentosertib**正在临床中获得成功。

在涉及71名患者的Phase IIa试验中，该药展示了**安全性良好**且对关键指标的改善——**肺活量（FVC）增加98.4 mL**（对比安慰剂下降20.3 mL）。

这是**第一个完全由AI生成和设计、已进入临床阶段并表现出疗效的小分子药物**。

从发现到临床平均需要10-15年和20亿美元的传统流程，正被AI大幅加速。

([via Insilico Medicine](https://insilico.com/tpost/tnrecuxsc1-insilico-announces-nature-medicine-publi))

---

## 深度阅读 · 精选6篇长文

### 📊 本周核心主题

这周的深度阅读集中在一个主题：**不是AI替代科学家，而是AI如何赋能科学家**

✅ **技术解析**（第1、2、3篇）- 理解AI在蛋白设计、单细胞分析、基础模型中的原理  
✅ **实战应用**（第4、6篇）- 看deepmirror和生物制药如何真正应用AI  
✅ **战略思维**（第5篇）- 思考AI在科学发现中的长期角色定位

---

### 推荐指南：按你的阅读需求选择

**【如果你想理解AI如何改变蛋白质设计】**

📖 **[蛋白质设计的艺术：AI如何改变药物开发](https://www.worksinprogress.news/p/the-art-of-protein-design-with-ai)**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/e62cad4a-a635-4ce4-92d8-6053ee800832.png" width="400" alt="AI protein design visualization">

✨ **为什么推荐**：深入探讨AI不再局限于模仿自然，而是设计自然从未存在过的新蛋白。从Chroma模型能够"凭空"设计出310个功能性蛋白说起，揭示了生成式AI如何拓展人类设计空间的可能性。

⏱️ **阅读时间**：18分钟  
🎯 **收获**：理解为什么AI在分子设计中堪称"创意伙伴"

---

**【如果你想看AI如何理解单细胞的秘密】**

📖 **[基础模型揭秘：单细胞内的隐藏世界](https://ryanfukushima.substack.com/p/a-foundation-model-reveals-what-cells) | Ryan Fukushima**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/3b444c26-e9b2-45a4-b980-281839d29f0e.png" width="400" alt="Single cell hidden patterns visualization">

✨ **为什么推荐**：从富有诗意的角度切入"单细胞如何从沉默中被唤醒"。用116万个单细胞数据训练的基础模型，揭示了细胞间的隐藏对话。这不是一篇纯技术文，而是探讨"如何用AI解读生命最小单位的秘密"的深度思考。

⏱️ **阅读时间**：15分钟  
🎯 **收获**：如何用AI解读生命最小单位的秘密

---

**【如果你对"为什么生物AI在2024年突破"感到困惑】**

📖 **[生物基础模型直观解读](https://aistartupscout.substack.com/p/biology-foundation-models-explained) | AI创业侦查**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/88b76d8a-7d04-4528-a396-9e79ce3304c6.png" width="400" alt="Biology foundation model architecture">

✨ **为什么推荐**：用类比而非公式来讲解——为什么2024年是生物AI的突破年？为什么通用LLM在生物学上失效？这篇文章用4000字把复杂的技术难题讲成了一个清晰的故事。

⏱️ **阅读时间**：20分钟  
🎯 **收获**：彻底理解生物AI的核心价值

---

**【如果你想看AI药物发现如何从论文走向工程实践】**

📖 **[深度镜像：规模化生成式药物设计](https://kiinai.substack.com/p/deepmirror-generative-drug-design) | KIIN AI**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/c3ce11f3-b326-46fd-b79b-071133dcfbe9.png" width="400" alt="Generative AI molecular design workflow">

✨ **为什么推荐**：从实战的角度展示了如何用生成式AI加速药物分子设计。与其他理论性的文章不同，deepmirror演示的是科学家们如何上传自己的数据集、让AI并行运行数百个模型、找到最适合的方案。这是"从论文到工程实践"的完整案例。

⏱️ **阅读时间**：16分钟  
🎯 **收获**：AI药物发现如何真正运作

---

**【如果你想像"架构师"一样思考生物AI的未来】**

📖 **[打造生物AI的大脑](https://ncfrey.substack.com/p/building-the-brain-of-a-biological) | Nicholas Frey**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/34d3fa74-92a0-4434-a8ee-e42be605df4d.png" width="400" alt="Biological AI system architecture design">

✨ **为什么推荐**：偏向"架构师视角"的深度文章。不问"AI能做什么"，而是问"如何设计一个生物学AI系统的大脑"。涉及数据编码、模型架构、训练策略等深层设计问题。文末金句：*"未来科学发现的主角是装备了AI的人类科学家"*

⏱️ **阅读时间**：22分钟  
🎯 **收获**：理解AI在科学发现中的长期角色定位

---

**【如果你想了解生物制药领域如何被AI革新】**

📖 **[AI赋能的药物发现革命：从生物制药的视角](https://bioscommunity.substack.com/p/frontier-perspectives-1-ai-enabled) | BIOS+**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/014aef46-be65-4b67-9867-8d3a45a99f60.png" width="400" alt="Biologics pharmaceutical protein drug">

✨ **为什么推荐**：深度分析特别关注生物制药（Biologics）与AI结合的前景。与小分子药物不同，生物制药具有更高特异性但筛选难度更大——AI在这个领域如何发挥作用？文章通过具体数据和案例说明，为什么生物制药领域最容易被AI革新。

⏱️ **阅读时间**：19分钟  
🎯 **收获**：理解AI应用差异化的本质

---

## 研究工具 · 你的"科研武器库"

### 🔬 单细胞分析

**1. [Scanpy](https://scanpy.readthedocs.io)** — Python中的"瑞士军刀"

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/35cc2081-c532-412b-a7a1-e6ef0aa48110.png" width="400" alt="Scanpy UMAP clustering visualization example">

💡 **什么时候用**：拿到单细胞测序数据，需要快速聚类和可视化  
⚙️ **怎么上手**：安装后10分钟内能跑出第一张图  
📊 **谁在用**：全球数千个发表论文的实验室  
💰 **费用**：完全免费

---

**2. [scvi-tools](https://github.com/scverse/scvi-tools)** — 深度学习工具

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/9f2448cb-290e-4706-af3e-d68c14b57508.png" width="400" alt="scvi-tools deep learning single-cell analysis">

💡 **什么时候用**：需要深度学习处理复杂的单细胞数据  
⚙️ **怎么上手**：官方教程详细，有现成的示例  
📊 **谁在用**：深度学习导向的研究小组  
💰 **费用**：完全免费

---

**3. [scverse 生态](https://scverse.org)** — 完整的生态系统

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/3b93bc35-85d1-4626-8b20-68e6e03a8921.png" width="400" alt="scverse integrated ecosystem visualization">

💡 **什么时候用**：需要从数据预处理到发表的完整工作流  
⚙️ **怎么上手**：官网有完整的教程和案例  
📊 **谁在用**：全球单细胞研究的主流工具  
💰 **费用**：完全免费

---

### 🧬 蛋白质结构

**4. [AlphaFold 3](https://alphafold.ebi.ac.uk)** — 最新的预测工具

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/5355dfd9-2743-43b8-b016-7ddad10e269a.png" width="400" alt="AlphaFold structure prediction visualization">

💡 **什么时候用**：需要预测蛋白质3D结构和相互作用  
⚙️ **怎么上手**：Web界面，上传序列即可  
📊 **谁在用**：全球数千个研究小组和公司  
💰 **费用**：学术用户完全免费

---

**5. [AlphaFold DB](https://alphafold.ebi.ac.uk)** — 2.2亿结构数据库

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/d1f72479-ca59-4792-bee8-7e86f4cf0446.png" width="400" alt="AlphaFold Protein Structure Database interface">

💡 **什么时候用**：需要查询已有的蛋白质结构  
⚙️ **怎么上手**：直接搜索蛋白质名称或序列  
📊 **谁在用**：全球结构生物学研究者  
💰 **费用**：完全免费

---

### 💊 药物发现

**6. [AutoDock Vina](https://vina.scripps.edu)** — 分子对接的经典

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/9f0b7a0d-f6e7-4abe-80f9-c79f05a72f58.png" width="400" alt="AutoDock Vina molecular docking result">

💡 **什么时候用**：进行分子对接，虚拟筛选化合物库  
⚙️ **怎么上手**：命令行简单易用，支持并行计算  
📊 **谁在用**：制药公司和研究机构  
💰 **费用**：完全免费

---

**7. [DrugPipe](https://github.com/HySonLab/DrugPipe)** — AI加速药物筛选

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/e7efa9d3-099d-4faa-b4d3-7a1f0e1a7be2.png" width="400" alt="DrugPipe AI-assisted drug discovery workflow">

💡 **什么时候用**：需要AI加速的虚拟药物筛选  
⚙️ **怎么上手**：GitHub有详细文档  
📊 **谁在用**：AI药物发现研究者  
💰 **费用**：开源免费

---

### 📈 数据可视化

**8. [ggplot2 + Plotly](https://plotly.com/r/)** — 出版级可视化

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/0d453de7-ed88-4e43-b941-d8196f8e03da.png" width="400" alt="ggplot2 publication-quality data visualization">

💡 **什么时候用**：需要为论文生成高质量的图表  
⚙️ **怎么上手**：`ggplotly()` 一行代码从静态转交互  
📊 **谁在用**：全球数千份发表论文  
💰 **费用**：完全免费

---

**9. [PyMOL](https://www.pymol.org)** — 3D分子可视化标准

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/8d27e0c4-4b5f-40c5-b5fd-82b969c27c4c.png" width="400" alt="PyMOL protein structure visualization">

💡 **什么时候用**：需要展示蛋白质3D结构  
⚙️ **怎么上手**：GUI友好，命令行强大  
📊 **谁在用**：结构生物学标准工具  
💰 **费用**：开源版免费

---

**10. [Avogadro](https://avogadro.cc)** — 分子编辑器

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/72974ca1-73ad-429b-b913-1d98a54451af.png" width="400" alt="Avogadro molecular editing and visualization">

💡 **什么时候用**：需要构建和优化分子结构  
⚙️ **怎么上手**：无需编程，图形界面  
📊 **谁在用**：化学信息学研究者  
💰 **费用**：完全免费

---

## AI应用案例 · 三个改变游戏规则的故事

### 案例1：Insilico Medicine — 30个月从发现到临床的奇迹

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/41ddfc34-b450-4730-922b-b5b045224397.png" width="400" alt="Insilico Medicine AI-designed drug discovery pipeline">

**问题**：肺纤维化患者肺功能快速衰退，传统药物开发太慢（5年）

**AI方案**：生成式AI平台Pharma.AI同时处理靶点发现和药物设计

**结果**：
- ⚡ **30个月进入临床**（vs传统5年），快17倍
- 🎯 发现**全新靶点**，此前无文献报道
- 💊 药物**Rentosertib**获FDA正式学名认可
- 📊 Phase IIa数据：肺活量改善98.4 mL

**启示**：AI不仅能加速"已知"，更能**发现"未知"**的新靶点和新作用机制。这不是单纯的速度提升，而是药物发现范式的根本性转变——从“筛选已有分子”到“生成全新分子”。当AI能够创造性地设计时，患者的等待时间将从年变成月。

---

### 案例2：Exscientia — 与Sanofi合作，将设计周期压缩70%

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/b7adb73c-c702-416b-8040-88241cbb20d1.png" width="400" alt="Exscientia AI drug design acceleration workflow">

**问题**：传统药物设计需要4.5年，罕见病患者等不起

**AI方案**：主动设计而非被动筛选，同时平衡药效、毒性、吸收等多参数

**结果**：
- 🚀 **设计周期缩短70%**（4.5年→12-15个月）
- 💰 开发成本显著降低
- ✅ 首个完全AI设计的**OCD治疗药物**进入人体试验
- 🌟 与Sanofi、GSK、住友制药建立长期合作

**启示**：这是**人+AI协作的完美范例**。AI处理海量的组合优化和参数平衡，人类科学家负责提出有价值的问题和做出关键决策。当重复性工作被自动化，科学家才能真正发挥创造力。这种分工模式正在重新定义药物研发的未来。

---

### 案例3：Recursion — 反转Eroom's Law的宏大野心

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/afe910ff-e98c-4891-b336-5d050f1cae9a.png" width="400" alt="Recursion Pharmaceuticals biology mapping AI system">

**问题**：Eroom's Law诅咒——尽管技术进步，药物开发成本和时间却在增加

**AI方案**：用AI+自动化高通量实验建立"人类细胞生物学完整地图"

**结果**：
- 🗺️ 建立**全球最大细胞生物学数据集**（数百万实验）
- 🎯 发现多个新靶点，多个候选药物进入临床
- 🚀 已成为**NASDAQ上市公司**，NVIDIA等巨头投资
- 📊 CEO宣称：**目标不是发现下一种药，而是改革整个流程**

**启示**：这代表了**从"单个靶点中心"到"整体生物学系统理解"的范式转变**。传统药物发现是在单个分子上下赌注，Recursion的方法是建立全局生物学地图，然后在地图上找路径。如果这种系统化方法成功，它可能真的能逆转Eroom's Law——让药物发现从愈发昂贵变得愈发高效。

---

## 数据集与资源 · 你需要的都在这

### 【我想快速获取高质量单细胞数据】

📊 **[scBaseCount - Virtual Cell Challenge](https://virtualcellchallenge.org/)**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/4df1d7d3-d253-435d-8648-e54f3646dd6b.png" width="400" alt="scBaseCount single-cell RNA-seq database">

- 📈 **300+百万细胞**跨26个生物体、72个组织
- 🎯 最大的单细胞基准数据集
- ⚙️ 标准化、可持续更新
- 🔬 **适合**：单细胞聚类、细胞类型识别、跨组织比较

---

### 【我想找基因表达研究的黄金源】

📊 **[GEO - Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/)**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/f8b7fb72-587c-4bba-ae86-c31938f9c106.png" width="400" alt="GEO Gene Expression Omnibus database interface">

- 📈 **50,000+研究**、数百万样本
- 🎯 学术界"金标准"，被10,000+论文引用
- ⚙️ 支持RNA-seq、微阵列、高通量表达数据
- 🔬 **适合**：基因表达挖掘、疾病相关基因、转录组学分析

---

### 【我想快速上手AI+生物学】

📚 **[Hugging Face Datasets - Biology](https://huggingface.co/datasets?search=biology)**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/5c4e4b36-24b5-4e75-b17f-a8d453ab3f2b.png" width="400" alt="Hugging Face Datasets biology collection">

- 📖 预处理、即插即用的生物学数据集
- 🎯 减少80%数据清理时间
- ⚙️ 支持迁移学习、版本管理
- 🔬 **适合**：AI/ML快速原型开发、LLM for biology

---

### 【我想零基础学生物信息学】

📚 **[Galaxy Training Platform](https://training.galaxyproject.org/)**

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/8cf4cc64-afdb-441a-9444-45694a8fefe5.png" width="400" alt="Galaxy Project training platform interface">

- 🎓 16+生物学子领域教程，从入门到高级
- 🎯 **零门槛实操**——直接在浏览器中运行
- ⚙️ 视频、代码、数据全提供
- 🔬 **适合**：入门学习、教师教学、快速验证分析流程

---

## 生命之美 · 自然的螺旋与秩序

在微观和宏观的世界里，从DNA分子到银河系，一个简单而优雅的数学规律在反复涌现——**螺旋**。这不仅是一种形状，更是生命的内在密码。本周，让我们透过显微镜和想象力，欣赏生命世界中那些隐藏的几何美学。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/e80fd1e1-0e33-4506-9590-a85e2be7dc4d.png" width="400" alt="DNA double helix 3D structure">

**DNA双螺旋** — 所有生命的语言，都被编写在这个优雅的旋转中。每一圈螺旋携带着数十亿年的进化历史，是生命延续的物质基础。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/71d19a65-e66b-4561-9e7c-219c0ebcad18.png" width="400" alt="Nautilus shell spiral cross-section">

**鹦鹉螺壳的黄金比例螺旋** — 这个贝壳的生长过程遵循完美的数学比例。每一间新建造的房间都比前一个大1.618倍（黄金比例），创造了视觉上绝对的和谐。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/fbfd5e07-d579-4eae-8ac7-d6a2e61c6a06.png" width="400" alt="Fern fiddlehead unfurling spiral">

**蕨类新芽的螺旋** — 春天到来时，新鲜的蕨叶从紧密的螺旋中缓缓展开，每一圈都遵循菲波那契数列。这是植物对空间和阳光的最优化解决方案。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/463f1b2e-2800-47ce-ac81-4eece979394e.png" width="400" alt="Butterfly wing scales microscopic detail">

**蝴蝶翅膀的鳞片** — 在显微镜下，这些微小的鳞片排列成完美的阵列，通过干涉和衍射光线产生虹彩。这是几百万年自然设计的结晶。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/89cf2df2-2030-4781-8520-aa8f174a903e.png" width="400" alt="Neural network brain connections">

**神经网络的无声建筑师** — 我们的思想和意识，归根结底是由数十亿个神经元和它们之间的连接构成。这张图展示了大脑皮层中神经突触的密集网络——一个自组织的、无比复杂的宇宙。

---

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/8b7a7759-eef3-4a1b-8b73-d30a436b0c23.png" width="400" alt="Snowflake crystal hexagonal symmetry">

**雪花的六边形完美** — 每一片雪花都是独特的，但它们都遵循相同的几何法则——水分子的对称性决定了晶体的形状。这说明，看似随机的自然创造，其实潜藏着数学的秩序。

---

### 最后的思考

看着这些图片，我们意识到生命不是混乱的，而是被一套优雅的数学规律所统治的。**螺旋、对称、比例**——这些数学元素在不同尺度上反复出现，从亚原子级别的DNA，到我们漫步其中的宇宙。

这提醒我们：**科学的本质就是在复杂的表象下，找到那些简单而美丽的规律**。而当我们看懂了这些规律，我们才真正看懂了生命。

---

## 前沿思考 · 这周最深刻的3个反思

<img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/a3769f52-9d67-461a-9c49-ccbcc67c1ce9.png" width="400" alt="Deep reflection and intellectual contemplation">

### 《医疗AI的真实困境：凭证制度与能力的碰撞》
**Bryan Vartabedian | 33 Charts**

医学一直是关于凭证的。我们是一个建立在等级制度、执照和长期培训轨迹上的系统。但AI改变了规则。

> "医学在历史上一直是'反创业'的。但它有效。它保护患者并维护公众信任。**但AI不在乎凭证。它在乎结果。而越来越多，我们作为患者和医生也开始在乎结果。**"

**深层问题**：在AI时代，专业信任应该建立在**凭证**上，还是建立在**可验证的能力**上？

[阅读原文](https://33charts.substack.com/p/the-end-of-medical-credentialism)

---

### 《AI的下一个范式转变：LLM的终局与世界模型的开始》
**Yann LeCun | Meta Chief AI Scientist**

当整个AI行业都在追逐更大的LLM时，一个关键的声音在问：

> "当前方法，尤其是过度依赖自回归大语言模型（LLM），在根本上受到限制，不会导致真正的高级机器智能。**真正的智能涉及在开放式、不可预测的环境中进行非平凡的问题解决。我们需要的是能够从感官输入直接学习世界模型的系统。**"

**深层问题**：我们是否正在走错方向？规模真的等于智能吗？

[阅读原文](https://www.bizrescuepro.com/future-of-ai-yann-lecun/)

---

### 《制药行业的成本困境：血流的警告》
**Derek Lowe | In The Pipeline**

在你看到血流之前，你不知道你削减得有多深。

> "真正的问题是：多少才是太多？问题是，**在你看到血流之前，你不知道你削减得有多深。**"

**深层问题**：对短期利润的追求是否正在摧毁长期创新能力？

[阅读原文](https://www.pharmamanufacturing.com/home/article/11358785/)

---

**这三篇文章的共同主题**：当我们用"效率"和"结果"重构传统制度时，我们会失去什么？

**🤔 值得深思的问题**：  
当AI取代医生的"凭证"，我们失去的是偏见还是信任？  
当我们追求更大的模型，我们是在接近真理还是远离本质？  
当企业削减成本以提高利润，创新的种子是否已被连根拔起？

**进步的代价，值得吗？**

---

## 专家观点 · 这周最触动人心的5句话

**1️⃣ Demis Hassabis** (DeepMind CEO, 2024年诺贝尔化学奖得主)

> "在人工智能加速科学发现的这个激动人心的新时代的风口浪尖，我们正准备好迎接一个深刻的变革。"

📍 出处：剑桥大学演讲  
💡 为什么重要：预示AI在科学发现中的变革性潜力

---

**2️⃣ Demis Hassabis**

> "AI将增强而非替代科学家。这些工具让科学家能'做得更多'——但它们无法理解什么是正确的问题。这必须来自人类的直觉。"

📍 出处：TIME专访  
💡 为什么重要：明确了AI的真实角色定位

---

**3️⃣ Yann LeCun** (Meta Chief AI Scientist, 图灵奖得主)

> "用更大的数据和更多计算资源堆砌LLM，只是工业团队的微小改进，而非突破性研究。我们缺少的是让机器像人类和动物一样高效学习的关键要素——我们还不知道那是什么。"

📍 出处：GTC 2025访谈  
💡 为什么重要：质疑AI发展方向，提出根本性警示

---

**4️⃣ Yann LeCun**

> "人工通用智能（AGI）可能在5到10年内出现。但我倾向于使用'先进机器智能'（AMI）这个术语，因为'通用'这个词本身就很误导——人类智能远非通用，我们已高度专化。"

📍 出处：LinkedIn访谈  
💡 为什么重要：冷静评估AI进展速度和方向

---

**5️⃣ Jennifer Doudna** (CRISPR发明者, 2020年诺贝尔化学奖得主)

> "我们正处于可编程基因组编辑的时代。看到这项技术的所有可能应用真的令人兴奋。我们知道它可以安全有效地治疗甚至潜在地治愈人类疾病，我们需要继续推进这项技术，使其部署更广泛。"

📍 出处：NYU Keynote演讲  
💡 为什么重要：从理论走向临床的里程碑

---

**核心启示**：AI和生物科学都站在突破的门槛上，但方向尚未确定。下一个十年，真正的进步不是来自更多的计算，而是来自对"根本问题"的重新思考。

---

## 下期预告 · 你最期待什么？

**下周可能的主题方向**：
- 🧪 AlphaFold在癌症靶点发现中的新突破？
- 🔬 单细胞空间组学如何革新免疫疗法？
- 💉 mRNA技术在个性化医学中的未来？

**你最关注哪个方向？欢迎留言告诉我们！**

---

**感谢你花45分钟与我们同行AI+生命科学的前沿。**

💬 **本期你最喜欢哪个部分？是AI发现新靶点的故事，还是显微镜下的米象甲？**  
你的反馈将帮助我们做得更好。

下期周五再见。🧬✨

---

*这份周报基于全球顶级科学机构的最新成果整理而成。*  
*本周刊[开源](github项目链接)，欢迎[投稿](github项目链接/issues)。*

**📮 订阅 | 🐙 GitHub | 💬 反馈**
