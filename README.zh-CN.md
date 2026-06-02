# awesome-ai-film 🎬

> **每一次技术革命，都在重塑艺术的边界。**
> 电力催生了电影。铝从皇室珍品变成了易拉罐。
> 智能——曾是人类最稀缺的资源——正在变得廉价。
>
> **当智能成为大宗商品，电影会变成什么？**

一份策展式的探索清单：AI 正在为电影制作打开哪些可能性，又有哪些东西依然是不可替代的人类领地。

[English](README.md) | 简体中文

---

## 前提

| 时代 | 稀缺资源 | 何时变得廉价 | 改变了什么 |
|------|---------|------------|-----------|
| 1880 年代 | 电力 | 电网普及 | 城市被点亮。电影诞生。 |
| 1890 年代 | 铝 | 霍尔-埃鲁法 | 从王冠上的珠宝变成易拉罐。摩天大楼、飞机成为可能。 |
| 1990 年代 | 算力 | PC + 互联网 | 任何有笔记本电脑的人都能成为出版者。 |
| 2000 年代 | 分发渠道 | YouTube、流媒体 | 任何人都能成为广播者。 |
| 2020 年代 | **智能** | 大语言模型、生成式 AI | 任何人都能成为……电影人？ |

每次当一个根本性约束消解时，我们得到的不仅是 *更多* 旧事物的复制品，而是 *全新类型* 的事物——那些在此之前根本不可想象的东西。

本仓库追踪电影领域的这场蜕变。

---

## 目录

