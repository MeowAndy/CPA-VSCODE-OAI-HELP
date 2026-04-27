# 更新日志

## cpa-vscode-oai-0.0.2 - 2026-04-27

### 新增

- 新增 `images/` 配图目录，加入 5 张自制 SVG 配图：
  - `01-architecture.svg`：CPA + VSCode + OAI 插件整体链路；
  - `02-install-flow.svg`：小白安装顺序；
  - `03-oai-config.svg`：OAI Provider 连接 CPA 的关键配置；
  - `04-model-picker.svg`：Copilot Chat 选择 OAI / CPA 模型流程；
  - `05-troubleshooting.svg`：常见问题排错顺序。
- README 新增“配图速览：先看图再操作”章节。
- README 增加知乎参考教程链接。

### 说明

- 用户提供的知乎页面当前对自动抓取返回 403，无法稳定获取原图；为避免误搬不可确认授权的图片，本仓库采用自制配图并保留原文链接。

## cpa-vscode-oai-0.0.1 - 2026-04-27

### 新增

- 初始化 `CPA-VSCODE-OAI-HELP` 教程仓库。
- 新增《CPA + VSCode + OAI Compatible Provider for Copilot 超级无敌小白教程》：
  - 解释 VSCode / Copilot Chat / OAI Compatible Provider / CPA / localhost；
  - 教小白安装 VSCode；
  - 教小白安装 GitHub Copilot / Copilot Chat；
  - 教小白安装 OAI Compatible Provider for Copilot；
  - 教小白安装、配置、登录并启动 CLIProxyAPI；
  - 教小白测试 `http://localhost:8317/v1/models`；
  - 教小白在 VSCode 中配置 Provider、Base URL、API Key、Model、API Mode；
  - 教小白在 Copilot Chat 中选择 OAI Compatible 模型；
  - 教小白第一次用 VSCode + CPA 解释代码、写代码、修 bug；
  - 补充 Windows / macOS / Linux 完整路线；
  - 补充 FAQ 与安全提醒。

### 安全

- 强调不要公开 CPA、不要泄露 API Key/token/cookie、不要上传配置目录。
