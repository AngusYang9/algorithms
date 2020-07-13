<h1 align="center" style="margin: 30px 0 35px;">JavaScript Algorithms</h1>
<p align="center">
  <a href="https://travis-ci.org/AngusYang9/algorithms"><img src="https://travis-ci.org/AngusYang9/algorithms.svg?branch=master" /></a>
</p>

[在线地址](https://www.90paw.com/javascript-algorithms)

算法是如何解决一类问题的明确规范。算法是一组精确定义操作序列的规则。

`B` - 初学者， `A` - 进阶

## 算法主题

### 数学：

- `B` [Bit 操控](/math/bits.html) - 位操作
- `B` [阶乘](/math/factorial.html) - `5! = 5 * 4 * 3 * 2 * 1 = 120`
- `B` [斐波那契数列](/math/fibonacci.html) - `0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...`
- `B` [素数检测](/math/primality-test.html) - 判断一个数是否为质数
- `B` [欧几里得算法](/math/euclidean.html) - 求两个数的最大公约数(GCD)
- `B` [最小公倍数](/math/least-common-multiple.html) - 求两个数的最小公倍数(LCM)
- `B` [素数筛](/math/sieve-of-eratosthenes.html) - 寻找 n 以下所有质数
- `B` [判断2次方数](/math/is-power-of-two.html) - 检测一个正整数是否是 `2` 的幂。
- `B` [杨辉三角形](/math/pascal-triangle.html)
- `B` [复数](/math/complex-number.html) - a + b * i 的形式，其中 i 为无解的虚数（`i^2 = −1`）
- `B` [弧度和角](/math/radian.html) -  圆的单位弧度 1rad = 圆半径大小的弧长对应的角；弧度`π` 等于角度 `180°`
- `B` [快速算次方](/math/fast-powering.html) - 幂次方复杂度由 O(n) 降为 O(log(n))
- `A` [整数拆分](/math/integer-partition.html)
- `A` [割圆术](/math/liu-hui.html)
- `A` [离散傅里叶变换](/math/fourier-transform.html)

### 集合：

- `B` [笛卡尔积](/sets/cartesian-product.html) - 多集合乘积生成的一个集合
- `A` [洗牌算法](/sets/fisher-yates.html) - 将有限序列 `随机排列` 的算法
- `A` [幂集](/sets/power-set.html) - 集合的所有子集
- `A` [排列](/sets/permutations.html) - 有/无重复排列
- `A` [组合](/sets/combinations.html) - 有/无重复组合
- `A` [最长公共子序列](/sets/longest-common-subsequence.html) - 最长公共子序列（LCS）
- `A` [最长递增子序列](/sets/longest-increasing-subsequence.html) - 最长递增子序列
- `A` [最短公共父序列](/sets/shortest-common-supersequence.html) - 最短公共父序列（SCS）
- `A` [背包问题](/sets/knapsack-problem.html) - 向固定容量的背包（容器）填充尽可能大的值
- `A` [最大子数列问题](/sets/maximum-subarray.html) - 数组中 `和最大` 的子数列
- `A` [组合求和](/sets/combination-sum.html) - `数列中总和等于目标值` 的所有可能的组合

### 字符串：

- `B` [汉明距离](/string/hamming-distance.html) - 两个等长字符串，对应位置的不同字符的个数
- `A` [莱温斯坦距离](/string/levenshtein-distance.html) - 两个字符串之间，由一个转成另一个所需的最少编辑操作次数。
- `A` [KMP 算法](/string//knuth-morris-pratt.html) - 子串搜索
- `A` [Z 算法](/string/z-algorithm.html) - 子串搜索
- `A` [Rabin Karp 算法](/string/rabin-karp.html) - 子串搜索（`哈希`，单一模式匹配）
- `A` [最长公共子串](/string/longest-common-substring.html) - 多个字符串的最长子串
- `A` [正则表达式匹配](/string/regular-expression-matching.html)

### 搜索：

时间复杂度效率排名：

① [插值查找](/search/interpolation-search.html) - `O(log(log(n)))`

② [二分查找](/search/binary-search.html) - `O(log(n))`

③ [跳跃查找/块查找](/search/jump-search.html) - `O(√n)`

④ [线性查找](/search/linear-search.html) - `O(n)`

描述：

- `B` [线性查找](/search/linear-search.html) - 遍历查找匹配的元素 `O(n)`
- `B` [跳跃查找/块查找](/search/jump-search.html) - 有序数组跳跃查找匹配的元素 `O(√n)`
- `B` [二分查找](/search/binary-search.html) - 有序数组二分查找匹配的元素 `O(log(n))`
- `B` [插值查找](/search/interpolation-search.html) - 有序数组依据`插值公式`定位查找 `O(log(log(n)))`

### 排序：

时间复杂度效率排名：

① [基数排序](/sorting/radix-sort.html) -  `O(n * k)`  k 为整数的位数

② [快速排序](/sorting/quick-sort.html) -  `O(nlog(n))`

② [归并排序](/sorting/merge-sort.html) -  `O(nlog(n))`

③ [希尔排序](/sorting/shell-sort.html) -  `O(n^(1.3—2))`

④ [冒泡排序](/sorting/bubble-sort.html) -  `O(n^2)`

④ [插入排序](/sorting/insertion-sort.html) -  `O(n^2)`

④ [选择排序](/sorting/selection-sort.html) -  `O(n^2)`

描述：

- `B` [冒泡排序](/sorting/bubble-sort.html) - `O(n^2)`
- `B` [快速排序](/sorting/quick-sort.html) - (递归)基于基数二分，大小各置一边 `O(nlog(n))`
- `B` [归并排序](/sorting/merge-sort.html) - (递归)拆分比较后合并 `O(nlog(n))`
- `B` [计数排序](/sorting/counting-sort.html) - (非比较型)适用于数值范围较小的整数排序 `O(n + r)` r 为数值最大与最小的差值
- `B` [基数排序](/sorting/radix-sort.html) - (非比较型)整数位数分隔，按位比较 `O(n * k)` k 为整数的位数
- `B` [插入排序](/sorting/insertion-sort.html) - 适用于少量元素排序 `O(n^2)`
- `B` [希尔排序](/sorting/shell-sort.html) - 按增量分组排序，每组执行插入排序 `O(n^(1.3—2))`
- `B` [选择排序](/sorting/selection-sort.html) - `O(n^2)`
- `B` [堆排序](/sorting/heap-sort.html)

![img](http://img.90paw.com/AngusYang9/2020-07-13%2016-12-59.png)
