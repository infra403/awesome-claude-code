# Awesome CLAUDE.md

精选 CLAUDE.md 模板、编码规范与提示词，助力 AI 辅助开发。

## 什么是 CLAUDE.md？

`CLAUDE.md` 是 Claude Code（Anthropic 官方 CLI 工具）的项目级配置文件。它定义了 AI 助手在特定项目中应遵循的规范、约束和最佳实践，让 Claude 更好地理解你的项目上下文并生成符合团队规范的代码。

## 模板列表

| 语言/框架 | 描述 | 链接 |
|-----------|------|------|
| **Golang** | Go 项目开发规范，包含工作流程、硬性规则、Uber Go Style Guide 最佳实践 | [查看](./templates/golang/CLAUDE.md) |

## 如何使用

1. 选择适合你项目的模板
2. 复制 `CLAUDE.md` 到你的项目根目录
3. 根据项目需求修改配置
4. 使用 Claude Code 进行开发

## 目录结构

```
templates/
├── golang/          # Go 语言模板
│   └── CLAUDE.md
├── python/          # Python 模板（欢迎贡献）
├── typescript/      # TypeScript 模板（欢迎贡献）
└── ...
```

## 贡献指南

欢迎提交你的 CLAUDE.md 模板！

1. Fork 本仓库
2. 在 `templates/` 下创建对应语言/框架的目录
3. 添加你的 `CLAUDE.md` 文件
4. 提交 Pull Request

### 模板要求

- 内容清晰、结构完整
- 包含实际项目中验证过的规范
- 中文为主，适合国内开发者

## 相关资源

- [Claude Code 官方文档](https://docs.anthropic.com/en/docs/claude-code)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)

## License

MIT
