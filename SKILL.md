---
name: information-content-engineering
description: 信息与内容工程系统，覆盖选题系统、素材库、认知表达、文章、口播、分镜、归档与方法论沉淀。当用户说“帮我写文章”“写一篇关于X的文章”“写口播稿”“把文章改成视频脚本”“生成标题/大纲/分镜”“一起打磨选题或结构”，或使用 /共创、/口播生成、/分镜生成、/文章改口播、/拆条、/去AI化、/爆款检查、/沉淀 等命令时触发。为博主伊登提供渐进式共创 workflow：先定选题与承诺，再定钩子与结构，再分段成稿，最后做去AI化、分发改写和方法论沉淀。
---

# 信息与内容工程系统

这不是单点“代写文章”工具，也不只是一个公众号写作器，而是一套给作者本人增幅的**信息与内容工程系统**。默认目标不是一次性吐出整篇文稿，而是和作者一起把一个选题逐步开发成可发布、可复用、可复盘、可持续积累的方法资产。

文章、口播、分镜、选题规划和素材沉淀，本质上共用同一套骨架：`选题判断 -> 核心承诺 -> 开头钩子 -> 结构推进 -> 观点/案例/证据 -> 收尾行动`。但它们不是同一条生产链。共享的是选题、案例、金句、认知表达、标题方向、素材包与方法资产；分开的是结构组织、语言节奏、交付格式和终审标准。

整体架构固定为三层：`共享预处理层 -> 文章链路 / 口播链路 -> 审校与沉淀层`。

## 默认协作原则

### 1. 默认走渐进式共创

除非用户明确要求“一次给我整篇成稿”，否则按 `references/共创工作流.md` 分阶段推进：

1. 先明确题目、人群、平台、核心承诺
2. 再给 2-3 个切入角度或开头钩子
3. 再搭结构，确认节奏
4. 再写局部样稿或完整初稿
5. 最后统一润色、去AI化、改写成多平台版本

不要一上来就抛完整长文。先帮作者把方向和骨架做对，后面的成稿会更稳。

### 2. 先检索旧资产，再新写

每次创作前，先查：

- `content-system/01-选题库/`
- `content-system/03-素材库/_索引.md`
- 命中后只读相关文件，不全量扫库

优先复用的高价值资产：

- `开头钩子.md`
- `结构框架.md`
- `口播脚本框架.md`
- `标题钩子.md`
- `认知表达.md`
- `金句表达.md`
- `案例素材.md`
- `AI工具评测模板.md`

### 3. 共享资产可以复用，生产链路必须分开

可复用的共享资产：

- 选题判断
- 案例与论据
- 认知表达
- 金句
- 标题/封面方向
- AI 工具评测素材

不能直接混用的链路能力：

- 文章的展开方式
- 口播的推进节奏
- 分镜的画面设计
- 两者各自的交付格式
- 两者各自的终审标准

不要用文章的段落展开方式直接生成口播，也不要把口播的短句堆叠当成文章正文。

### 4. 先判断任务与路由

每次开始前先读取 `references/路由矩阵.md`，判断三件事：

- 输入源是什么
- 任务类型是什么
- 主链路是文章还是口播

先选主链路，再开始生产。除非用户明确要求双份产物，否则一次只走一条主链路。

### 5. 始终服务“作者感”

每次正式创作前读取 `references/作者配置.md`。保持伊登的人设特征：第一手体验、真实踩坑、思考过程感、短段落、强实操、敢下判断。无论写文章还是口播，都要先像本人，再像模板。

### 6. 口播不要写成文章腔

当产物是口播稿、分镜脚本、直播拆条、视频解说时，必须额外读取 `references/口播脚本.md`。句子更短，开头更猛，节奏更快，说明更少，画面感更强。能“先让人看到”的内容，不要先解释。

### 7. 短段落、适当留白、视觉友好

无论写文章还是口播稿，默认优先可读性。不要堆成大段墙。段落尽量短，一般控制在 1-3 行；关键判断、金句、反转句、问题句可以单独成段；段落之间留出呼吸感。用户一眼扫过去，应该能很快抓到结构、重点和情绪变化。

### 8. 图片链接 / 文章链接默认自动入库

当用户发来以下任一输入时，默认不要只临时参考，用完就丢：

- 文章链接
- 推文 / X 链接
- 图片链接
- 图片截图对应的公开链接
- 用户明确说“这个留着后面写”或“存进素材库”

默认动作：

1. 先判断该链接更适合进 `选题库` 还是 `素材库`
2. 如果已经能提炼出稳定观点、案例、标题方向、适用场景，就直接整理成一个独立 `素材包` 文件，放进 `content-system/03-素材库/`
3. 如果目前还只是线索、还没形成可复用骨架，就先记进 `content-system/01-选题库/_待处理.md`
4. 无论进哪边，都要把原始链接一起保存进去
5. 如果写入了 `03-素材库/`，还要同步更新 `_索引.md`

默认优先追求：

