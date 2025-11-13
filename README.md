# 主流 AI 编程工具总览（更新至 2025-11）

> 本文档总结了 2025 年国内外较主流的 AI 编程工具，分为 GUI/IDE 类和 CLI/Terminal 类两大类别。  
> 定价为官方公开参考价，实际以各工具官网为准。

---

## 📱 一、GUI / IDE 集成工具

### 1.1 国际主流工具

| 工具名称 | 开发商 | 主要特性 | 支持 IDE / 形态 | 定价（参考） | 官网 |
|---------|--------|----------|------------------|--------------|------|
| **Cursor** | Anysphere | AI-first 代码编辑器，支持 Agent 模式、多文件重构、项目级理解，`@web` 联网搜索 | 独立 IDE（基于 VS Code 分支） | 免费 / Pro 约 $20/月起 | <https://cursor.com> |
| **GitHub Copilot** | GitHub / Microsoft / OpenAI | 最早爆火的 AI 编程助手，支持 30+ 语言，深度 GitHub 集成，行内补全 + 对话 + 类 Agent 工作流 | VS Code、JetBrains、Neovim 等 | 免费试用 / Pro $10/月 / Business $19+/月 | <https://github.com/features/copilot> |
| **Windsurf** | Windsurf（原 Codeium 团队） | AI-native IDE，内置 Cascade / Flow 等 Agent 工作流，适合长任务与大型重构 | 独立 IDE | 基础功能免费 / Pro 约 $15/月起 | <https://windsurf.com> |
| **Claude Code** | Anthropic | Terminal-first 的 agentic coding 工具，可在本地工程上执行多步自动修改，支持 MCP 工具与持久记忆 | CLI + VS Code 插件 + Web | 随 Claude 订阅：Pro $20/月，Max 最高约 $200/月 | <https://www.claude.com/product/claude-code> |
| **JetBrains AI Assistant** | JetBrains | 深度集成 IntelliJ / PyCharm / WebStorm 等 IDE，使用 JetBrains 自研 Mellum 等模型，支持代码生成、重构、文档问答 | JetBrains 全系 IDE | 订阅制：在 JetBrains 账号下单独购买 AI 套餐 | <https://www.jetbrains.com/ai-assistant> |
| **Amazon Q Developer** | Amazon AWS | AWS 生态优化的 AI 开发助手，支持代码生成、调试、基础设施 IaC、云服务问答，多代理工作流 | VS Code、JetBrains、AWS 控制台 / CloudShell | 有限免费额度 / 付费版约 $19/用户/月起 | <https://aws.amazon.com/q/developer> |

---

### 1.2 中国主流工具（桌面 / IDE）

| 工具名称 | 开发商 | 主要特性 | 支持 IDE / 形态 | 定价（参考） | 官网 |
|---------|--------|----------|------------------|--------------|------|
| **Trae** | 字节跳动 | 国内首批 AI 原生 IDE，多模态引擎（文本 + 图像），支持 Doubao / Claude / GPT，多文件 Agent 开发，公开报道月活 100 万+ | 独立 IDE（基于 VS Code） | 截至 2025-11：国内个人版使用免费（企业 / 海外版可能有独立定价） | <https://www.trae.cn> |
| **Qoder** | 阿里巴巴 | Agentic 编程平台，支持 Quest / Ask 模式、Repo Wiki 自动生成项目知识库、持续记忆，多智能体协同 | 独立 IDE | 公测阶段主要功能免费，正式版预计采用订阅制 | <https://qoder.com> |
| **通义灵码** | 阿里云 | 基于通义大模型，支持 200+ 编程语言；提供编程智能体，多文件批量修改、终端命令执行、MCP 服务配置 | VS Code、JetBrains、终端等 | 个人基础版永久免费 / 个人专业版及企业版为订阅制（个人专业版约 ¥59+/月） | <https://lingma.aliyun.com> |
| **CodeBuddy** | 腾讯云 | 混元 + DeepSeek 双引擎，全流程 AI IDE，Craft 智能体支持多文件改造与项目生成，腾讯内部报告中 50% 新增代码由其辅助 | VS Code、JetBrains、Visual Studio、Xcode 等 | 个人 / 旗舰版阶段性免费；企业专享版约 ¥158/人/月，10 人起购 | <https://copilot.tencent.com> |
| **豆包 MarsCode** | 字节跳动 | 编程助手 + Cloud IDE 双形态，整仓理解，内置云端开发环境和模板，支持多语言和主流 IDE 集成 | VS Code 插件、浏览器 Cloud IDE | 提供免费版与订阅版（企业版和高配资源按套餐计费） | <https://www.marscode.cn> |
| **文心快码（Baidu Comate）** | 百度 | 基于文心大模型，支持代码补全、重构、单元测试生成、代码问答及 CLI 辅助，企业实践中代码采纳率可达 50% 左右 | VS Code、JetBrains、Web、CLI | 基础功能免费；个人专业版与企业版采用订阅制（个人专业版约 ¥59+/月起） | <https://comate.baidu.com/zh> |

