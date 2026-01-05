<h1 align="center">Awesome Claude Skills</h1>

<p align="center">
  <strong>语言：</strong>简体中文 | <a href="./README.en.md">English</a>
</p>

<p align="center">
<a href="https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills">
  <img width="1280" height="640" alt="Composio banner" src="https://github.com/user-attachments/assets/adb3f57a-2706-4329-856f-059a32059d48">
</a>


</p>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
  <a href="https://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
  </a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square" alt="License: Apache-2.0" />
  </a>
</p>
<div>
<p align="center">
  <a href="https://twitter.com/composio">
    <img src="https://img.shields.io/badge/Follow on X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" />
  </a>
  <a href="https://www.linkedin.com/company/composiohq/">
    <img src="https://img.shields.io/badge/Follow on LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Follow on LinkedIn" />
  </a>
  <a href="https://discord.com/invite/composio">
    <img src="https://img.shields.io/badge/Join our Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord" />
  </a>
  </p>
</div>

面向中文社区的 Claude Skills 推荐列表，帮助在 Claude.ai、Claude Code 与 Claude API 中提升生产力。

> 想让技能连接 500+ 应用？试试 [Composio](https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills)。

## 目录

- [什么是 Claude Skills？](#什么是-claude-skills)
- [技能分类](#技能分类)
  - [文档处理](#文档处理)
  - [开发与代码工具](#开发与代码工具)
  - [数据与分析](#数据与分析)
  - [商业与市场](#商业与市场)
  - [沟通与写作](#沟通与写作)
  - [创意与多媒体](#创意与多媒体)
  - [效率与组织](#效率与组织)
  - [协作与项目管理](#协作与项目管理)
  - [安全与系统](#安全与系统)
- [快速开始](#快速开始)
- [创建技能](#创建技能)
- [贡献指南](#贡献指南)
- [资源](#资源)
- [许可证](#许可证)

## 什么是 Claude Skills？

Claude Skills 是可定制的工作流，教会 Claude 按照你的需求执行特定任务，在各个平台实现标准化和可复用的自动化。

## 技能分类

### 文档处理

- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - 创建、编辑、审阅 Word 文档，支持修订、批注与格式调整。
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - 提取文本、表格与元数据，支持合并和标注 PDF。
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - 阅读、生成并调整幻灯片布局与模板。
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - 电子表格公式、图表与数据转换。
- [Markdown to EPUB Converter](https://github.com/smerchek/claude-epub-skill) - 将 Markdown 和聊天摘要转成专业 EPUB 电子书。*By [@smerchek](https://github.com/smerchek)*

### 开发与代码工具

- [artifacts-builder](https://github.com/anthropics/skills/tree/main/web-artifacts-builder) - 使用 React、Tailwind、shadcn/ui 生成复杂的 claude.ai HTML artifact。
- [aws-skills](https://github.com/zxkane/aws-skills) - AWS 开发技能：CDK 最佳实践、成本优化 MCP 服务器、无服务/事件驱动架构。
- [Changelog Generator](./changelog-generator/) - 自动将 Git 提交转换成用户友好的更新日志。
- [Claude Code Terminal Title](https://github.com/bluzername/claude-code-terminal-title) - 为每个 Claude Code 终端窗口显示动态标题，便于区分。
- [D3.js Visualization](https://github.com/chrisvoncsefalvay/claude-d3js-skill) - 生成 D3 图表和交互式可视化。*By [@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay)*
- [FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) - 集成 ffuf 进行 Web 模糊测试并分析漏洞。*By [@jthack](https://github.com/jthack)*
- [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - 引导完成开发分支的选项和流程。
- [iOS Simulator](https://github.com/conorluddy/ios-simulator-skill) - 与 iOS 模拟器交互，支持测试和调试。*By [@conorluddy](https://github.com/conorluddy)*
- [MCP Builder](./mcp-builder/) - 指导用 Python 或 TypeScript 创建高质量 MCP 服务器以集成外部 API。
- [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - 按 Move 2024 检查表分析 Move 语言包的质量。
- [Playwright Browser Automation](https://github.com/lackeyjb/playwright-skill) - 让模型调用 Playwright 进行 Web 自动化测试。*By [@lackeyjb](https://github.com/lackeyjb)*
- [prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) - 总结提示工程技巧与说服策略。
- [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - 使用 PICT 生成配对测试用例并优化覆盖率。
- [Skill Creator](./skill-creator/) - 指导创建具备专长、工作流和工具整合的 Claude 技能。
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - 将任何文档网站在数分钟内转换为 Claude 技能。*By [@yusufkaraaslan](https://github.com/yusufkaraaslan)*
- [software-architecture](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) - 覆盖 Clean Architecture、SOLID 等软件设计模式。
- [subagent-driven-development](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) - 通过子代理分派任务并在检查点审查。
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - 在实现前先进行 TDD 开发流程。
...
- [Competitive Ads Extractor](./competitive-ads-extractor/) - 提取并分析竞品广告，洞察信息和创意。
- [Domain Name Brainstormer](./domain-name-brainstormer/) - 生成域名创意并检查 .com/.io/.dev/.ai 可用性。
- [Internal Comms](./internal-comms/) - 撰写公司内部沟通，包括更新、简报、FAQ 等。
- [Lead Research Assistant](./lead-research-assistant/) - 结合产品分析目标公司并提供外联策略。

### 沟通与写作

- [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - 提取网页全文和元数据。
- [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) - 通过结构化提问将想法打磨成熟设计。
- [Content Research Writer](./content-research-writer/) - 进行研究、补充引文、优化开头并逐节反馈。
- [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) - 协助规划家谱研究项目。
- [Meeting Insights Analyzer](./meeting-insights-analyzer/) - 分析会议记录中的行为模式与表达比例。
- [NotebookLM Integration](https://github.com/PleasePrompto/notebooklm-skill) - 在 Claude Code 中直接查询 NotebookLM，基于上传文档作答。*By [@PleasePrompto](https://github.com/PleasePrompto)*

### 创意与多媒体

- [Canvas Design](./canvas-design/) - 依据设计原则生成精美 PNG/PDF 作品。
- [imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - 使用 Gemini 生成 UI 草图、图标和插画。*By [@sanjay3290](https://github.com/sanjay3290)*
- [Image Enhancer](./image-enhancer/) - 提升图片分辨率、锐度和清晰度，适合演示与文档。
- [Slack GIF Creator](./slack-gif-creator/) - 为 Slack 优化的 GIF 生成器，支持尺寸校验与组合动画。
- [Theme Factory](./theme-factory/) - 将专业字体和配色应用到幻灯片、报告与落地页，内置 10 套主题。
- [Video Downloader](./video-downloader/) - 下载 YouTube 等平台视频，支持多格式和质量选项。
- [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - 抓取 YouTube 字幕并总结。

### 效率与组织

- [File Organizer](./file-organizer/) - 识别上下文、去重并提供更好的文件组织方案。
- [Invoice Organizer](./invoice-organizer/) - 自动整理发票收据，提取信息并统一命名。
- [kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) - 基于持续改进理念的多角度分析。
- [n8n-skills](https://github.com/haunchen/n8n-skills) - 让 AI 助手直接理解和操作 n8n 工作流。
- [Raffle Winner Picker](./raffle-winner-picker/) - 使用安全随机性选择抽奖获奖者，支持列表或表格。
- [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - 帮助基于反馈迭代下一步产品或学习方向。
- [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) - 将相关文档串联成知识网络并总结。

### 协作与项目管理

- [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - 自动化 Git 操作与仓库交互。
- [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - 评估实现方案并与规格对齐。
- [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - 识别失败测试并提出修复。

### 安全与系统

- [computer-forensics](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) - 数字取证分析与调查技巧。
- [file-deletion](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) - 安全删除文件与数据清理。
- [metadata-extraction](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) - 提取并分析文件元数据。
- [threat-hunting-with-sigma-rules](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) - 使用 Sigma 规则狩猎威胁并分析事件。

## 快速开始

### 在 Claude.ai 中使用技能

1. 点击聊天界面的技能图标 (🧩)。
2. 从市场添加技能或上传自定义技能。
3. Claude 会根据任务自动激活相关技能。

### 在 Claude Code 中使用技能

1. 将技能放入 `~/.config/claude-code/skills/`：
   ```bash
   mkdir -p ~/.config/claude-code/skills/
   cp -r skill-name ~/.config/claude-code/skills/
   ```

2. 验证技能元数据：
   ```bash
   head ~/.config/claude-code/skills/skill-name/SKILL.md
   ```

3. 启动 Claude Code：
   ```bash
   claude
   ```

4. 启动后技能会自动加载并在需要时激活。

### 通过 API 使用技能

使用 Claude Skills API 以编程方式加载和管理技能：

```python
import anthropic

client = anthropic.Anthropic(api_key="your-api-key")

response = client.messages.create(
    model="claude-3-5-sonnet-20241022",
    skills=["skill-id-here"],
    messages=[{"role": "user", "content": "Your prompt"}]
)
```

详细说明见 [Skills API 文档](https://docs.claude.com/en/api/skills-guide)。

## 创建技能

### 技能结构

每个技能是包含 `SKILL.md` 的文件夹，使用 YAML 前置区块：

```
skill-name/
├── SKILL.md          # 必需：技能说明与元数据
├── scripts/          # 可选：辅助脚本
├── templates/        # 可选：文档模板
└── resources/        # 可选：参考资料
```

### 基础模板

```markdown
---
name: my-skill-name
description: 简明描述技能作用与使用场景。
---

# My Skill Name

技能目的与能力的详细描述。

## 何时使用

- 用例 1
- 用例 2
- 用例 3

## 操作指南

[指导 Claude 执行此技能的详细步骤]

## 示例

[展示技能的真实使用示例]
```

### 最佳实践

- 聚焦具体、可重复的任务
- 包含清晰的示例与边界情况
- 以「写给 Claude」的方式编写说明
- 在 Claude.ai、Claude Code 与 API 全部测试
- 记录前置条件与依赖
- 提供错误处理指引

## 贡献指南

欢迎贡献！请阅读 [贡献指南](CONTRIBUTING.md)，内容包括：

- 如何提交新技能
- 技能质量标准
- Pull Request 流程
- 行为准则

### 快速贡献步骤

1. 确保技能来源于真实场景
2. 检查现有技能是否重复
3. 遵循技能结构模板
4. 在各平台测试技能
5. 提交包含清晰文档的 Pull Request

## 资源

### 官方文档

- [Claude Skills 概览](https://www.anthropic.com/news/skills) - 官方发布与特性
- [Skills 使用指南](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - 如何在 Claude 中使用技能
- [创建自定义技能](https://support.claude.com/en/articles/12512198-creating-custom-skills) - 开发指南
- [Skills API 文档](https://docs.claude.com/en/api/skills-guide) - API 集成
- [Agent Skills 博文](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - 工程实践解析

### 社区资源

- [Anthropic Skills 仓库](https://github.com/anthropics/skills) - 官方示例技能
- [Claude 社区](https://community.anthropic.com) - 讨论与分享
- [Skills Marketplace](https://claude.ai/marketplace) - 发现与共享技能

### 灵感与场景

- [Lenny's Newsletter](https://www.lennysnewsletter.com/p/everyone-should-be-using-claude-code) - 50 种 Claude Code 用法
- [Notion Skills](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) - Notion 集成技能

## 加入社区

- 想将 Composio 接入你的认证体系？[预约沟通](https://calendly.com/thomas-composio/composio-enterprise-setup)
- [关注 Twitter](https://x.com/composio)
- [加入 Discord](https://discord.com/invite/composio)

## 许可证

本仓库采用 Apache License 2.0。单个技能可能使用不同许可证，请查阅对应文件夹。

---

**说明**：Claude Skills 可在 Claude.ai、Claude Code 和 Claude API 间通用，让你的工作流在各平台保持一致。

- [AgentsKB](https://agentskb.com) - 以经过调研的答案升级你的 AI。