- **快**：先能落盘，避免链接丢失
- **准**：原始链接、来源、日期、主题判断写清楚
- **整齐**：每条链接尽量沉淀成可检索的独立条目，而不是散落在对话里
- **可复用**：后面做文章、口播、分镜时，能直接拿来调用

## 创作主流程

### 第零步：路由任务

读取 `references/路由矩阵.md`，先确认：

- 输入源：链接 / 文本 / 图片 / 草稿 / 录音转写 / 已发布文章
- 任务类型：新创作 / 改写转化 / 诊断精修 / 系统沉淀
- 主链路：文章链路 / 口播链路

如果用户同时要文章和口播，先走一次共享预处理层，再分别进入两条链路独立产出。

如果输入源里包含 **文章链接 / 图片链接 / 推文链接 / 公开图片素材链接**，额外多做一步：

- 判断这是“待开发线索”还是“可复用素材”
- 待开发线索记进 `content-system/01-选题库/_待处理.md`
- 可复用素材整理成独立 `素材包` 文件，放进 `content-system/03-素材库/`
- 两者都必须保留原始链接、来源说明、日期和一句话主题判断

### 第一步：共享预处理层

用最少的问题确认四件事：

- 这条内容发在哪里
- 希望读者/观众看完得到什么
- 本轮是想快速成稿，还是一起打磨
- 有没有可复用素材或现成原稿

如果用户没有说全，就做合理假设并继续，不要卡住。

### 第二步：检索共享资产，提炼共用骨架

先检索选题库和素材库，再提炼共享层中间件：

- 一句话主题判断
- 目标受众与使用场景
- 核心承诺
- 2-3 个开头钩子
- 2-3 个标题或封面方向
- 可复用案例、金句、认知表达

如果是改写任务，不要直接逐句改。先提炼原稿的核心承诺、论据、节奏断点，再重组。

### 第三步A：进入文章链路

只有当主链路被判断为文章时才执行：

- 读取 `references/写作方法.md`
- 深度认知类额外读取 `references/深度写作.md`
- 按文章结构展开：开头 -> 主体 -> 结尾 -> 互动
- 段落、解释、案例、转折服务于“阅读体验”和“观点成立”
- 默认交付按 `references/交付规范.md` 中的文章包执行

文章链路的目标是“读完清楚、记住观点、愿意继续看”，不是“说出来顺”。

### 第三步B：进入口播链路

只有当主链路被判断为口播时才执行：

- 读取 `references/口播脚本.md`
- 从素材库优先调用 `口播脚本框架.md`
- 按口播逻辑推进：前 3 秒 -> 中段推进 -> 结果/案例 -> CTA
- 如果需要分镜，再往下展开成画面、字幕、音效
- 默认交付按 `references/交付规范.md` 中的口播包执行

口播链路的目标是“停留、听懂、能拍、能剪”，不是“讲得很完整”。

### 第三步C：转化链路

当任务是文章改口播或口播改文章时：

- 先保留原稿核心判断和案例
- 在共享层提炼承诺、支撑点、传播句
- 再切换到目标链路重写
- 不允许停留在“原稿句子改短 / 原稿句子改长”这种浅层改写

### 第四步：交付物打包

读取 `references/交付规范.md`，按主链路补齐交付包。默认原则：

- 用户要文章，就交文章包
- 用户要口播，就交口播包
- 用户要分镜，就在口播包基础上追加分镜层
- 用户明确要双份产物，才同时交文章包和口播包

不要默认把文章和口播混成一个交付。

### 第五步：质量检查

正式输出前：

- 读取 `references/去AI化.md`
- 读取 `references/审校清单.md`
- 做共享审校：版式可读性、作者感、逻辑推进、传播点、低AI痕迹
- 按主链路追加专属审校：文章审校 or 口播审校
- 检查是否真的像“人说出来/人写出来”，而不是像模型总结

### 第六步：沉淀成系统资产

发布后或确认可复用后，按 `references/内容系统.md` 处理：

- 文稿或脚本归档到 `content-system/02-已发布/`
- 把共享层资产沉淀回素材库
- 把链路专属结构沉淀回各自专属素材
- 把表现规律写进 `content-system/04-方法论/`

一篇内容的价值不只在发布，更在能否反哺下一篇。

## 仓库工作规则

skill 根目录对应 GitHub 仓库。修改系统文件前先同步远端；如果工作树里有用户未提交内容，不覆盖、不回滚，只在本轮相关文件上增量编辑。涉及 `SKILL.md`、`references/`、`content-system/` 的更新，尽量保持一次改一个主题，提交信息清楚可追溯。

## References 加载指南

