# 高级语言程序设计（C 语言）

**2026 秋季 · 19 份独立 C 语言练习**

[返回仓库首页](../README.md)

课程目录完整保留为 `2026秋季高级语言程序设计(C语言)/`，继续按练习来源与已有知识点分类。文件名使用有含义的英文小写 `snake_case`；下表保留中文题名和原文件名，方便查找。

每个文件都有独立的 `main`，请单独编译。两份整数求和实现分别保留，文件命名不表示正确性评定。

## 欧歌 · 顺序结构

| 中文题名 / 内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 公式计算 | [`formula_calculation.c`](./欧歌/C语言顺序结构/formula_calculation.c) | `公式计算.c` |
| 字符输入 | [`character_input.c`](./欧歌/C语言顺序结构/character_input.c) | `字符输入.c` |
| 格式化输出 | [`formatted_output.c`](./欧歌/C语言顺序结构/formatted_output.c) | `格式化输出.c` |

## 欧歌 · 选择结构初步

| 中文题名 / 内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 一元二次方程求根 | [`quadratic_equation_roots.c`](./欧歌/C语言选择结构初步/quadratic_equation_roots.c) | `一元二次方程求根.c` |
| 三角形面积 | [`triangle_area.c`](./欧歌/C语言选择结构初步/triangle_area.c) | `三角形面积.c` |
| 倍数判断 | [`divisible_by_3_not_7.c`](./欧歌/C语言选择结构初步/divisible_by_3_not_7.c) | `倍数判断.c` |
| 字母大小写转换 | [`toggle_letter_case.c`](./欧歌/C语言选择结构初步/toggle_letter_case.c) | `字母大小写转换.c` |
| 求最大值 | [`max_of_three.c`](./欧歌/C语言选择结构初步/max_of_three.c) | `求最大值.c` |

## 欧歌 · 选择结构进阶

| 中文题名 / 内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 三角形判断 | [`triangle_classification.c`](./欧歌/C语言选择结构进阶/triangle_classification.c) | `三角形判断.c` |
| 分段函数计算 | [`piecewise_function.c`](./欧歌/C语言选择结构进阶/piecewise_function.c) | `分段函数计算.c` |
| 大小写字母转换 | [`toggle_letter_case.c`](./欧歌/C语言选择结构进阶/toggle_letter_case.c) | `大小写字母转换.c` |
| 成绩分等 | [`grade_classification.c`](./欧歌/C语言选择结构进阶/grade_classification.c) | `成绩分等.c` |
| 简单的计算器 | [`simple_calculator.c`](./欧歌/C语言选择结构进阶/simple_calculator.c) | `简单的计算器.c` |

## 超星练习

| 中文题名 / 内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 体积重量计算 | [`dimensional_weight.c`](./超星/dimensional_weight.c) | `DimensionalWeight.c` |
| 两整数求和（直接输出） | [`sum_two_integers_direct.c`](./超星/sum_two_integers_direct.c) | `asumb.c` |
| Hello World | [`hello_world.c`](./超星/hello_world.c) | `helloworld.c` |
| 交换两个整型变量 | [`swap_two_integers.c`](./超星/swap_two_integers.c) | `定义两个整型变量a和b.c` |
| 时间差计算 | [`time_difference.c`](./超星/time_difference.c) | `时间差计算.c` |
| 两整数求和（保存到 sum） | [`sum_two_integers_stored.c`](./超星/sum_two_integers_stored.c) | `计算aplusb.c` |

## 编译与提交

在仓库根目录执行，例如：

```bash
gcc "2026秋季高级语言程序设计(C语言)/超星/hello_world.c" -o hello
```

涉及 `sqrt`、`sin`、`exp` 等数学函数的程序，在部分 GCC 环境中需要在编译命令末尾添加 `-lm`。

请对照课程题目核对输入输出和边界条件。如课程要求固定提交文件名，提交时仍应遵循原要求；上表可用于查找原文件名。
