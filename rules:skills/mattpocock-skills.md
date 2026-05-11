# mattpocock/skills 项目说明

项目地址：<https://github.com/mattpocock/skills>

`mattpocock/skills` 是一个面向 AI 编程代理（如 Claude Code、Codex 等）的技能集合。  
它的目标不是“全流程接管开发”，而是通过一组小而可组合的技能，帮助工程师在真实项目中更稳地完成需求、排查问题和提升代码质量。

## 项目定位

- 强调工程基本功：对齐需求、测试反馈、调试方法、架构演进。
- 强调可组合：每个技能都专注一个场景，可按需搭配使用。
- 强调可迁移：技能设计尽量与模型无关，便于在不同代理环境中复用。

## 快速开始

1. 安装技能集合：

```bash
npx skills@latest add mattpocock/skills
```

2. 选择要安装的技能和目标代理。
3. 运行 `/setup-matt-pocock-skills` 完成仓库级配置（如 issue tracker、标签词汇、文档目录等）。

## 解决的常见问题

该仓库主要针对 AI 辅助开发中的四类典型问题：

1. **需求不对齐**：通过 `grill-me`、`grill-with-docs` 深挖需求与边界。
2. **表达冗长、术语混乱**：通过共享领域语言（如 `CONTEXT.md`）降低沟通成本。
3. **代码可用性差**：通过 `tdd`、`diagnose` 建立高频反馈回路。
4. **架构熵增过快**：通过 `to-prd`、`improve-codebase-architecture` 等技能持续治理。

## 技能分类（示例）

### Engineering（工程向）

- `diagnose`：系统化诊断与回归验证流程。
- `tdd`：红-绿-重构循环的测试驱动开发。
- `triage`：问题分诊状态机。
- `to-prd` / `to-issues`：从讨论沉淀需求并拆解为可执行任务。
- `improve-codebase-architecture`：识别并改进代码库的架构问题。

### Productivity（效率向）

- `caveman`：超精简沟通模式，降低 token 消耗。
- `grill-me`：通过追问澄清决策树。
- `write-a-skill`：快速编写新的技能模板。

### Misc（工具向）

- `git-guardrails-claude-code`：防止危险 Git 操作。
- `setup-pre-commit`：快速配置提交前检查。

## 适用场景

- 想把 AI 从“能写代码”提升到“能稳定协作”。
- 团队希望沉淀统一的 AI 开发工作流。
- 项目规模增长后，需要持续控制复杂度与变更风险。

## 一句话总结

`mattpocock/skills` 本质上是把资深工程实践打包成可复用的 AI 工作流指令集，帮助你在 AI 加速开发时保持可控性与工程质量。
