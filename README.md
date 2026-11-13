# 论文与书籍阅读记录

记录读什么、按什么顺序读、目前理解了什么，以及读后留下的问题和心得。

以中文笔记为主，保留论文原题、书籍版本、原文链接和关键图表位置。内容要点与个人心得分别记录，阅读状态随实际进度更新。

## 阅读专区

| 专区 | 入口 | 记录内容 |
| --- | --- | --- |
| 论文阅读 | [论文目录](#论文目录) · [主题阅读路线](reading-paths/neutral-atoms.md) | 论文顺序、关键图文、方法与证据、理解和心得 |
| 书籍阅读 | [书籍专区](books/README.md) · [书籍笔记模板](templates/book-note.md) | 章节顺序、阅读进度、概念与推导、习题和心得 |

**上传什么格式？** 日常笔记用 Markdown（`.md`），需要保留完整版式时再附 PDF。参见[文件格式与公式示例](docs/file-formats.md)。

## 从这里开始

- **当前主题：**[中性原子量子计算与编译](reading-paths/neutral-atoms.md)
- **正在阅读：**[纠缠原子阵列的相干输运](papers/neutral-atoms/2022-coherent-transport.md)
- **新增论文：**复制[论文笔记模板](templates/paper-note.md)，再补充下面的目录。
- **新增书籍：**从[书籍专区](books/README.md)进入，按书籍或章节整理笔记。

## 论文目录

| 顺序 | 论文 | 关注点 | 状态 | 阅读笔记 |
| --- | --- | --- | --- | --- |
| 01 | A quantum processor based on coherent transport of entangled atom arrays | 硬件原理、相干搬运、动态连接 | 在读 | [打开笔记](papers/neutral-atoms/2022-coherent-transport.md) |
| 02 | Atomique: A Quantum Compiler for Reconfigurable Neutral Atom Arrays | 量子比特映射、原子移动、并行调度 | 待读 | [打开笔记](papers/neutral-atoms/2024-atomique.md) |
| 03 | Reuse-Aware Compilation for Zoned Quantum Architectures Based on Neutral Atoms | 分区架构、量子比特复用、跨区搬运 | 待读 | [打开笔记](papers/neutral-atoms/2025-zac.md) |

当前收录论文 **3 篇**：在读 **1 篇**，待读 **2 篇**，读完 **0 篇**。书籍另见[书籍专区](books/README.md)。

## 阅读路线

| 主题 | 建议顺序 | 适合解决的问题 |
| --- | --- | --- |
| [中性原子量子计算与编译](reading-paths/neutral-atoms.md) | 相干搬运 → Atomique → ZAC | 从原子硬件的能力与约束，理解编译器为何这样设计 |

## 每篇笔记记什么

1. **基本信息：**论文出处、版本、原文与代码链接。
2. **阅读顺序：**先看哪些小节、图表和实验，再补哪些细节。
3. **论文要点：**作者解决的问题、方法、证据和局限。
4. **我的理解与心得：**用自己的话复述，记录认同、疑问和可借鉴的想法。
5. **下一步：**复读位置、要补的知识，以及与后续论文的联系。

## 如何维护

- 新增或更新笔记，参考[记录方法](CONTRIBUTING.md)。
- 阅读状态使用：**待读 → 在读 → 初读完成 → 复读中 → 读完**。
- “讲解过”与“已经理解”分别记录；完成理解检查并补充自己的总结后，再更新阅读状态。
- 原文使用 DOI、arXiv 或作者页面链接；本仓库保存阅读笔记。
- 排版后的个人笔记 PDF 可以放入 [exports](exports/README.md)；可编辑正文和原文定位链接放在 Markdown 中。

笔记起始日期：2026-11-13。
