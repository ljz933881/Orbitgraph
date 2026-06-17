# Orbitgraph

Obsidian 双环同心圆知识图谱插件 —— **内环知识点、外环题目**，Canvas + d3-force 渲染，可选 AI 批改回路。当前版本 v1.0.0。

## 安装（手动三件套）

1. 下载本仓库的 `main.js`、`manifest.json`、`styles.css` 三个文件。
2. 放进你的库：`<vault>/.obsidian/plugins/orbitgraph/`（目录不存在就新建）。
3. Obsidian → 设置 → 第三方插件 → 启用 **Orbitgraph**。

> 也可用 **BRAT**：安装 BRAT 后添加 `ljz933881/Orbitgraph`。

## 依赖

| 功能 | 需要 |
|---|---|
| 知识图谱 | Obsidian 1.4.0+ |
| 主页仪表盘 | 社区插件 **Dataview**（插件会自动开启它的 JavaScript 查询） |
| AI 批改（可选） | Claude 对话插件（如 Claudian）+ 系统安装 Claude Code CLI（仅桌面端） |

## 怎么建库

按 [建库规则.md](建库规则.md) 组织你的库（字段、目录、命名约定），插件会自动识别、连线、上色、统计——**不限学科**，会计/法考/英语/医学/编程都行。

## 许可证

[Apache-2.0](LICENSE)
