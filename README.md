# 数学建模工作区

三人协作请先阅读 [协作入口](START_HERE.md)，其中包含分工、交接模板和资料共享规则。

| 目录 | 用途 |
| --- | --- |
| 01_Problem | 题目、要求与提交规则 |
| 02_References | 文献、教材与参考资料 |
| 03_Data | 原始数据与处理后的数据 |
| 04_Code | 数据处理、建模与绘图代码 |
| 05_Results | 图表、模型输出与实验结果 |
| 06_Paper | 论文正文、附件与提交版本 |
| 07_Notes | 学习笔记、讨论与任务记录 |

## 开始使用

1. 在新开的 PowerShell 中运行 `python --version` 和 `git --version`。
2. Python 可用后，可在本目录运行 `python -m venv .venv`。
3. 使用 `.\.venv\Scripts\python.exe -m pip install 包名` 安装需要的包。
4. 在 Codex 中选择此文件夹作为项目。

## Git 与隐私

仓库包含入门文件、协作说明与空白模板，以及七个目录的 `.gitkeep` 占位文件；代码需逐项审查后添加。
题目、参考资料、数据、结果、论文和笔记默认忽略；本地 Git 仓库不会自动上传。
添加文件前先检查 `git status` 与 `git diff --cached`。
未经用户明确确认，不上传私人资料、团队资料、密钥或受限制的数据。
Git 不保存空目录，因此使用 `.gitkeep` 保留目录结构；占位文件不包含题目或数据。
