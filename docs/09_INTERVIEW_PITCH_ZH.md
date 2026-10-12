# 09 — ENTTEC 面试故事线（中文版）

## 这次面试要讲的不是“一堆 idea”

你真正要讲的是一个完整的产品故事：

> **我为什么会对音乐与光影表达产生兴趣  
> → 我看到了什么用户问题  
> → 我为什么认为 EMU 是合适的实验入口  
> → 我会怎样低成本验证市场  
> → 怎样把内容升级成 Artist Lab 和产品发现  
> → AI 在什么时候才值得出现  
> → 我希望 Product Specialist 在这条链路里承担什么责任**

这条故事比“我有一个 AI 灯光 idea”完整得多。

---

# 1. 故事起点：为什么是音乐 × 光

先讲个人真实来源，不讲技术。

> 我以前去过坂本龙一在北京的《观音·听时》展览。那是我第一次很强烈地意识到，光影和音乐之间不一定只是简单同步。光、空间、时间本身都可以参与表达创作者的意图。
>
> 后来我接触过 Hue + Spotify 这类音乐联动，又觉得它虽然能让灯跟着音乐变化，但离“创作者真正想表达什么”还有很远。
>
> 所以我一直在想一个问题：**一个不是专业灯光设计师的音乐人，怎样把脑子里的感觉变成真正可执行的光影语言？**

停一下。

这就是整套故事的原点。

---

# 2. 再回到岗位本身：先问 ENTTEC 为什么改了职位

不要一上来就 pitch。

先问：

> Since the role is now broader than EMU, what product problems or opportunities made the team decide to broaden it?

然后：

> When you say “not limited to EMU”, does that mainly mean supporting more products, or taking broader product responsibility across software and hardware applications?

你要先知道真实岗位是什么。

---

# 3. 产品观察：EMU 和 ELM 可以形成怎样的关系

如果她的回答说明岗位确实接近产品、软件组合或用户发现，再说：

> 我注意到 ELM 2026 已经引入了大量来自 EMU 的 shader effects。这让我产生一个假设：也许 EMU 不一定只是一个小型版工具，它还可以承担 creator-facing experimentation 的角色；而 ELM 继续承担专业、大规模、可重复和可靠的 production workflow。
>
> 这样一些在音乐人身上验证成熟的 creative idea，未来如果真的对专业用户也有价值，再进入 ELM。

英文可以直接说：

> I noticed that ELM 2026 includes a large set of effects that originated in EMU. It made me wonder whether EMU could be a creator-facing experimentation platform, while ELM remains the professional environment where selected mature creative ideas become production-grade capabilities.
>
> I don’t know whether that matches how ENTTEC thinks internally, so I’d be interested in how you see the relationship between the two products.

然后停。

---

# 3A. 我真正想和音乐人一起研究的东西：Music-to-Light Visual Grammar

这一段其实是整套 Artist Lab / AI 逻辑里非常核心的一层，面试里如果对方开始认真聊 EMU 的未来，我会主动讲。

我真正想做的，不只是：

> “把 drums、bass、vocals、synth 分出来，然后分别控制灯。”

因为这仍然只是技术层的 mapping。

我更想和音乐人一起研究：

> **他们自己到底怎样理解一首歌里的不同元素？这些元素在表达上分别承担什么作用？这些作用又应该怎样变成视觉语言？**

比如同一个 bass：

- 对某个音乐人来说可能代表重量、压迫感；
- 对另一个音乐人来说可能代表流动、身体感；
- 甚至有些歌里 bass 很重要，但视觉上反而不应该被单独强调。

所以真正要建立的是：

**musical element  
→ artist-defined role  
→ artistic intent  
→ desired visual relationship  
→ visual primitive  
→ EMU implementation**

而不是：

**bass = 红色 / kick = 闪光 / vocal = spotlight**

### 我会怎么和音乐人一起做

拿音乐人自己的一首真实作品，一起拆：

- 哪些 section 对 ta 最重要？
- 哪些元素是“主角”？
- 哪些元素负责 tension、release、intimacy、movement、atmosphere？
- 哪些东西应该跟光精确同步？
- 哪些应该 delayed / drifting / counterpoint？
- 哪些虽然音乐上重要，但灯光反而应该保持安静？
- 第二次副歌为什么不能只是第一次的复制？
- 什么样的光影会让 ta 觉得“这根本不是我这首歌”？

然后再一起把这些东西翻译成：

- brightness / darkness
- colour / colour transition
- spatial focus
- width / compression
- movement
- density
- transition
- foreground / background
- sync / delay / drift / counterpoint
- repetition / variation
- stillness / silence

