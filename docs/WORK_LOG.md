# ChopTree · 工作记录与交接日志

前置：[WORKFLOW.md](./WORKFLOW.md) → 对应需求 / 决策 / 代码。
这里记「做了什么、证据是什么、下一步是什么」，不是聊天全文记录。

## 2026-11-15 — 首版 AI 项目记忆工作流

- **任务：** 在已有 `docs/` 基础上搭建固定入口、状态导航、流程分支、主动判断记录重要信息、候选想法与验证交接机制。
- **依据：** 用户明确批准开始搭建，并要求 AI 主动决定记录内容，不把责任转嫁给用户。
- **已创建文件：** `START_HERE.md`、`WORKFLOW.md`、`IDEAS_INBOX.md`、`REQUIREMENTS.md`、`DECISIONS.md`、`PROJECT_STATUS.md`、`WORK_LOG.md`；`README.md` 更新导航。
- **验证口径：** GitHub 文件与最新 `main` 提交为准。提交成功不等于已配置 ChatGPT 项目指令或已完成跨会话演练。
- **剩余事项：** 将启动规则加入 ChatGPT「砍树游戏」项目指令；从新对话执行一次冷启动演练；具体玩法与源码结构尚未确定。
- **交接入口：** [START_HERE.md](./START_HERE.md) → [PROJECT_STATUS.md](./PROJECT_STATUS.md)。
- **注意：** 本记录于建设期间写入；最新 GitHub SHA 与最终写入验证应由执行者核对，不凭文档预先宣称成功。

## 后续任务记录模板

### YYYY-MM-DD — 任务名
- 任务目标 / 关联需求：
- 处理分支和文件：
- 已做 / 尚未做：
- 测试方法、结果及未覆盖范围：
- GitHub 提交 SHA（已核验才填写）：
- 是否触发部署、是否验证生产页面：
- 阻塞与待用户确认：
- 下一步可执行动作及入口文档：

**下一步：** [PROJECT_STATUS.md](./PROJECT_STATUS.md) 更新当前状态。