---

### 1.3 浏览器 / 云端开发环境

| 工具名称 | 开发商 | 主要特性 | 典型使用场景 | 官网 |
|---------|--------|----------|--------------|------|
| **Bolt.new** | StackBlitz | 基于 WebContainers 的浏览器内完整开发环境，可从自然语言 / 提示词生成全栈项目，一键预览与部署 | 全栈 Web 应用快速原型、Demo、技术分享 | <https://bolt.new> |
| **v0** | Vercel | “设计到代码”工具，可从自然语言描述或 Figma 设计稿生成 React / Next.js 组件，并与 Vercel 托管无缝集成 | 前端开发、营销页面、内部工具搭建、设计稿落地 | <https://v0.app> |
| **Replit** | Replit | 云端协作 IDE，内置托管与数据库，Replit AI / Ghostwriter 可生成、调试和部署代码，支持多人实时协作 | 教育、个人项目、小型 SaaS、远程协作开发 | <https://replit.com> |

---

## 💻 二、CLI / Terminal 工具

### 2.1 国际主流 CLI 工具

| 工具名称 | 开发商 | 主要特性 | 定价 / 许可 | 官网 |
|---------|--------|----------|-------------|------|
| **aider** | Aider-AI 社区 | 开源终端内 AI pair programming；自动 Git 提交与回滚、多文件编辑、仓库建图、Lint / 测试集成，支持 Claude / GPT / DeepSeek / 本地模型，提供语音输入 | 开源免费（Apache-2.0）；需自备 LLM API Key 或本地模型 | <https://github.com/Aider-AI/aider> |
| **Claude Code CLI** | Anthropic | 官方 CLI 形态，专注本地工程的多步自动修改，支持 MCP 服务器、持久记忆、工具调用，可与 VS Code 插件和 Web 端共享上下文 | 随 Claude Pro / Max / Team / Enterprise 订阅使用（约 $20–200/月档） | <https://www.claude.com/product/claude-code> |
| **Gemini CLI** | Google | 官方开源 CLI，用于调用 Gemini 2.x 系列模型，支持 Agent / MCP 扩展，可编排本地任务与远程工具 | 开源（Apache-2.0）；调用按 Google AI 计费（含一定免费额度） | <https://github.com/google-gemini/gemini-cli> |
| **Amazon Q Developer CLI** | Amazon AWS | 将 Amazon Q Developer 带到终端，支持自然语言运行命令、分析日志、生成 / 重构脚本，整合 Docker / Kubernetes / Git 等开发工作流 | CLI 工具本身免费；功能受 Amazon Q 订阅档位限制（约 $19/用户/月起） | <https://github.com/aws/amazon-q-developer-cli> |

---

### 2.2 中国 CLI 工具

| 工具名称 | 开发商 | 主要特性 | 定价 / 许可 | 官网 |
|---------|--------|----------|-------------|------|
| **Qoder CLI** | 阿里巴巴 | Qoder 的命令行形态，支持用自然语言驱动代码生成、重构与调试，兼容 MCP 扩展，可与 Qoder IDE 共享工程上下文 | 公测阶段免费，正式商用后预计与 Qoder IDE 统一订阅 | <https://qoder.com> |
| **CodeBuddy CLI（CodeBuddy Code）** | 腾讯云 | CodeBuddy 的终端形态，可在命令行中使用 Craft 智能体执行多文件改造、脚本生成与项目初始化，并与 IDE 插件共享企业知识库与权限体系 | 个人 / 旗舰版阶段性免费；企业专享版约 ¥158/人/月（10 人起购） | <https://copilot.tencent.com/cli> |

---

> 💡 提示：价格和功能变化比较频繁，建议在 README 里保留一行「以上信息仅供参考，以各工具官网为准」，后续有新版你可以直接在这个表格基础上继续增删行。
