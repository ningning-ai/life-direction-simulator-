# 人生方向模拟推演师
### Life Direction Simulator

不是替你决定人生，  
而是帮你把几种可能的人生方向，提前推演一遍。

This is a life direction simulation project inspired by Odyssey Plan.  
It helps people turn vague life choices into clearer, more comparable, and more testable paths.

---

## 这是什么

**人生方向模拟推演师** 是一个基于 **Odyssey Plan / 人生设计思路** 构建的 AI Skill。

它不预测命运，不给宿命式答案，也不假装替你做决定。  
它做的事情是：

- 帮你梳理当前状态
- 帮你看清真实矛盾
- 帮你推演 3 条不同的人生路径
- 帮你比较每条路的吸引力、代价、风险
- 帮你设计 7 天 / 30 天的低成本验证动作

一句话说，它想解决的是：

> **很多人不是没有想法，而是想法太多，却没被推演清楚。**

---

## 这个项目为什么存在

我想把这个项目放在 GitHub 上，帮助和我一样迷茫的人。

很多时候，我们并不是真的没有方向，  
而是卡在这些问题里：

- 我到底是真的想换路，还是只是现在太累了？
- 我想要的，是更高的收入，还是更自由的生活？
- 我是不甘心，还是不适合？
- 我到底是在追求自己想要的人生，还是在完成别人眼中的“正确”？

比起一句“听从内心”，  
我更相信：**人生选择需要被推演。**

所以我做了这个项目。  
希望它能帮助更多人，把模糊的纠结，变成更清晰的路径。

---

## 它适合谁

这个项目适合：

- 正在职业转型的人
- 在婚姻、城市、事业之间摇摆的人
- 对现状不满意，但说不清真正想要什么的人
- 想用 AI 辅助重大人生选择的人
- 想把“脑内空转”变成“现实验证”的人

---

## 它不做什么

这个项目 **不是**：

- 算命工具
- 命运预测器
- 心理诊断工具
- 替你做决定的权威顾问
- 冲动辞职 / 冲动改变人生的鼓动器

它更像一个：

- 人生访谈师
- 路径推演师
- 风险分析师
- 原型实验教练

---

## 核心方法

项目默认推演 3 条路径：

### A线｜当前轨道深化版
继续沿着现在的主路径发展，但做优化、升级和重构。

### B线｜替代转向版
假设当前路径不成立，或者你主动切换到另一条现实可行的路。

### C线｜Wildcard 实验版
暂时放下外界评价、身份包袱和面子压力，尝试一条更真实、更有生命力的方向。

---

## 它会输出什么

每次推演通常会包含：

- 当前状态摘要
- 核心矛盾提炼
- 三条人生方向模拟
- 每条路径的 5 年主线
- 工作 / 生活 / 关系 / 健康 / 财务状态
- 每条路径的吸引力、代价、风险
- 第 3 年的一个普通一天模拟
- 横向比较
- 最值得先验证的方向
- 7 天 / 30 天低成本实验建议

---

## 仓库结构

```text
life-direction-simulator/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── skill/
│   ├── system-prompt.md
│   ├── welcome-message.md
│   ├── intake-questions.md
│   └── output-template.md
├── examples/
│   ├── case-career-shift.md
│   ├── case-city-choice.md
│   └── case-relationship-balance.md
├── docs/
│   ├── methodology.md
│   ├── boundaries.md
│   └── faq.md
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug-report.yml
    │   ├── improvement.yml
    │   └── share-your-story.yml
    └── pull_request_template.md
```

---

## 如何使用

### 方法一：直接复制 Prompt 使用
进入 `skill/system-prompt.md`，复制提示词到你常用的 AI 平台中使用。

### 方法二：按模块组合使用
你也可以拆开使用：

- `welcome-message.md`：欢迎语
- `intake-questions.md`：提问采集
- `output-template.md`：结构化输出模板

### 方法三：结合你自己的案例迭代
你可以根据自己的经历，补充案例、优化问题、调整输出结构。

---

## 示例问题

你可以拿这些问题开始：

- 我到底该不该转行？
- 我要不要离开现在的城市？
- 婚姻、事业、自由，怎么排优先级？
- 我现在的痛苦，是阶段性的，还是方向性的？
- 我想创业，但不知道这是真想做，还是不想上班了
- 我想换一种生活，但不知道该先试哪条路

---

## 项目边界

本项目用于 **人生方向模拟与决策辅助**。

它不用于：

- 命运预测
- 宿命论判断
- 心理诊断
- 替代心理咨询、医疗、法律、投资等专业意见

这个项目鼓励的是：

> **低成本验证，而不是高风险冲动决策。**

---

## 欢迎贡献

这个项目还在持续迭代中。

欢迎你通过以下方式参与：

- 提出更好的提问方式
- 优化输出模板
- 补充真实案例
- 增加边界说明
- 修正文案与结构问题
- 分享你的使用反馈

你可以通过 Issue 或 Pull Request 参与共建。

---

## 适合先从哪里开始

初次使用建议先看这 4 个文件：

- `skill/system-prompt.md`
- `skill/welcome-message.md`
- `skill/intake-questions.md`
- `skill/output-template.md`

---


---

Created and maintained by **ningning-ai**.

Built with a little of warmth for anyone trying to think more clearly about life choices.

## 一个小小的愿望

希望这个项目不能替你回答“人生的标准答案”，  
但至少能陪你把未来几种可能性，先认真推演一遍。

> **把人生选择，从纠结，变成推演。**


Created and maintained by **ningning**
