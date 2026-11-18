# 三人数学建模协作入口

本仓库用于共享经过审查的技能、代码、模型说明与论文交接材料。当前版本是协作框架，尚未包含真实题目、实验结果或论文。

原始目录说明见 [README.md](README.md)。团队从本页开始。

## 先完成这四件事

1. 三人各自使用自己的 GitHub 与 Codex 账号；仓库所有者邀请队友加入私有仓库。
2. 队友克隆仓库，在 Codex 中把下载后的 MathModeling 文件夹设为项目文件夹。
3. 阅读 [协作约定](00_Collaboration/WORKFLOW.md)，确定建模、代码、论文三个负责人。
4. 阅读 [共享边界](00_Collaboration/SHARING.md)，确认本次允许共享的资料。七个目录通过 `.gitkeep` 占位文件保留，克隆后会自动出现。

## 工作入口

| 任务 | 文件 |
| --- | --- |
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
