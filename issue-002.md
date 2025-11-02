# AI+生命科学周报（第 2 期）：AI用1天干完人类270年的活

记录每周值得分享的AI+生命科学前沿内容，周五发布。

本周刊[开源](https://github.com/dongyu19920904/ai-bio-weekly)，欢迎[投稿](https://github.com/dongyu19920904/ai-bio-weekly/issues)。

## 封面图

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-37-47-c09b343ce16bf68e503a23c4c8d94144.jpg)

**这张图展示了**：AI能力在医疗健康8大领域的冲击增长趋势。从2022年的2%影响力，逐年上升到2032年预测的26%。

**3个震撼数字**：

- 医疗分析和诊断：最高影响领域
- 增长轨迹：年均稳步上升
- 预期2032年：AI将成为医疗决策的关键因素

**一句话**：2025年10月，AI从"加速器"升级为"创新引擎"。

([via](https://intuitionlabs.ai/articles/genai-capabilities-life-sciences))

## 本期主题：AI用1天干完人类270年的活

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-38-34-410d615f8c45085460e0695e0f0e920c.jpg)

### 【第一幕】问题：找新药太慢

筛选1万个分子 → 花10年 → 烧26亿美元 → 只能找到1个药。

就像在10亿个分子库中筛选，即使每天筛选10万个，也需要27年才能完成。

---

### 【第二幕】转折：DrugReflector在24小时筛选10亿分子

| 指标     | 传统方法 | DrugReflector | 提升       |
| ------ | ---- | ------------- | -------- |
| 每日筛选量  | 10万  | 10亿           | **1万倍**  |
| 完整筛选时长 | 27年  | 1天            | **快27倍** |
| 能力     | 被动筛选 | **主动设计**      | 范式转变     |

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-39-09-853c90f1ff4621d20f5d2fa90660d961.jpg)

**尤其值得关注的是**：AI找到的靶点，从未在任何文献中出现过。

**真实案例**：一家药企用传统方法筛了3年50万个化合物，未能找到理想候选。用DrugReflector重新分析，3天找到5个全新分子，其中2个已进入临床前验证阶段。

---

### 【第三幕】启示：意味着啥？

**旧思路**：在现有化合物库里查找 → 测试 → 失败 → 重新查找
**新思路**：AI直接设计最优分子 → 合成验证 → 快速迭代

**一句话**：以后新药不是"找"出来的，是AI"设计"出来的。

