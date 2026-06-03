# openclaw-github: 个人 AI 工作空间

这是一个为 GitHub Copilot 长期服务设计的个人 AI 工作空间。

🤖 **身份**：GitHub Copilot，为 @ijiayiiii 长期服务  
📍 **模式**：不只回答问题，还要持续做事、积累记忆、维护进度  
💾 **核心理念**：文件即记忆，GitHub 仓库作为持久化工作空间

---

## 快速开始

如果你是第一次来到这个仓库，请按顺序阅读：

1. **[AGENTS.md](./AGENTS.md)** - 了解我是谁，我如何工作
2. **[MEMORY.md](./MEMORY.md)** - 查看长期原则、决策和经验
3. **[daily/](./daily/)** - 查看最近的进展

---

## 仓库结构

```
.
├── AGENTS.md                 # 我的身份与工作定义（核心）
├── MEMORY.md                 # 长期记忆和原则
├── memory/
│   ├── projects/            # 各项目进展
│   ├── learnings/           # 技术与经验笔记
│   └── decisions/           # 设计和决策记录
├── daily/                    # 每日日志（临时记录）
│   └── 2026-06-03.md
├── code/                     # 代码、脚本、工具
├── docs/                     # 文档、指南
└── README.md                 # 你在这儿
```

---

## 工作方式

### 单个对话的流程

```
🔄 START
  ↓
📖 检查 AGENTS.md & MEMORY.md 恢复身份和原则
  ↓
🔍 检查 memory/ 获取相关背景
  ↓
⚡ 执行用户任务
  ↓
💾 更新 memory/ 或 daily/ 记录进展
  ↓
✅ 提交变更
  ↓
🔄 END
```

### 记忆类型

| 类型 | 位置 | 用途 |
|-----|------|------|
| **长期记忆** | MEMORY.md | 工作原则、决策、经验 |
| **项目记忆** | memory/projects/ | 项目进展、依赖、里程碑 |
| **知识记忆** | memory/learnings/ | 技术笔记、最佳实践 |
| **决策记忆** | memory/decisions/ | 设计选择的权衡 |
| **临时记录** | daily/YYYY-MM-DD.md | 今日任务、进度 |

---

## 最后更新

- **2026-06-03**：初始化工作空间，创建核心文件（AGENTS.md, MEMORY.md, 首个日志）

---

**角色**：GitHub Copilot | **用户**：@ijiayiiii | **创建**：2026-06-03
