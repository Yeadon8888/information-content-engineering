# information-content-engineering

**信息与内容工程系统**

这是原 `wechat-article-writing` skill 的软迁移版本。

当前这套系统已经不再按单一写作工具理解，而是按一套更完整的长期系统来使用：

- 信息处理
- 选题规划
- 素材沉淀
- 认知表达
- 文章写作
- 口播脚本
- 分镜设计
- 发布归档
- 方法论沉淀

## 当前状态

当前已完成的是**软迁移**：

- 系统名统一为 `information-content-engineering`
- 中文定位统一为 **信息与内容工程系统**
- `content-system/` 明确为唯一主库
- `SKILL.md` 与内容系统说明已按新口径更新

当前尚未执行的是**硬迁移**：

- 本地目录名暂时仍为 `wechat-article-writing`
- GitHub 仓库名暂时仍未改名
- 旧路径仍然保留，用于兼容现有脚本、Obsidian 接入和 Git 同步链路

## 目录结构

- `SKILL.md`：skill 定位、工作规则、路由和协作原则
- `references/`：写作方法、口播脚本、审校规则、共创流程等说明
- `content-system/`：唯一主内容库

## Content System

`content-system/` 是这套系统的单一真相源。

核心目录：

- `01-选题库/`：选题积压、线索、规划
- `02-已发布/`：已发布文章和关键发布资产
- `03-素材库/`：素材包、案例、钩子、金句、认知表达、结构资产
- `04-方法论/`：模板、框架、工作流、迭代记录

## Obsidian Relationship

Obsidian 是查看和编辑界面，不是第二套独立数据库。

规则：

1. 先写入 `content-system/`
2. 再让 Obsidian 映射这套主库
3. 不再维护平行的第二套选题库或素材库

## Migration Note

当前仓库路径仍然是：

`~/.agents/skills/wechat-article-writing`

但从定位和使用方式上，它已经按下面这个名字来理解：

`information-content-engineering`

后续等仓库状态干净、脚本引用和 GitHub 侧准备好后，再执行目录名和仓库名的硬迁移。
