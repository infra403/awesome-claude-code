# Awesome Claude Code

精选 Claude Code 资源集合：CLAUDE.md 模板、实用工具、编码规范与提示词，助力 AI 辅助开发。

## 目录

- [CLAUDE.md 模板](#claudemd-模板)
- [工具](#工具)
- [如何使用](#如何使用)
- [贡献指南](#贡献指南)
- [相关资源](#相关资源)

## 什么是 Claude Code？

[Claude Code](https://docs.anthropic.com/en/docs/claude-code) 是 Anthropic 官方推出的 CLI 工具，让 Claude 直接在你的终端中协助编程。通过 `CLAUDE.md` 配置文件，可以定义项目规范、约束和最佳实践，让 AI 更好地理解项目上下文。

## CLAUDE.md 模板

| 语言/框架 | 描述 | 链接 |
|-----------|------|------|
| **Golang** | Go 项目开发规范，包含工作流程、硬性规则、Uber Go Style Guide 最佳实践 | [查看](./templates/golang/CLAUDE.md) |

## 工具

> 即将推出，敬请期待...

<!--
| 工具名称 | 描述 | 链接 |
|----------|------|------|
| **示例工具** | 工具描述 | [查看](./tools/example/) |
-->

## 目录结构

```
awesome-claude-code/
├── templates/           # CLAUDE.md 模板
│   └── golang/
│       └── CLAUDE.md
├── tools/               # 实用工具和脚本
│   └── ...
└── README.md
```

## 如何使用

### 使用模板

1. 浏览 `templates/` 目录，选择适合你项目的模板
2. 复制 `CLAUDE.md` 到你的项目根目录
3. 根据项目需求进行定制
4. 使用 Claude Code 进行开发

### 使用工具

查看各工具目录下的 README 获取具体使用说明。

## 贡献指南

欢迎贡献你的模板和工具！

### 提交模板

1. Fork 本仓库
2. 在 `templates/` 下创建对应语言/框架的目录
3. 添加你的 `CLAUDE.md` 文件
4. 提交 Pull Request

### 提交工具

1. Fork 本仓库
2. 在 `tools/` 下创建工具目录
3. 添加工具代码和 README 说明
4. 提交 Pull Request

### 要求

- 内容清晰、结构完整
- 包含实际项目中验证过的内容
- 中文为主，适合国内开发者

## 相关资源

- [Claude Code 官方文档](https://docs.anthropic.com/en/docs/claude-code)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)

## License

MIT
