# 学习笔记目录

这个文件夹整理了每天的 Jupyter Notebook。每个 notebook 开头都补充了中文说明，方便老师直接了解当天学了什么。

## Day 1：NumPy ndarray 基础

文件：[`Day1_NumPy_ndarray基础.ipynb`](Day1_NumPy_ndarray基础.ipynb)

主要学习 NumPy 的 ndarray 基础。内容包括数组创建、数组属性、数据类型、常用创建函数、矩阵创建和随机数生成。

## Day 2：NumPy 数组操作与常用函数

文件：[`Day2_NumPy数组操作与常用函数.ipynb`](Day2_NumPy数组操作与常用函数.ipynb)

主要学习 ndarray 的实际操作。内容包括索引、切片、条件筛选、广播、矩阵乘法、数学函数、统计函数、比较函数、排序、去重、拼接、拆分和 reshape。

## Day 3：Pandas Series 与 DataFrame 基础

文件：[`Day3_Pandas_Series与DataFrame基础.ipynb`](Day3_Pandas_Series与DataFrame基础.ipynb)

主要学习 Pandas 的基础结构。内容包括 Series 的创建、自定义索引、数据访问、缺失值检查、去重、排序、分位数、时间序列，以及 DataFrame 的基本创建。

## Day 4：Pandas 数据导入、清洗与分箱

文件：[`Day4_Pandas数据导入清洗与分箱.ipynb`](Day4_Pandas数据导入清洗与分箱.ipynb)

主要学习 Pandas 更接近实际数据处理的内容。内容包括读取 CSV 和 JSON、导出 CSV、缺失值处理思路、数据类型转换、数据变形、数据分箱、时间戳处理和 groupby 分组聚合。

## 练习数据

Day 4 使用的数据文件放在 [`pandas_import_data/`](pandas_import_data/)。

这些文件用于练习：

- `sales_basic.csv` 和 `sales_data.csv`：CSV 导入。
- `products.json`：JSON 导入。
- `students_missing.csv`：缺失值处理。
- `type_conversion_practice.csv`：数据类型转换。
- `events.jsonl`：JSON Lines 数据。
- `new.csv`：练习导出 CSV 时生成的数据。
