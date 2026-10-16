# 高级语言程序设计（C 语言）

**2026 秋季 · 26 份独立 C 语言练习**

[返回仓库首页](../README.md)

课程目录完整保留为 `2026秋季高级语言程序设计(C语言)/`，继续按练习来源与已有知识点分类。已整理的练习使用有含义的英文小写 `snake_case` 文件名；近期新增文件仍保留提交时的名称。下表列出全部当前源码，已有重命名记录继续保留，未重命名项标为「同现文件名」。

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

## 欧歌 · 循环结构初步

当前目录名保留为 `C语言结构循环初步/`。

| 中文题名 / 当前内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 读入 10 个整数，统计能被 3 整除且不能被 7 整除的个数 | [`数据统计.c`](./欧歌/C语言结构循环初步/数据统计.c) | 同现文件名 |
| 偶数求和（当前实现求严格小于 n 的正偶数和） | [`统计不大于n的偶数之和.c`](./欧歌/C语言结构循环初步/统计不大于n的偶数之和.c) | 同现文件名 |
| 阶乘累乘（当前使用 while） | [`计算n阶层-dowhile.c`](./欧歌/C语言结构循环初步/计算n阶层-dowhile.c) | 同现文件名 |
| 奇数分母倒数和：1 + 1/3 + … + 1/(2n−1) | [`计算分数之和-while.c`](./欧歌/C语言结构循环初步/计算分数之和-while.c) | 同现文件名 |
| 分数和：1/(1×2) + … + 1/(n×(n+1)) | [`计算分数之和for.c`](./欧歌/C语言结构循环初步/计算分数之和for.c) | 同现文件名 |

文件名不是正确性结论：偶数求和文件在循环前先执行 `n--`，与名称中的「不大于」存在边界差异；阶乘文件名带 `dowhile`，实际使用 `while`。这里按当前源码登记，尚未修改实现或补造题目要求，请结合原题核对。

## 超星练习

| 中文题名 / 内容 | 源码 | 原文件名 |
| :--- | :--- | :--- |
| 华氏温度转摄氏温度 | [`celsius.c`](./超星/celsius.c) | 同现文件名 |
| 前置 / 后置自增自减表达式 | [`temp.c`](./超星/temp.c) | 同现文件名 |
| 体积重量计算 | [`dimensional_weight.c`](./超星/dimensional_weight.c) | `DimensionalWeight.c` |
| 两整数求和（直接输出） | [`sum_two_integers_direct.c`](./超星/sum_two_integers_direct.c) | `asumb.c` |
| Hello World | [`hello_world.c`](./超星/hello_world.c) | `helloworld.c` |
| 交换两个整型变量 | [`swap_two_integers.c`](./超星/swap_two_integers.c) | `定义两个整型变量a和b.c` |
| 时间差计算 | [`time_difference.c`](./超星/time_difference.c) | `时间差计算.c` |
| 两整数求和（保存到 sum） | [`sum_two_integers_stored.c`](./超星/sum_two_integers_stored.c) | `计算aplusb.c` |

## 编译与提交

在仓库根目录执行，例如（Linux / macOS 或 Git Bash，已安装 GCC）：

```bash
mkdir -p build
gcc "2026秋季高级语言程序设计(C语言)/超星/hello_world.c" -o build/hello
./build/hello
```

输出放在已被 Git 忽略的 `build/` 目录。Windows PowerShell 的建目录与运行写法见[仓库首页](../README.md#开始使用)。

涉及 `sqrt`、`sin`、`exp` 等数学函数的程序，在部分 GCC 环境中需要在编译命令末尾添加 `-lm`。

请对照课程题目核对输入输出和边界条件。如课程要求固定提交文件名，提交时仍应遵循原要求；上表可用于查找原文件名。