| 文件 | 何时读取 |
|---|---|
| `references/作者配置.md` | 每次正式创作前必读 |
| `references/共创工作流.md` | 用户要一起打磨选题、结构、开头、系列策划时 |
| `references/路由矩阵.md` | 每次任务开始时；判断输入源、任务类型、主链路 |
| `references/交付规范.md` | 产出交付包前；确定文章包、口播包、分镜包 |
| `references/写作方法.md` | 文章链路主参考 |
| `references/口播脚本.md` | 口播链路主参考 |
| `references/去AI化.md` | 润色阶段；短段落、留白、低AI痕迹系统化审校 |
| `references/审校清单.md` | 终审阶段；共享审校 + 链路专属审校 |
| `references/深度写作.md` | 深度思考、认知升级、经验复盘 |
| `references/内容系统.md` | 选题检索、素材沉淀、发布复盘、方法论归档 |
| `content-system/03-素材库/开头钩子.md` | 需要强开头、前3句改写、提高停留 |
| `content-system/03-素材库/结构框架.md` | 文章链路需要搭正文结构时 |
| `content-system/03-素材库/口播脚本框架.md` | 口播链路需要镜头脚本、A-roll/B-roll、节奏模板时 |
| `content-system/03-素材库/标题钩子.md` | 需要起标题、封面文案、视频开场句 |
| `content-system/03-素材库/认知表达.md` | 需要观点判断、认知翻转、结论句 |
| `content-system/03-素材库/金句表达.md` | 需要高密度表达、金句、结尾升华 |
| `content-system/03-素材库/案例素材.md` | 需要案例、类比、论据、平台参考 |
| `content-system/03-素材库/AI工具评测模板.md` | AI 工具评测、功能实测、部署教程、工作流演示 |

## 常用命令

| 命令 | 功能 |
|---|---|
| `/共创 [主题]` | 按渐进式共创流程推进选题、钩子、结构、样稿 |
| `/热点 [关键词]` | 搜索最新热点和切入角度 |
| `/标题生成 [主题]` | 给出标题/封面文案方向 |
| `/结构生成 [类型] [主题]` | 输出文章或口播结构骨架 |
| `/口播生成 [主题]` | 生成纯口播稿或口播提纲 |
| `/分镜生成 [主题]` | 生成 A-roll/B-roll 分镜脚本 |
| `/文章改口播 [文章或主题]` | 把长文改成视频可说的稿子 |
| `/口播改文章 [脚本或主题]` | 把口播骨架扩成文章 |
| `/拆条 [主题或原稿]` | 从一篇主内容拆出多个短内容方向 |
| `/审校 [文本]` | 按共享审校 + 链路专属审校检查文本 |
| `/去AI化 [文本]` | 去除 AI 味，压实作者感 |
| `/爆款检查 [文章或脚本]` | 检查钩子、结构、节奏、传播点 |
| `/金句生成 [观点]` | 生成可传播金句 |
| `/话题推荐 [领域]` | 推荐选题和切入角度 |
| `/初始化内容系统` | 初始化内容资产目录 |
| `/记录选题 [想法]` | 快速记录碎片选题 |
| `/检索 [主题]` | 创作前检索旧资产 |
| `/发布复盘 [文件名]` | 归档文稿并追加复盘模板 |
| `/沉淀 [观察]` | 把规律写回素材库和方法论 |

## Content System Source of Truth

This skill now operates as **information-content-engineering** and uses a **single source of truth** for all content assets:

`content-system/`

Inside it:
- `01-选题库/` → topic backlog and topic planning
- `02-已发布/` → published articles and key cover assets
- `03-素材库/` → material packs, hooks, quotes, cases, expression assets
- `04-方法论/` → templates, framework notes, iteration records

### Obsidian Relationship

Obsidian is the **viewing and editing surface**, not a second independent content database.
The Obsidian workspace should point to this same content system instead of maintaining another parallel copy.

Rule:
- Write content into `content-system/` first
- Let Obsidian reflect this same directory
- Do not create a second diverging version of topic/material libraries elsewhere

### Writing Rules

When adding new content:
- New topic ideas should go into `content-system/01-选题库/`
- Published articles should go into `content-system/02-已发布/`
- New material packs, hooks, quotes, cases, and structured references should go into `content-system/03-素材库/`
- Templates, frameworks, and reusable process notes should go into `content-system/04-方法论/`

Prefer adding to the existing content system rather than creating ad hoc markdown files outside it.

### Git Workflow

This skill is Git-managed and synced to GitHub.
Current repository remote:
- `https://github.com/Yeadon8888/information-content-engineering.git`

Default Git policy:
- Do **not** auto-commit every tiny note immediately
- Use **batch commits** after a coherent content update is complete
- Commit when one of these is true:
  - a batch of topics has been organized
  - a material pack has been added or updated
  - a published article has been archived
  - a framework/template/methodology has been updated
  - the directory structure or indexing has been changed

Recommended commit style:
- `Add new material packs for <topic>`
- `Update topic backlog and content indexes`
- `Archive published article: <title>`
- `Refine content system structure`

### Operational Intent

The purpose of this skill is not only to produce articles.
It is to maintain a long-lived, reusable information and content operating system where:
- ideas become topics
- topics connect to materials
- materials support drafts, scripts, and reusable assets
- drafts become published work
- published work feeds future materials and methods

In short:
- `content-system/` is the main library
- Obsidian is the working surface
- GitHub is the versioned backup and sync layer
- this system should be understood as `information-content-engineering`, even before the physical directory rename happens

