# [1565. 按月统计订单数与顾客数](https://leetcode-cn.com/problems/unique-orders-and-customers-per-month)

[English Version](/solution/1500-1599/1565.Unique%20Orders%20and%20Customers%20Per%20Month/README_EN.md)

## 题目描述

<!-- 这里写题目描述 -->

<p>表：<code>Orders</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| order_id      | int     |
| order_date    | date    |
| customer_id   | int     |
| invoice       | int     |
+---------------+---------+
order_id 是 <strong>Orders </strong>表的主键<sub>。</sub>
这张表包含顾客(customer_id)所下订单的信息<sub>。</sub>
</pre>

<p>写一个查询语句来 <strong>按月 </strong>统计 <strong>金额大于 $20 </strong>的唯一 <strong>订单数</strong> 和唯一 <strong>顾客数 。</strong></p>

<p>查询结果无排序要求。</p>

<p>查询结果格式如下面例子所示：</p>

<pre>
<code>Orders</code>
+----------+------------+-------------+------------+
| order_id | order_date | customer_id | invoice    |
+----------+------------+-------------+------------+
| 1        | 2020-09-15 | 1           | 30         |
| 2        | 2020-09-17 | 2           | 90         |
| 3        | 2020-10-06 | 3           | 20         |
| 4        | 2020-10-20 | 3           | 21         |
| 5        | 2020-11-10 | 1           | 10         |
| 6        | 2020-11-21 | 2           | 15         |
| 7        | 2020-12-01 | 4           | 55         |
| 8        | 2020-12-03 | 4           | 77         |
| 9        | 2021-01-07 | 3           | 31         |
| 10       | 2021-01-15 | 2           | 20         |
+----------+------------+-------------+------------+

Result 表：
+---------+-------------+----------------+
| month   | order_count | customer_count |
+---------+-------------+----------------+
| 2020-09 | 2           | 2              |
| 2020-10 | 1           | 1              |
| 2020-12 | 2           | 1              |
| 2021-01 | 1           | 1              |
+---------+-------------+----------------+
在 2020 年 09 月<sub>，</sub>有 2 份来自 2 位不同顾客的金额大于 $20 的订单<sub>。</sub>
在 2020 年 10 月<sub>，</sub>有 2 份来自 1 位顾客的订单<sub>，</sub>并且只有其中的 1 份订单金额大于 $20 <sub>。</sub>
在 2020 年 11 月<sub>，</sub>有 2 份来自 2 位不同顾客的订单<sub>，</sub>但由于金额都小于 $20 <sub>，</sub>所以我们的查询结果中不包含这个月的数据<sub>。</sub>
在 2020 年 12 月<sub>，</sub>有 2 份来自 1 位顾客的订单<sub>，</sub>且 2 份订单金额都大于 $20<sub> 。</sub>
在 2021 年 01 月<sub>，</sub>有 2 份来自 2 位不同顾客的订单<sub>，</sub>但只有其中一份订单金额大于 $20 <sub>。</sub>
</pre>


## 解法

<!-- 这里可写通用的实现逻辑 -->

<!-- tabs:start -->

### **Python3**

<!-- 这里可写当前语言的特殊实现逻辑 -->

```python

```

### **Java**

<!-- 这里可写当前语言的特殊实现逻辑 -->

```java

```

### **...**

```

```

<!-- tabs:end -->