([via](https://www.science.org/doi/10.1126/science.adi8577))

---

## 科研动态 · 本周5条快讯

### 1️⃣ 【视频AI】Sora 2：你的宠物能当AI视频演员了

![Three woolly mammoths walking in a snowy mountainous landscape with mist behind them](https://pplx-res.cloudinary.com/image/upload/v1759272085/pplx_project_search_images/1f22f633ec7ff6e94dbcdf5891ac2c028079aa9e.png)

拍一张宠物照片，AI就能生成60秒的动态视频。
**关键升级**：视频时长从46秒→60秒，并支持自动配音。
**医学用途**：蛋白质折叠、细胞分裂、生理过程，都能生成可视化动画。

**一句话**：生物教学以后不看静态图片，看"AI生成的生物动画"。

([via](https://help.openai.com/en/articles/12593142-sora-release-notes))

### 2️⃣ 【战略级】ChatGPT Atlas：挑战Google的AI浏览器

![Instacart website interface showing a ChatGPT assistant fulfilling a beach essentials shopping request](https://pplx-res.cloudinary.com/image/upload/v1761220129/pplx_project_search_images/07fd336ca725f372e0b3eeea12ae35a15247700f.png)

不是搜索框，是对话框。直接问AI："这篇PubMed论文讲什么？"
**市场冲击**：10%用户迁移，Google年收入面临约200亿美元风险。
**科研用途**：自动阅读文献、查询蛋白质数据库、分析实验数据。

**一句话**：从"搜索信息"转变为"AI理解信息"。

([via](https://intuitionlabs.ai/articles/chatgpt-atlas-openai-browser))

### 3️⃣ 【技术突破】Google Veo 3.1：8秒高清AI视频

![Confocal microscopy images showing stages of cell division and the effect of PLK1 inhibitor on mitosis](https://pplx-res.cloudinary.com/image/upload/v1754680634/pplx_project_search_images/ff2fad31171afd7418140347b08926448c23c89c.png)

1080p、24FPS、自动配音，业界领先的写实度。
**医学用途**：细胞分裂、DNA复制、手术过程，8秒完整展示。
**对比Sora**：Sora时长更长(60秒) vs Veo写实度更高(纹理细节)。

**一句话**：8秒足以展示完整的生物学过程，写实度可用于医学培训。

([via](https://blog.google/products/gemini/gemini-drop-october-2025/))

### 4️⃣ 【开源安全】OpenAI开源安全模型：AI安全决策透明了

![3D ribbon structure of a protein molecule highlighting its folding and domains in different colors](https://pplx-res.cloudinary.com/image/upload/v1762052295/pplx_project_search_images/3e0d1110a7f6dfcc06b290ebf3439d2bc69deb0c.png)

**gpt-oss-safeguard**让你看到AI是怎么判断"这个危险"的。
**关键创新**：政策变更无需重新训练，数小时内就能更新安全规则。
**生物安全用途**：审核病原体研究文献、评估基因编辑风险。

**一句话**：在生物安全领域，“为什么危险”与“是否危险”同样关键。

([via](https://openai.com/index/introducing-gpt-oss-safeguard/))

### 5️⃣ 【基础设施】Google+Anthropic：35亿美元算力军备竞赛

![Google TPU chip with metal heat sink for AI computing](https://pplx-res.cloudinary.com/image/upload/v1755868943/pplx_project_search_images/349696571211f19674f47140ee3255a908efea5c.png)

海量TPU集群、吉瓦级计算能力，AI领域迄今最大的算力协议。
**战略意义**：Anthropic 2026年营收预计260亿美元(相比2025年的90亿)。
**影响**：生物医学AI训练的计算能力正在指数级增长。

**一句话**：谁控制算力，谁就控制未来AI的方向。

([via](https://www.voxfor.com/google-and-anthropic-forge-massive-cloud-deal-a-game-changing-alliance-in-ai-infrastructure/))

---

## 💡 前沿思考：这周科学家们在争论什么

### 争论一：AI设计的危险蛋白——我们该如何平衡创新与安全？

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-50-49-c3dc2d7a6a7fd62af331daf4271433ac.jpg)

**背景**：2025年10月，微软研究团队证实AI设计的危险蛋白质能绕过DNA合成筛查系统。

**安全派**：这是实际的安全缺陷，需要国际协调的应对标准。
**创新派**：过度限制会阻碍疫苗和药物研发的进度。
**平衡派**：采用"分层访问"模式，低敏感数据公开，高敏感数据需授权。

**你该想啥**：不是“是否允许AI设计蛋白”，而是“如何建立有效的安全防护”。

([via](https://www.science.org/doi/10.1126/science.xxx))

### 争论二：AI医疗系统中的种族偏见——算法会延续历史不公吗？

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-52-54-38a607f0bce328a08d6e1f1c48fbb08b.jpg)

**背景**：一个广泛使用的美国医疗风险预测算法被发现存在严重的种族偏见。在同样的风险分数下，黑人患者患慢性病的数量比白人患者多**26.3%**。

**原因**：算法用"医疗支出"预测健康状况，但黑人患者因系统性医疗不公正获得医疗资源较少，导致被误判为"低风险"。
**修复**：改用直接的健康指标(慢性病诊断)后，黑人患者的招募率增加3倍。
**启示**：修复一个偏见≠解决问题，需要在AI全生命周期中嵌入公平性考虑。

**你该想啥**：算法会延续历史不公，需要在AI设计中考虑公平性。

([via](https://www.science.org/doi/10.1126/science.aax2342))

---

### 争论三：AI自主处方权——创新还是冒险？

**提案**：美国众议员提议允许AI自主处方药物，只需FDA批准和州监管。
**时机**：同时FDA正在裁员2000人，包括AI监管部门。

**反对派**：处方错误可能致命，AI责任界定不清，时机不当。
**支持派**：医生处方错误率也有5-9%，AI可缓解医疗人员短缺。

**你该想啥**：我们在同时削弱监管能力，又扩大需要监管的技术权限，这个顺序反了.

---

## 🌟 专家观点：这周最触动人心的5句话

**1️⃣ DrugReflector研究团队 — “我们不再问‘这个分子可能有用吗？’我们问‘什么分子会最有用？’然后让AI告诉我们答案。”**

📍 出处：Science论文及Cellarity发布会  
💡 **为什么重要**：精准概括了从“被动筛选”到“主动设计”的范式转变

---

**2️⃣ Nicheformer研究团队 — “我们不是在训练AI识别癌细胞。我们在训练AI理解癌细胞如何与它的‘邻居’互动——这才是决定患者命运的关键。”**

📍 出处：*Nature Methods* Nicheformer论文  
💡 **为什么重要**：揭示了AI在生命科学领域从“识别”到“理解”的关键跨越

---

**3️⃣ Microsoft Research团队 — “现有的DNA合成筛查机制已经严重落后于AI生成的新颖序列。这不是一个理论问题，这是一个现实的安全缺口。”**

📍 出处：*Science*杂志生物安全论文（2025年10月）  
💡 **为什么重要**：用最直白的语言警告我们——AI能力的增长速度已经超过了安全措施的跟进速度

---

**4️⃣ Obermeyer等研究者 — “算法无法区分‘花钱少’是因为健康状况好，还是因为系统性的医疗不公正。”**

📍 出处：*Science*杂志医疗AI偏见研究（2019年，2025年被广泛引用）  
💡 **为什么重要**：一句话揭示了医疗AI偏见的根本原因——历史不公正会被算法学习和放大

---

**5️⃣ Nature Digital Medicine编辑 — "Congress should reject any legislation introducing AI-enabled autonomous prescribing unless it is accompanied by empowered, well-resourced regulatory oversight."**

📍 出处：Nature Digital Medicine评论（2025年3月）  
💡 **为什么重要**：为AI在医疗领域的应用设定了一个清晰的原则——权力必须与监管能力相匹配

---

## 有意思的图

![](https://github.com/dongyu19920904/ai-bio-weekly/blob/fc5f2f0338f20ecdb767478e727a801c292f94d0/image/2025-11-02-13-53-57-b23f751aecb04bdfa44005f5eb52c3d7.jpg)

**这张图展示**：2025年多模态Transformer架构如何整合视觉、语言、推理能力。

---

## 📚 深度阅读：那些改变想法的文章

📖 **[DrugReflector: 从筛选到设计的革命](https://www.science.org/doi/10.1126/science.adi8577)**

> “我们不再是在已知化合物库中寻找，而是在无限可能性中创造。”

✍️ **推荐理由**：详细解释AI如何从10亿分子中找到最优候选药物  
⏱️ **阅读时间**：15分钟  
🎯 **收获**：理解为什么AI药物设计是“完全不同的思维方式”

---

📖 **[医疗AI种族偏见研究](https://www.science.org/doi/10.1126/science.aax2342)**

> “算法无法区分‘花钱少’是因为健康好，还是因为系统性不公正。”

✍️ **为什么推荐**：这是医疗AI偏见领域的里程碑论文，用具体数据揭示了算法如何学习并放大社会不公  
⏱️ **阅读时间**：20分钟  
🎯 **收获**：理解偏见的根源，以及为什么修复一个偏见不等于解决问题

---

📖 **[GPT-5生物医学能力评估](https://intuitionlabs.ai/articles/gpt-5-biotechnology-healthcare-overview)**

> “在医学推理任务上，GPT-5的理解分数74.37%——超越了专家医生的44.97%。”

✍️ **为什么推荐**：第一份系统评估最新GenAI在生命科学领域表现的研究  
⏱️ **阅读时间**：25分钟  
🎯 **收获**：看清AI在哪些任务上已经超越人类，哪些还远远不够

---

## 下周预告

🚀 **下周可能聊**：

- AlphaFold 3的最新突破
- mRNA癌症疫苗新进展
- AI在罕见病诊断的应用

📌 **对哪个方向感兴趣？欢迎留言！**

---

**感谢你花20分钟与我们同行AI+生命科学的前沿。**

💬 **本期你最喜欢哪个部分？是DrugReflector的神速筛选，还是AI医疗偏见的争议？**  
你的反馈将帮助我们做得更好。

下期周五再见。🧬✨

---

*这份周报基于全球顶级科学机构的最新成果整理而成。*  
*本周刊[开源](https://github.com/dongyu19920904/ai-bio-weekly)，欢迎[投稿](https://github.com/dongyu19920904/ai-bio-weekly/issues)。*

**📮 订阅 | 🐙 GitHub | 💬 反馈**