- [AI 电影制作工具](#ai-电影制作工具)
- [文本生成视频](#文本生成视频)
- [AI 编剧与故事](#ai-编剧与故事)
- [AI 视觉特效与后期制作](#ai-视觉特效与后期制作)
- [AI 语音、音乐与声音设计](#ai-语音音乐与声音设计)
- [数字人类与 AI 演员](#数字人类与-ai-演员)
- [民主化：现在谁有资格拍电影？](#民主化现在谁有资格拍电影)
- [什么依然属于人类？](#什么依然属于人类)
- [研究论文](#研究论文)
- [早期案例与实验](#早期案例与实验)
- [经济变革](#经济变革)
- [哲学与批评](#哲学与批评)
- [参与贡献](#参与贡献)

---

## AI 电影制作工具

*端到端及专项 AI 辅助电影制作工具。*

- [Runway](https://runwayml.com) — Gen-3 Alpha。文本/图像转视频，运动笔刷，镜头控制。用于《瞬息全宇宙》的转描。
- [Pika](https://pika.art) — 文本生成视频，风格控制。支持唇形同步生成。
- [Kling](https://klingai.com) — 高保真中文视频生成模型。可生成 2 分钟连贯视频。
- [Sora](https://openai.com/sora) — OpenAI 文本生成视频。60 秒照片级写实短片，具有涌现式 3D 理解能力。
- [Hailuo (MiniMax)](https://hailuoai.video) — 文本生成视频，运动连贯性强。
- [LTX Studio](https://ltx.studio) — AI 原生视频编辑：剧本 → 故事板 → 剪辑。
- [Wonder Studio](https://wonderdynamics.com) — 自动替换演员为 CG 角色。光影与运动迁移。
- [Descript](https://descript.com) — 基于文本转录的 AI 视频编辑。删语气词就像删文字一样简单。
- [Topaz Video AI](https://topazlabs.com) — 画质提升：超分辨率、去隔行、降噪、帧插值。
- [EbSynth](https://ebsynth.com) — 基于关键帧的风格迁移。《凯尔经的秘密》同款美学管线。

---

## 文本生成视频

*从文本描述生成动态画面的模型与研究。*

- **Sora**（OpenAI，2024）— 扩散 Transformer。涌现式世界模拟。1920×1080 @ 60 秒。[技术报告](https://openai.com/research/video-generation-models-as-world-simulators)
- **Veo 2**（Google DeepMind，2025）— 4K 视频生成。电影级镜头控制。[官方公告](https://deepmind.google/technologies/veo/)
- **Kling 2.0**（快手，2025）— 1080p，2 分钟短片。3D 面部与身体重建管线。
- **Hailuo**（MiniMax，2024）— 时间连贯性强，短片段上可与 Sora 媲美。
- **Stable Video Diffusion**（Stability AI）— 开源。图像转视频，14/25 帧。
- **AnimateDiff** — 开源。嵌入 Stable Diffusion 实现动画输出。
- **ModelScope Text-to-Video** — 开源。中英文，16 帧片段。
- **CogVideoX**（清华/智谱）— 开源双语文本生成视频。720×480 @ 6 秒。

---

## AI 编剧与故事

*用于叙事生成、故事结构和剧本写作的大语言模型及专业工具。*

- [Sudowrite](https://sudowrite.com) — AI 小说写作。故事圣经、节拍表、散文生成。
- [ScriptBook](https://scriptbook.io) — AI 剧本分析。预测票房、受众画像、叙事缺陷。
- [Dramatron](https://arxiv.org/abs/2209.14958)（DeepMind）— 通过 LLM 链式调用的层级故事生成。梗概 → 角色 → 情节 → 对白。
- [PlotGen](https://plotgen.io) — 生成式情节大纲，支持按类型设定结构。
- [Claude](https://anthropic.com/claude) / [GPT-4](https://openai.com/gpt-4) — 通用模型。越来越多地被用作编剧助手：节拍表、对白润色、剧本评估。
- **编剧室**（概念）— 多智能体 AI 编剧室。每个 LLM 扮演房间里的不同"声音"。

---

## AI 视觉特效与后期制作

*AI 如何改变 VFX 管线、合成、调色和剪辑。*

- [Wonder Dynamics](https://wonderdynamics.com) — 自动角色替换。无需动捕、无需跟踪标记。（2024 年被 Autodesk 收购）
- [Runway Motion Brush](https://runwayml.com/research/motion-brush) — 选择性地让图像的特定区域动起来。
- [DAIN](https://github.com/baowenbo/DAIN) — 深度感知帧插值。将 12fps 平滑提升至 60fps。
- [神经辐射场（NeRF）](https://www.matthewtancik.com/nerf) — 从 2D 图像重建 3D 场景。实现虚拟机位。
- [高斯泼溅（Gaussian Splatting）](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) — 实时辐射场渲染。VFX 预可视化领域的变革者。
- [DeepFaceLab](https://github.com/iperov/DeepFaceLab) — 换脸/深度伪造工具。在《爱尔兰人》的减龄探索中使用。
- [Colourlab AI](https://colourlab.ai) — AI 调色。自动匹配参考影调。
- [Adobe Firefly](https://firefly.adobe.com) — 生成式填充、视频调色、文字特效。

---

## AI 语音、音乐与声音设计

*合成语音、AI 谱曲、程序化音效。*

- [ElevenLabs](https://elevenlabs.io) — 文本转语音与声音克隆。29 种语言。用于配音和 ADR 替换。
- [Suno](https://suno.ai) — 文本生成音乐。可生成完整歌曲（人声 + 器乐）。
- [Udio](https://udio.com) — 高质量音乐生成。在曲式结构上表现出色。
- [AIVA](https://aiva.ai) — AI 电影配乐作曲。已在 SACEM 注册超过 250 部作品。
- [Respeecher](https://respeecher.com) — 电影级声音克隆。在《曼达洛人》中重现年轻卢克·天行者的声音。
- [Murf](https://murf.ai) — AI 配音工作室，支持情感控制。
- [Descript Overdub](https://descript.com/overdub) — 克隆你的声音，通过打字修复音频错误。

---

## 数字人类与 AI 演员

*合成演员、数字替身，以及"谁在表演？"这个问题。*

- [MetaHuman](https://metahuman.unrealengine.com)（Epic Games）— 实时照片级写实数字人类。数分钟内创建完成。
- [Siren AI / Digital Domain](https://digitaldomain.com) — 数字人类管线。用于《复仇者联盟》《银翼杀手 2049》、演员减龄。
- **虚拟偶像 / VTubers** — 完全由 AI 驱动的表演人格。"演员"从未作为一个独立的人存在过。
- [Synthesia](https://synthesia.io) — AI 视频播报员。140+ AI 形象。已在企业培训中大规模使用。
- [HeyGen](https://heygen.com) — 照片说话、AI 形象视频生成。
- **减龄技术** — 《爱尔兰人》《夺宝奇兵 5》《双子杀手》。保真度快速提升。
- **逝后表演** — 彼得·库欣在《侠盗一号》、凯丽·费雪在《天行者崛起》。法律与伦理的前沿。

---

## 民主化：现在谁有资格拍电影？

*当成本底线下降时，谁会进入竞技场？*

历史上电影制作的成本结构：
- **2000 年代以前**：5000 万美元以上的制片厂体系。高度门槛化。
- **2000 年代**：1 万美元以上的准专业摄影机 + YouTube。独立电影浪潮。
- **2010 年代**：1000 美元以上的智能手机。"用 iPhone 拍摄"成为营销活动。
- **2020 年代**：每月 0 美元的 AI 工具，任何有网络的人都能使用。

### 新一代电影人
- **单人创作者** — 一个人 + AI = 一部电影。不需要团队、不需要预算、不需要看门人。
- **非英语电影** — AI 配音/本地化打破发行壁垒。
- **小众类型片** — 一部零预算的实验科幻短片可以看起来像一亿美元的制作。
- **交互式与生成式电影** — 每一次观看都是不同的电影。
- **同人电影与混剪文化** — 法律灰色地带。创意大爆炸。

### 反作用力
- **发行仍然重要**。拍出电影 ≠ 被看到。
- **品味的守门转向策展**。瓶颈从生产转移到发现。
- **平台依赖**。AI 工具是 SaaS。生产资料并不归你所有。

---

## 什么依然属于人类？

*在一个 AI 能生成任何画面、任何声音、任何场景的世界里——有什么是它做不到的？*

### 人类不可替代的理由

| 人类能力 | AI 为何难以企及 |
|---------|--------------|
| **亲身经历** | AI 没有童年、没有心碎、没有悲伤。它模拟情感——但并不感受。 |
| **品味与判断** | 知道该剪哪一镜、该用哪一条、哪句台词能击中人心。AI 能生成 1000 个版本，但选不出那个 *重要* 的。 |
| **文化直觉** | 理解为什么一个笑话在拉各斯好笑但在洛杉矶不好笑。亚文化的质地。 |
| **道德重量** | 人类创作的艺术承载着意图的重量。"一个人选择说出这句话"与"一个 AI 生成了这句话"是不同的。 |
| **凝视** | 电影是某个人的*注视*。他们选择看什么、看多久、为什么——这是导演的意识。 |
| **在场** | 一个演员在房间里。现场表演的张力。镜头之间发生的东西。 |
| **风险与脆弱** | 把真实的东西放在银幕上，创作者要付出代价。AI 什么都不承担。 |

### 什么可能真正存活下来（有根据的推测）

- **现场表演** — 戏剧、音乐会、直播。"此刻正在发生"，无可替代。
- **纪录片** — 摄影机与现实的关系。索引性的真实。
- **作者电影** — 某个特定人类异质性的视角。不是因为 AI *不能* 异质，而是因为我们不会 *在乎* AI 的异质。
- **社区电影** — 为特定社区、由特定社区制作。制作本身*就是*意义。
- **手工美学** — 当 AI 的完美变得廉价，不完美就成为溢价。颗粒感、实拍效果、"人为错误"。

### 那个尖锐的问题

> 当一部 AI 生成的电影赢得奥斯卡——不是最佳视觉效果，而是最佳影片——我们该怎么办？

---

## 研究论文

*AI 与电影的学术研究。*

- [Video Generation Models as World Simulators](https://openai.com/research/video-generation-models-as-world-simulators) — OpenAI Sora 技术报告，2024。
- [Dramatron: Hierarchical Story Generation](https://arxiv.org/abs/2209.14958) — DeepMind，2022。LLM 链式编剧。
- [Make-A-Video: Text-to-Video without Text-Video Data](https://arxiv.org/abs/2209.14792) — Meta，2022。T2V 先驱工作。
- [Imagen Video: High Definition Video Generation](https://arxiv.org/abs/2210.02303) — Google，2022。
- [Align your Latents: High-Resolution Video Synthesis](https://arxiv.org/abs/2304.08818) — Video LDM，2023。
- [Phenaki: Variable Length Video Generation](https://arxiv.org/abs/2210.02399) — Google，2022。长视频生成。
- [Tune-A-Video: One-Shot Tuning of Image Diffusion Models](https://arxiv.org/abs/2212.11565) — 2023。微调文生图模型用于视频。
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) — Stanford/Google，2023。LLM 智能体作为角色。
- [Neural Radiance Fields (NeRF)](https://arxiv.org/abs/2003.08934) — Mildenhall 等，2020。场景表示。
- [3D Gaussian Splatting](https://arxiv.org/abs/2308.04079) — Kerbl 等，2023。实时辐射场。

---

## 早期案例与实验

*值得一看的 AI 生成或 AI 辅助电影。*

- **The Frost**（Waymark，2023）— 12 分钟 AI 生成电影，使用 DALL-E 2 + D-ID。叙事连贯性的里程碑。
- **Thanksgiving**（Fabian Stelzer，2023）— AI 原生短片。观众投票决定故事分叉。[Twitter 帖](https://twitter.com/fabianstelzer)
- **Safe Zone**（Runway AI 电影节获奖作品，2023）— AI 辅助制作的关于监控的短片。
- **The Crowd**（Glenn Marshall，2022）— 神经风格迁移短片。戛纳入选。
- **Critterz**（Native Foreign，2023）— 首部登陆主流平台的 AI 生成动画。DALL-E + 专业动画管线。
- **AI 生成预告片** — 粉丝使用 Midjourney + Runway 制作"如果"概念预告片（如《塞尔达传说》《生化奇兵》）。
- [Runway AI 电影节](https://runwayml.com/ai-film-festival/) — 年度展映。作品质量逐年提升。
- [Curious Refuge](https://curiousrefuge.com) — AI 电影制作社区。病毒式 AI《星球大战》预告片的诞生地。

---

## 经济变革

*当制作成本趋近于零，电影产业的经济逻辑会发生什么？*

### 当前成本结构（估算）
| 项目 | 制片厂电影 | 独立电影 | AI 辅助 |
|------|----------|---------|--------|
| 剧本 | $50 万–$500 万 | $1 万–$10 万 | $0–$100（大语言模型） |
| 演员 | $500 万–$1 亿+ | $5 万–$100 万 | $0–$500（TTS 语音） |
| 视觉特效 | $1000 万–$2 亿 | $5 万–$100 万 | $0–$5000（生成式） |
| 声音/音乐 | $50 万–$500 万 | $1 万–$5 万 | $0–$100（AI 音乐） |
| **总计** | **$5000 万–$3 亿+** | **$50 万–$1000 万** | **$0–$1 万** |

### 影响
- **供给爆炸**。当任何人都能拍电影，我们会被内容淹没。
- **策展成为新的守门人**。电影节、算法、品味引领者。
- **长尾吃掉大片？** 还是大片作为文化锚变得更加重要？
- **IP 成为一切**。当执行变得廉价，*创意* 才是唯一重要的。
- **现场 + 体验的溢价**。那些无法被生成的东西变得更加珍贵。

---

## 哲学与批评

*深入思考这一切意味着什么的声音。*

- **Ted Chiang（姜峯楠）** — 《为什么 AI 不会创造艺术》。[《纽约客》，2024](https://www.newyorker.com/culture/the-weekend-essay/why-ai-isnt-going-to-make-art)
- **Walter Benjamin（瓦尔特·本雅明）** — 《机械复制时代的艺术作品》（1935）。原作的"灵光"。在生成时代重读此文。
- **André Bazin（安德烈·巴赞）** — 《摄影影像的本体论》。电影与现实的关系是什么？当影像是生成的，而非捕捉的。
- **Hito Steyerl（黑特·史德耶尔）** — "劣质影像"。当图像失去分辨率却获得速度，会发生什么？AI 反转了这一点：无限分辨率，可疑的来源。
- **Lev Manovich（列夫·马诺维奇）** — 《新媒体的语言》。数据库逻辑与叙事。AI 作为终极数据库电影。
- **Shane Denson** — 《去关联影像》。后电影情动。AI 图像的"感觉"为何不同。

---

## 参与贡献

这是一份活的文档。面貌每周都在变化。

**如何贡献：**
1. **新工具** — 必须可公开访问（开源、商业版或等候名单中的内测）。不接受纸面产品。
2. **论文** — 必须具有 arXiv/DOI。预印本也欢迎。
3. **电影/案例** — 必须可在线观看。链接到作品本身，而非关于它的推文。
4. **哲学** — 必须有实质内容。不接受即兴评论。

提交 PR 或 Issue。附上链接，解释为什么它对于 **从"不可能"到"可能"的转变** 很重要。

详细指南请参阅 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 许可协议

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — 公共领域。这些知识属于每一个人。

---

*由 [SpencerRaw](https://github.com/SpencerRaw) 维护。源于一种信念：智能成本降至零是我们这个时代最重要的故事——而电影，是我们将最直观地看到其影响的地方。*
