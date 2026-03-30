# 🏗️ 系统设计教程（System Design Tutorial）

> 基于 [system-design-primer](https://github.com/donnemartin/system-design-primer) 仓库整理的系统设计中文教程。通俗易懂、循序渐进、图文并茂。

---

## 📖 什么是系统设计？

**系统设计**（System Design）是指设计一个能够满足特定需求的**大规模分布式系统**的过程。它涉及到如何选择合适的技术架构、如何处理海量数据、如何保证系统的可用性和扩展性等一系列关键决策。

> 🍕 **通俗比喻**：系统设计就像规划一座城市——你需要考虑道路（网络）、供水系统（数据流）、电力分配（负载均衡）、应急预案（容错机制）等方方面面，确保这座城市能够高效运转并承载不断增长的人口（用户）。

---

## 🎯 为什么要学习系统设计？

| 场景 | 说明 |
|------|------|
| 🏢 **技术面试** | Google、Meta、Amazon 等大厂面试必考 |
| 💼 **实际工作** | 架构设计能力是高级工程师的核心技能 |
| 🧠 **技术视野** | 理解全栈技术如何协同工作 |
| 📈 **职业发展** | 从"写代码"到"设计系统"的进阶 |

---

## 🗺️ 学习路线图

```mermaid
graph LR
    A[🚀 入门介绍] --> B[📊 可扩展性与性能]
    B --> C[🌐 网络基础设施]
    C --> D[🗄️ 数据库设计]
    D --> E[⚡ 缓存策略]
    E --> F[📨 异步与消息队列]
    F --> G[🔌 通信协议]
    G --> H[🔒 安全设计]
    H --> I[🏛️ 实战案例]
    I --> J[🧩 面向对象设计]
    J --> K[🎓 面试指南]
```

> 💡 **建议**：按照顺序学习效果最佳，每个章节都会引用前面学过的知识。

---

## 📚 目录

| 序号 | 章节 | 内容概要 |
|:---:|------|---------|
| 01 | [🚀 系统设计入门](./01-introduction/README.md) | 基本概念、设计原则、面试框架 |
| 02 | [📊 可扩展性与性能基础](./02-scalability/README.md) | 性能 vs 可扩展性、延迟 vs 吞吐量、CAP 定理 |
| 03 | [🌐 DNS、CDN 与负载均衡](./03-networking/README.md) | 域名系统、内容分发网络、负载均衡器 |
| 04 | [🗄️ 数据库设计](./04-database/README.md) | SQL vs NoSQL、主从复制、分片、联合 |
| 05 | [⚡ 缓存策略](./05-cache/README.md) | 缓存模式、更新策略、缓存穿透与雪崩 |
| 06 | [📨 异步处理与消息队列](./06-async/README.md) | 消息队列、任务队列、背压机制 |
| 07 | [🔌 通信协议](./07-communication/README.md) | HTTP、TCP/UDP、RPC vs REST |
| 08 | [🔒 安全设计](./08-security/README.md) | 加密、认证授权、常见攻击防护 |
| 09 | [🏛️ 系统设计实战案例](./09-system-design-cases/README.md) | Pastebin、Twitter、Web 爬虫等真实系统 |
| 10 | [🧩 面向对象设计](./10-oop-design/README.md) | LRU Cache、停车场、聊天系统等 |
| 11 | [🎓 面试指南与附录](./11-interview-guide/README.md) | 面试技巧、估算方法、学习资源 |

---

## ⏱️ 学习时间规划

| 计划 | 时长 | 适合人群 | 建议 |
|------|------|---------|------|
| 🏃 **短期冲刺** | 1-2 周 | 即将面试 | 重点学习第 1-5 章 + 第 11 章 |
| 🚶 **中期计划** | 3-4 周 | 有一定基础 | 全部章节 + 2-3 个实战案例 |
| 🧘 **长期深入** | 6-8 周 | 深入掌握 | 全部章节 + 所有案例 + 扩展阅读 |

---

## 📐 约定说明

本教程中使用以下约定：

- 📌 **重点概念**：需要特别关注的核心知识
- 💡 **小贴士**：实用的补充说明
- ⚠️ **注意事项**：常见的坑或误区
- 🍕 **通俗比喻**：用生活中的例子来解释技术概念
- 🔧 **代码示例**：可运行的示例代码
- 📊 **图表说明**：使用 Mermaid 绘制的架构图和流程图

---

## 📝 参考资料

- 📘 [System Design Primer (原始仓库)](https://github.com/donnemartin/system-design-primer)
- 📗 [Designing Data-Intensive Applications](https://dataintensive.net/)
- 📙 [System Design Interview - An Insider's Guide](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)

---

## 📜 许可协议

本教程内容基于 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) 发布。

---

> 🌟 *"好的系统设计不是一蹴而就的，而是在不断迭代中逐步演化的。"*
>
> *— 让我们开始这段学习之旅吧！*
