# ChopTree 项目文档

本目录是砍树游戏（ChopTree）的**统一文档存放位置**。

- **需求文档**：功能需求、玩法设计、变更需求与验收标准。
- **开发文档**：技术方案、架构说明、接口与数据结构、开发实现记录。
- **其他文档**：测试记录、缺陷修复、部署运维、版本发布说明以及决策记录。

## 文档约定

1. 后续新增的项目需求、开发及其他说明文档，统一放在仓库根目录的 `docs/` 下；需要时可按主题创建子目录。
2. 采用 Markdown（`.md`）为主；文件名应清晰、可检索，文档内容注明必要的背景、结论与更新时间。
3. 修改功能时，相关说明应同步更新，避免代码与文档不一致。
4. 不在仓库根目录分散放置项目文档；根目录仅保留确有必要的工程配置与入口文件。

## 项目信息

- 项目：ChopTree（纯 HTML5 砍树小游戏）
- GitHub 仓库：`119shenhao/choptree`
- 默认分支：`main`
- 部署平台：Cloudflare Pages（与 GitHub 关联）
- 用户提供的访问地址：https://3a24e45e.choptree.pages.dev/


## AI 项目管理 · 从固定入口开始

> **新对话第一步：** [START_HERE.md](./START_HERE.md) → [PROJECT_STATUS.md](./PROJECT_STATUS.md) → [WORKFLOW.md](./WORKFLOW.md) → 按任务进入对应文档。
>
> 这一入口需要同步写进 ChatGPT「砍树游戏」的项目指令，单靠 GitHub 文档本身不会自动启动 AI。

| 文件 | 职责 |
| --- | --- |
| [START_HERE.md](./START_HERE.md) | 新对话 / 新任务的固定阅读入口 |
| [PROJECT_STATUS.md](./PROJECT_STATUS.md) | 当前阶段、已完成事项、阻塞和下一步 |
| [WORKFLOW.md](./WORKFLOW.md) | 任务分流、自动判断记录内容、保存与提交核验 |
| [IDEAS_INBOX.md](./IDEAS_INBOX.md) | 可能重要但未确认的想法；不自动作为开发需求 |
| [REQUIREMENTS.md](./REQUIREMENTS.md) | 用户已确认的需求及其状态、验收条件 |
| [DECISIONS.md](./DECISIONS.md) | 已确定的架构、流程和技术决策 |
| [WORK_LOG.md](./WORK_LOG.md) | 实际执行、测试证据、中断恢复与交接记录 |

**主动记录规则：** 用户不必每次提醒「记下来」。AI 在明确决定或关键里程碑时及时保存；有价值但尚不确定的想法先记候选并按需询问，绝不当作已确定需求。每次提交须核验 GitHub 结果；无法保存时明确说明。不能依赖聊天结束自动触发后台保存。
