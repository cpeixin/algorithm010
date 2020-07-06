# 刷题进度表

<a name="5W7xp"></a>
### 切题四件套
- Clarification
- Possible solutions
- compare (time/space)
- optimal（加强）
- Coding（多写）
- Test cases
<a name="nZ4ED"></a>
### 五毒练习法

- 刷题第一遍 5 分钟：读题 + 思考（最多不要超过 15 分钟）,直接看解决：注意！多解法，比较解法优劣（如何 15 分钟后依旧没思路的情况下） 背诵、默写好的解法（这一步很重要）<br />
- 刷题第二遍 将每种解法写一遍（闭卷），反复 Debug，直到代码在 LeetCode 上执行通过,对多种解法之间的优劣进行体会、优化.总结及反思自己写的时候遇到的一些问题<br />
- 刷题第三遍 时隔一天后，再重复做题,对于不同解法的熟练程度进行专项练习<br />
- 刷题第四遍：时隔一周后，反复回来练习相同的题目<br />
- 刷题第五遍：面试前一周进行恢复性训练<br />
<a name="ydb68"></a>
### 刷题核心思想和误区

- 思想 重复刷题至少刷 5 遍
- 优化方法：空间换时间、升维（二维）
- 误区：做题只做一遍
<a name="3OsXA"></a>
### 


<a name="lb9v2"></a>
### 时间复杂度
<a name="6jRUU"></a>
### ![20180928135003419.png](https://cdn.nlark.com/yuque/0/2020/png/1072113/1594023601960-34ee7c5c-3201-45b3-93ec-5b5e6fe3faf7.png#align=left&display=inline&height=525&margin=%5Bobject%20Object%5D&name=20180928135003419.png&originHeight=525&originWidth=990&size=94052&status=done&style=none&width=990)
<a name="2PHzv"></a>
### 
<a name="Y0gxG"></a>
### 数据结构时间复杂度
<a name="fbnh9"></a>
### ![1592554431322-a01740ce-a5e4-4496-b2a0-a7130a6f607c.jpeg](https://cdn.nlark.com/yuque/0/2020/jpeg/1072113/1594023723145-97aa641b-584b-4f72-8e42-ec524a21248d.jpeg#align=left&display=inline&height=829&margin=%5Bobject%20Object%5D&name=1592554431322-a01740ce-a5e4-4496-b2a0-a7130a6f607c.jpeg&originHeight=829&originWidth=1440&size=239867&status=done&style=none&width=1440)
<a name="oj7RK"></a>
### 
<a name="gtQ1q"></a>
### 递归时间复杂度
![v2-6b854efd30ba33dbd1d758605fbf7c44_1440w.jpg](https://cdn.nlark.com/yuque/0/2020/jpeg/1072113/1594050010167-45bba720-6fa2-4c00-bc34-75b3765da6e2.jpeg#align=left&display=inline&height=669&margin=%5Bobject%20Object%5D&name=v2-6b854efd30ba33dbd1d758605fbf7c44_1440w.jpg&originHeight=669&originWidth=1440&size=92869&status=done&style=none&width=1440)<br />

<a name="gZhuH"></a>
### 
<a name="AftUg"></a>
### 题型总结
[团灭买卖股票问题（python）实现](https://github.com/cpeixin/leetcode-bbbbrent/blob/master/dp/%E5%9B%A2%E7%81%AD%20LeetCode%20%E8%82%A1%E7%A5%A8%E4%B9%B0%E5%8D%96%E9%97%AE%E9%A2%98.md)<br />[团灭二分查找](https://github.com/cpeixin/leetcode-bbbbrent/blob/master/binary_search/%E5%9B%A2%E7%81%AD%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE.md)<br />
<br />

<a name="DT5Nt"></a>
### 刷题列表
| 题目 | 首刷时间 | 最近刷时间 | 毒*n | 备注 |
| :---: | :---: | :---: | :---: | :---: |
|[两数之和](https://leetcode-cn.com/problems/two-sum/)| 2020-06-06 | 2020-07-06 | ✅✅✅ | dict |
| <a name="10f63edd"></a> [旋转数组](https://leetcode-cn.com/problems/rotate-array/)| 2020-06-12 | 2020-07-06 | ✅✅✅ | k = k%len(nums)<br />三段翻转 |
| <a name="b2da4b50"></a>[杨辉三角 II](https://leetcode-cn.com/problems/pascals-triangle-ii/)| 2020-06-06 | 2020-07-06 | ✅✅ | 貌似正解是利用动态规划来实现 |
| <a name="49f70b28"></a>[杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/)| 2020-06-06 | 2020-07-06 | ✅✅ |  递归递归<br />res.append([1]+[res[-1][i-1]+res[-1][i] for i in range(1, numRows-1)]+[1]) |
| <a name="d8935536"></a>[反转字符串](https://leetcode-cn.com/problems/reverse-string/)| 2020-02-07 | 2020-07-06 | ✅✅✅ | 递归，双指针。要求空间复杂度为O(1)，则只能用双指针实现 |
| <a name="c82ed90b"></a>[二叉树的后序遍历](https://leetcode-cn.com/problems/binary-tree-postorder-traversal/)| 2020-06-06 | 2020-07-06 | ✅✅ | 涉及到打印，所以引入辅助函数helper(root, res) |
| <a name="a080b4fa"></a>[交换和](https://leetcode-cn.com/problems/sum-swap-lcci/)| 2020-07-06 | 2020-07-06 | ✅ |  |
| [分发饼干](https://leetcode-cn.com/problems/assign-cookies/) | 2020-07-02 | 2020-07-02 | ✅ |  |
| [买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/) | 2020-07-03 | 2020-07-04 | ✅✅ |  |
| [验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/) | 2020-06-26  | 2020-07-03 | ✅✅✅✅✅ |  |
| [二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | 2020-06-26  | 2020-07-03 | ✅✅✅✅✅✅ |  |
| [买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/) | 2020-07-03 | 2020-07-03 | ✅✅ |  |
| [买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii/) | 2020-07-03 | 2020-07-03 | ✅✅ |  |
| [最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | 2020-07-04 | 2020-07-04 | ✅ |  |
| [买卖股票的最佳时机含手续费](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | 2020-07-04 | 2020-07-04 | ✅ |  |
| [买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) | 2020-07-04 | 2020-07-04 | ✅ |  |
| <a name="8e25c1ab"></a>[x 的平方根](https://leetcode-cn.com/problems/sqrtx/)| 2020-07-05 | 2020-07-05 | ✅ |  |
| <a name="56c24d16"></a>[有效的完全平方数](https://leetcode-cn.com/problems/valid-perfect-square/)| 2020-07-05 | 2020-07-05 | ✅✅ |  |
| <a name="a1eddbab"></a>[搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/)| 2020-07-06 | 2020-07-06 | ✅ |  |
| <a name="832674da"></a>[部分排序](https://leetcode-cn.com/problems/sub-sort-lcci/)| 2020-07-06 | 2020-07-06 | ✅ |  |



