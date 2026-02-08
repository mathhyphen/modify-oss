# Modify OSS - 开源软件修改助手

**智能选择模式，平衡效率与准确性**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🌍 语言

- [English](#english)
- [中文](#中文)

---

<a name="english"></a>
## English

### Overview

Modify OSS is an OpenClaw Skill that provides a systematic workflow for modifying open-source software configurations or code. It offers **three execution modes** to balance efficiency and accuracy.

### 🚀 Three Execution Modes

#### Mode 1: Quick Mode ⚡ (Token Efficient)
**When to use:**
- Software I've handled before (recorded in memory)
- Simple configuration changes (e.g., change port, toggle feature)
- Time-sensitive tasks with acceptable trial-and-error cost

**Process:**
1. Check memory/TOOLS.md for existing records
2. If exists → Reuse previous solution
3. If not → Try once based on experience
4. Success → Record to memory
5. Failure → Ask if switching to Standard Mode

**Token Cost:** ⭐ Low

#### Mode 2: Standard Mode 📋 (Balanced)
**When to use:**
- Unfamiliar software but relatively simple task
- Need to read key documentation but not deep architecture
- Want high success rate without too many tokens

**Process:**
1. Collect basic info (software, version, goal)
2. Read README + Configuration docs (key chapters only)
3. Create simplified plan (modification list + verification steps)
4. Execute and verify
5. Record key findings

**Token Cost:** ⭐⭐ Medium

#### Mode 3: Deep Mode 🔬 (Thorough)
**When to use:**
- Complex enterprise software (e.g., Kubernetes, OpenStack)
- Critical production environment, cannot afford mistakes
- Need deep understanding of software architecture

**Process:**
Full 5-phase workflow with comprehensive analysis

**Token Cost:** ⭐⭐⭐ High

### 📖 Usage

**Specify mode in your request:**

| Request | Mode | Action |
|---------|------|--------|
| "Quick fix..." / "Simple change..." | Quick | Check memory → Direct modify |
| "Help me config..." / "Modify..." | Standard | Read docs → Plan → Execute |
| "Deep analysis..." / "Thoroughly understand..." | Deep | Full 5-phase workflow |

### 📋 Workflow

1. **Info Collection** - Gather software details
2. **Learning** - Read documentation (level-based)
3. **Analysis** - Create modification plan
4. **Execution** - Modify and verify
5. **Knowledge** - Record to memory

### 🎯 Features

- ✅ **Smart Mode Selection** - Auto-choose based on familiarity
- ✅ **Token Efficient** - Reuse knowledge, avoid repetition
- ✅ **Safe & Reversible** - Always backup, easy rollback
- ✅ **Knowledge Building** - Learn once, use forever

---

<a name="中文"></a>
## 中文

### 概述

Modify OSS 是一个 OpenClaw Skill，提供系统化的开源软件配置/代码修改工作流程。提供**三种执行模式**以平衡效率与准确性。

### 🚀 三种执行模式

#### 模式 1: 快速模式 ⚡（省 Token）
**适用场景：**
- 我之前处理过的软件（memory 中有记录）
- 简单配置修改（如改端口号、开关功能）
- 时间紧急，愿意承担试错成本

**流程：**
1. 检查 memory/TOOLS.md 是否有记录
2. 有 → 直接复用方案
3. 无 → 凭经验尝试
4. 成功 → 记录到 memory
5. 失败 → 询问是否切换到标准模式

**Token 消耗：** ⭐ 低

#### 模式 2: 标准模式 📋（平衡）
**适用场景：**
- 不熟悉的软件但任务简单
- 需要阅读关键文档但不需要深入架构
- 希望一次成功但不想花太多 Token

**流程：**
1. 收集基本信息
2. 阅读 README + 配置文档（仅关键章节）
3. 制定简化方案
4. 执行并验证
5. 记录关键发现

**Token 消耗：** ⭐⭐ 中

#### 模式 3: 深度模式 🔬（完整）
**适用场景：**
- 复杂企业级软件（如 Kubernetes、OpenStack）
- 关键生产环境，不能出错
- 需要深入理解软件架构

**流程：**
完整的 5 阶段工作流程

**Token 消耗：** ⭐⭐⭐ 高

### 📖 使用方法

**在请求时指定模式：**

| 请求 | 模式 | 行动 |
|------|------|------|
| "快速改一下..." / "简单改个..." | 快速 | 查 memory → 直接改 |
| "帮我看看配置..." / "帮我修改..." | 标准 | 读文档 → 定方案 → 执行 |
| "详细分析一下..." / "彻底理解..." | 深度 | 完整 5 阶段流程 |

### 📋 工作流程

1. **信息收集** - 收集软件详情
2. **学习阶段** - 阅读文档（按级别）
3. **分析方案** - 制定修改计划
4. **执行验证** - 修改并验证
5. **知识沉淀** - 记录到 memory

### 🎯 特性

- ✅ **智能模式选择** - 根据熟悉度自动选择
- ✅ **Token 高效** - 复用知识，避免重复
- ✅ **安全可回滚** - 始终备份，易于回滚
- ✅ **知识积累** - 一次学习，终身使用

---

## 🔧 Installation

1. Copy `SKILL.md` to your OpenClaw skills directory
2. Restart OpenClaw gateway
3. Start using: "帮我用 modify-oss 修改 XXX 配置"

## 📝 License

MIT License - See [LICENSE](LICENSE)

## 🤝 Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md)

## 💡 Tips

**Token Optimization:**
- Quick Mode for familiar software
- Standard Mode for new but simple tasks
- Deep Mode for critical or complex tasks

**Remember:** Record everything to memory for future reuse!