做出几个小版本，让音乐人直接判断：

> 哪个最像我想表达的东西？  
> 哪个技术上很炫，但艺术上完全不对？

### 面试里可以直接说

> What I’d really like to learn from musicians is not just which stems are present in a song, but what those elements mean in their own creative language.
>
> I’d want to build a music-to-light visual grammar with them: which musical elements carry weight, tension, intimacy or release, how they want light to relate to those elements, and which visual primitives actually feel true to their intention.
>
> I think that research could become the foundation for better EMU workflows first, and only later, if the pattern is real, an AI-assisted creative translator.

这里最重要的是：

> **先和音乐人一起定义 translation grammar，再考虑自动化。**

这会让后面的 Artist Lab 和 AI 都显得不是凭空冒出来的。

---

# 4. 市场怎么开始：不要一上来就请大艺人

这是现在整套故事里非常重要的一步。

你可以说：

> 如果要验证这个方向，我不会一开始就花很多成本请大牌音乐人。我会先验证一个更基础的问题：**大家到底愿不愿意看、愿不愿意自己尝试“把一首歌重新做成光影视觉表达”这件事。**

## 最初的内容形式

比如做一个：

**Reimagined in Light / Song to Light**

每一期：

1. 选一首有明确视觉气质、版权可行的音乐
2. 拆解它想传达的感觉
3. 用 EMU 做新的灯光解释
4. 找舞者 / creator 真正表演
5. YouTube 放完整制作过程
6. TikTok / Shorts 放最终成片
7. 复盘哪些地方 EMU 做得好、哪些地方卡住

一句话：

> **内容不是最终目的，而是一个低成本的 market discovery + product discovery 机制。**

---

# 5. 为什么旧歌 / K-pop / 舞蹈创作者是一个好切口

你可以用《Get Out》作为例子，但不要把它说成已经确定的计划。

> 比如我最近想到 JYJ 的 *Get Out*。它本身已经有很强的红色视觉语言、舞蹈、室内外空间切换。我觉得有意思的不是复刻原 MV，而是问：如果今天主要用光去重新解释这首歌，会是什么样？
>
> 老 K-pop 还可以带来一批因为 nostalgia 进来的观众，而舞团、K-pop cover creator 本来就非常在意视频视觉质量。

然后把市场机会讲出来：

> 这可能会打开一块我之前没有马上想到的市场：**dance studios、dance crews、choreographers、performance content creators。**
>
> 他们不一定需要大型专业灯光系统，他们真正想要的是让自己的视频不只是“翻跳”，而成为一次对音乐更完整的视觉诠释。

英文一句话：

> This may open an adjacent creator segment: dance studios, dance crews and performance creators who want to reinterpret music visually, not just record choreography.

---

# 6. 如果内容市场验证成立，再升级 Artist Lab

这时候才进入音乐人本人。

> 如果前面的内容形式证明真的有人看、有人想用、舞团和创作者愿意反复参与，我才会把它升级成 Artist Lab。

Artist Lab 的原则：

> **Design partner first, endorsement second.**

音乐人带来自己的歌。

不问：

> “你想要什么功能？”

而问：

- 你希望观众这一段感受到什么？
- 哪些地方灯光反而不应该跟 beat？
- 什么视觉会毁掉这首歌？
- 第二次副歌和第一次为什么应该不同？

团队把这些表达变成 product hypothesis。

---

# 7. 最有记忆点的一部分：Return Episode

可以很短地讲：

> 有时候音乐人想要的东西，现有 EMU 就是做不到。我觉得没必要藏起来。第一次可以诚实地做一个缩水版本，告诉观众这个 limitation。
>
> 如果几个月后我们真的把这个 capability 做出来了，再把这个音乐人请回来，用另一首歌重新做一次。
>
> 观众看到的是一个真实的过程：**创作者的愿望 → 产品限制 → 实验 → 产品变化 → 创作者回来验证。**

这个机制同时服务：

- product discovery
- 产品可信度
- 长期 creator relationship
- 连续内容叙事

---

# 8. 评论区：社区参与，但不能让点赞控制 roadmap

你可以说：

> 我很希望产品团队和音乐人一起直接跟评论区互动，但评论应该产生 hypothesis，而不是直接投票决定 roadmap。

比如有人问：

> “能不能识别歌词？”

不要直接说：

> 2000 赞，所以做。

而要问：

> 这里真正的需求是歌词语义？歌曲叙事？section awareness？还是别的东西？

这就是 Product Specialist 应该做的转译。

---

