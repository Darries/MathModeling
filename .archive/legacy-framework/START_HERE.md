# 三人数学建模协作入口

本仓库用于共享经过审查的技能、代码、模型说明与论文交接材料。当前版本是协作框架，尚未包含真实题目、实验结果或论文。

原始目录说明见 [README.md](README.md)。团队从本页开始。

## 先完成这四件事

1. 三人各自使用自己的 GitHub 与 Codex 账号；仓库所有者邀请队友加入私有仓库。
2. 队友克隆仓库，在 Codex 中把下载后的 MathModeling 文件夹设为项目文件夹。
3. 阅读 [团队入门说明](00_Collaboration/TEAM_QUICKSTART.md) 和 [协作约定](00_Collaboration/WORKFLOW.md)，按阶段安排人类任务；建模、代码与论文由 Agent 配合 Skills 推进。
4. 阅读 [共享边界](00_Collaboration/SHARING.md)，确认本次允许共享的资料。七个目录通过 `.gitkeep` 占位文件保留，克隆后会自动出现。

## 工作入口

不知道先做什么时：先看进度，选一个小任务，复制任务模板填写；找到技能先登记候选，完成工作后写交接。不要把每个文件夹分给一个固定成员。

| 任务 | 文件 |
| --- | --- |
| 给组员的简单入门说明 | [TEAM_QUICKSTART.md](00_Collaboration/TEAM_QUICKSTART.md) |
| 新建任务、确认与交接 | [TASK_TEMPLATE.md](00_Collaboration/TASK_TEMPLATE.md) |
| 共享技能清单与接入规范 | [SKILL_GUIDE.md](00_Collaboration/SKILL_GUIDE.md) |
| 按八种用途查找或提交技能 | [技能分类目录](08_Skill_Candidates/README.md) |
| 记录数据、文献、图表及实验来源 | [SOURCE_TEMPLATE.md](00_Collaboration/SOURCE_TEMPLATE.md) |
| 记录 AI 的实际使用 | [AI_USAGE_TEMPLATE.md](00_Collaboration/AI_USAGE_TEMPLATE.md) |
| 检查成员的运行环境 | [ENVIRONMENT_CHECKLIST.md](00_Collaboration/ENVIRONMENT_CHECKLIST.md) |
| 分工、同步、评审与新队友接入 | [WORKFLOW.md](00_Collaboration/WORKFLOW.md) |
| 模型定义和选择理由 | [MODEL_HANDOFF.md](00_Collaboration/MODEL_HANDOFF.md) |
| 运行记录、实际结果、图表和验证 | [EXPERIMENT_HANDOFF.md](00_Collaboration/EXPERIMENT_HANDOFF.md) |
| 论文结构、证据追踪和核对 | [PAPER_HANDOFF.md](00_Collaboration/PAPER_HANDOFF.md) |
| 当前进度与关键决策 | [STATUS.md](00_Collaboration/STATUS.md) |
| 可共享材料与忽略规则 | [SHARING.md](00_Collaboration/SHARING.md) |
| 后续技能建设 | [SKILLS_PLAN.md](00_Collaboration/SKILLS_PLAN.md) |

所有“待填写”“未验证”均表示缺少证据，不可直接写成论文结论。交接模板一旦填入团队内容，提交和上传前必须重新审查并获得用户确认。

## 环境

需要 Git、可用的 Python 和 Codex。目前没有真实建模代码，因此尚未确定或安装项目依赖，也没有运行过模型实验。

```powershell
python --version
git --version
python -m venv .venv
```

如果 python 指向 Windows 占位入口，先修复本机 Python 配置，或使用本机真实安装路径。不要把某位队友的绝对路径写入公共运行脚本。后续依赖必须与实际代码一起验证和记录。
