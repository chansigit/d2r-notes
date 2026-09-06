# 词计数的统计学:从一枚硬币到 Markov 链

*Word Count Statistics from i.i.d. to Markov*

一个词在随机字母序列里出现几次?它的均值、方差、高阶矩和分布是什么?当字母服从 Markov 链而非独立时,哪些结论保留、哪些要改?
这套笔记从硬币问题出发,一路推到 Markov 背景下的精确结果。起点是 D2R 论文
(Chen et al., *Bioinformatics* 35(22):4596–4606, 2019)中的 overlapping coefficient。

- `index.html` — 总目录
- `d2r_history.html` — A. overlapping coefficient 是怎么想出来的
- `d2r_theory.html` — B. i.i.d. 背景下的词计数理论(B0–B7)
- `d2r_iid_variance.html` — C. D2R 论文的 i.i.d. 处理与 Var[X(X−1)] 的精确闭式
- `d2r_markov.html` — D. Markov 背景下的词计数理论(D0–D7)
- `d2r_statistic.html` — E. 统计量:从配对数到 p 值(E0–E5)
- `d2r_discussion.html` — 题外话:统计量形式的讨论稿

纯静态 HTML,公式由 MathJax(CDN)渲染。直接用浏览器打开 `index.html` 即可。