# 9. AI 最后出现，而不是最先出现

只有 Ebony 主动聊 AI、automation，或者问到你的 AI 背景时，再进入这一层。

核心观点：

> **AI should be a creative translator, not an automatic taste-maker.**

例子：

音乐人说：

> “最后一个副歌我要感觉整个空间变大，但不要更躁。”

AI 帮忙把这句话变成一个可编辑的 starting point：

- section
- spatial behaviour
- intensity
- movement
- transition
- sync / drift / restraint

但最终决定仍然在音乐人手里。

一句话：

> The product shouldn’t decide what the music means. It should help the artist express what they mean.

---

# 10. 最后把所有内容收回到 Product Specialist 这个岗位

这是你最重要的落点。

你不是在说：

> “我有很多创意。”

你是在说：

> **我希望成为那个能把模糊用户表达变成可验证产品问题的人。**

英文：

> I see the Product Specialist role as a bridge from customer input to product decision participation — understanding the problem, testing the hypothesis, and helping decide whether it deserves product investment and where it belongs in the portfolio.

---

# 11. 如果问你入职前 3–6 个月怎么做

不要说：

> “我马上做 Artist Lab / AI。”

回答：

## 0–30 天 — Learn
- 真正用 EMU
- 理解 ELM
- shadow Product / Engineering / Support / Sales
- 看真实 support data
- 搞清楚决策权和资源机制

## 31–60 天 — Discover
- 访谈音乐人 / creator
- 访谈 ELM professional users
- 找重复问题
- 验证 dance / creator market 是否真的成立

## 61–90 天 — Experiment
- 做 2–3 个 rights-cleared 的 Reimagined in Light pilot
- 至少一个舞团 / performance creator 合作
- 同时测试一个小 product hypothesis

## 4–6 个月 — Prove
- 看内容是否真的带来 qualified users
- 看 creator 是否愿意持续使用
- 再决定是否做 Artist Lab
- 再决定是否值得做 AI
- 再决定哪些 creative primitive 有 ELM 价值

最重要一句：

> I wouldn’t join and immediately try to build my idea. I’d first validate whether the problem is real and repeated.

---

# 12. 2 分钟极简版

如果对方只给你很短的时间：

> My interest in this space started from Ryuichi Sakamoto’s *seeing sound, hearing time* exhibition in Beijing. It made me realise that light shouldn’t just react to music — it can participate in artistic expression.
>
> That’s why EMU interests me. I think there may be a product opportunity between what a creator wants to express and the technical lighting controls they have to operate.
>
> I also noticed that ELM 2026 includes creative effects that originated in EMU, which made me wonder whether EMU could be a creator-facing place to experiment with new ideas, while selected mature capabilities eventually scale into professional workflows in ELM.
>
> I wouldn’t start by building a big AI feature or hiring major artists. I’d first test the market through a content format — reimagining rights-cleared music through light, working with dance creators, and seeing whether this creates real creator demand and product learning.
>
> If that works, I’d evolve it into an Artist Lab where musicians become design partners. I’d first work with them to understand how they decompose their own music and build a music-to-light visual grammar — what different musical elements mean to them, and how those meanings should translate into visual behaviour. AI could come later as a creative translator only after that grammar is understood.
>
> What I’d like to understand is whether this Product Specialist role would actually have the user access, experimentation space and product decision participation to run that kind of loop.

然后停。

---

# 13. 面试中不要急着说

一面不要主动展开：

- 要请 Sia / Muni Long / LANY
- 艺人 2–3 年合同
- 完整 AI architecture
- detailed shared engine architecture
- 明确断言 ENTTEC 应该把 EMU 定位成什么
- 明确断言公司老板已经想做 AI
- 一口气展示整个 GitHub

如果对方真的有兴趣，再把 repo 当成 follow-up material。

---

# 14. 你也在面试 ENTTEC

最后不要忘记，这不是单向展示创意。

你需要确认：

- Product Specialist 有没有 direct user access？
- 有没有独立 problem space？
- 能不能做 experiment？
- 有没有 Engineering capacity？
- 会不会参与 roadmap discussion？
- broader scope 是 ownership 还是更多 support？
- 12 个月以后能不能拥有更明确的 domain？
- 能不能从 discovery 一直跟到结果？

如果这些都没有，那么对方即使很喜欢你的 idea，这个岗位也可能不是你想要的产品入口。
---

# 中文版说明

本文件正文已经是中文版，因此不再重复附加同一份内容。  
对应的英文版本见：[10 — Interview Story (English)](10_INTERVIEW_PITCH_EN.md)。
