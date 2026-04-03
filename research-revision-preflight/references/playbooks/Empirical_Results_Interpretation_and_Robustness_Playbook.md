---
created: 2026-04-03
updated: 2026-04-03
tags:
  - status/active
  - type/method_note
  - topic/results
  - topic/robustness
summary: 围绕 methods/results 的 3C、交互效应解释、稳健性、异常值与异质性的可复用方法论笔记。
---

# Empirical results、interpretation 与 robustness playbook

## 一句话原则

结果部分不是“把显著性倒出来”，而是要清楚回答：我检验了什么、发现了什么、这意味着什么、哪些解释还站不住。

## Methods 部分的 3C

- `Completeness`
  数据如何获得、为何这样收、变量如何构造、分析如何执行，都要交代完整。
- `Clarity`
  构念、编码、模型、样本和时间窗口要让读者一眼看懂。
- `Credibility`
  要说明为什么这套方法、样本和控制变量能合理支撑当前研究问题。

## Results 部分的 3C

- `Completeness`
  报告均值、标准差、相关矩阵、样本量、分析单位和核心模型设定。
- `Clarity`
  每个假设都要明确对应到一条结果，而不是让读者自己猜。
- `Credibility`
  除了统计显著，还要处理经济意义、稳健性与可能的替代解释。

## 解释一个结果时至少要交代五件事

- 这一列模型到底在检验哪条理论关系？
- 方向与大小是否符合预期？
- 不确定性有多大，结论是否脆弱？
- 这个结果对理论理解改变了什么？
- 如果结果不支持假设，最合理的解释是什么？

## 交互效应最容易写坏的地方

- 没有先说清主效应，就直接讨论调节效应。
- 解释了调节变量对 Y 的直接影响，却没有解释它如何改变 `X -> Y` 的机制。
- 只报告交互项显著，不画边际效应图，不说明关系在什么区间翻转或增强。
- 把交互写成中介，或者把中介写成调节。

## 稳健性不是 kitchen sink

- 好的稳健性检验应针对“核心脆弱点”，而不是无差别堆模型。
- 常见稳健性包括：
  替代测量、样本重切、时间窗口变化、placebo、排除极端样本、不同估计器。
- 如果一个稳健性结果会改变你对主结论的理解，就不能把它藏在附录里一带而过。

## 异常值与异质性是理论机会

- 异常值不一定是脏数据，也可能是理论最有信息量的地方。
- 如果极端案例反复改变结果，先问它暴露了什么边界条件，而不是先删掉。
- 潜在异质性、子群体和不同反应路径，可能比“平均效应”更接近真实机制。

## 对面板和事件数据的额外提醒

- 不要只满足于“有固定效应”，还要解释动态关系本身是否有理论意义。
- 若研究依赖外生事件，结果部分要说明事件后效应如何展开，而不是只给一个平均系数。
- 如果存在 anticipation、滞后效应或处理强度差异，结果解读必须同步调整。

## 常见误区

- `p < .05` 就当成理论成功。
- 结果部分重复方法，讨论部分又重复结果，真正的意义始终没说。
- 稳健性检验很多，但没有一项对应最核心的质疑。
- 交互项显著就立刻上升到复杂理论，却没有交代基线机制。
- 遇到异常值先删，遇到异质性先平均。

## Connected notes

- [[Research_Playbook_Method_Map]]
- [[Research_Design_and_Identification_Playbook]]
- [[Construct_Measurement_and_Operationalization_Playbook]]
- [[Paper_Writing_and_Section_Design_Playbook]]
- [[Discussion_Practical_Implications_and_Endgame_Playbook]]
- [[research_playbook_word_notes_chunk_018]]
- [[research_playbook_word_notes_chunk_019]]
