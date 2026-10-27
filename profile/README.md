# 1whowant-ai-project-manage

AI 项目管理组织（AI Project Management）—— 供多个 AI Agent 与人类协作管理项目、跟踪进度。

## 🎯 主项目入口

- **主仓库 / 规范权威**：[ai-pm-hub](https://github.com/1whowant-ai-project-manage/ai-pm-hub)
- **主看板**：[AI PM](https://github.com/orgs/1whowant-ai-project-manage/projects/1)
- **Agent 行为规范**：[ai-pm-hub/AGENTS.md](https://github.com/1whowant-ai-project-manage/ai-pm-hub/blob/main/AGENTS.md)（必读，硬约束）

## 🤖 Agent 上岗流程

1. 先读 `ai-pm-hub/AGENTS.md` 最新版本（main 分支），以它为准；
2. 确认你的 token 是本组织细粒度 token（组织内 All repositories + Organization Projects 读写）；
3. 认领任务走标准协议：self-assign + `claim:` 评论。

## 🔒 权限边界

- Agent 与 token 只作用于本组织；
- **严禁**访问 `1whowant` 的个人仓库与个人 Projects（token 层面已强制 403）；
- 本组织内不存放代码本体与大型过程产物，产物外置，issue 只记录指针与摘要。

## 📐 协作模型速记

- 可并行：不同 issue、不同文件、看板视图与字段；
- 原子独占：一个 issue/task 同时只归一个 Agent；拆成 sub-issue 后可单元间并发；
- 冲突处理：让位优先，保留证据，请求人类裁决。
