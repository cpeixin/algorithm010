

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
| 题目 | 首刷时间 | 最近刷时间 | 毒*n | 复杂度 | 代码片段 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements/) | 2020-06-16 | 2020-07-07 | ✅✅ |  | heapq.heappush(heap, (-dict[key], key)) |
| [数对和](https://leetcode-cn.com/problems/pairs-with-sum-lcci/) | 2020-06-23 | 2020-07-07 | ✅✅ |  | if dict.get(target-num, 0) == 0<br />dict[num]+=1 |
| [两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs/) | 2020-06-07 | 2020-07-07 | ✅✅ |  | first_node.next = self.swapPair(second_node.next) |
| [两数之和](https://leetcode-cn.com/problems/two-sum/) | 2020-06-06 | 2020-07-06 | ✅✅✅ |  | dict |
| [旋转数组](https://leetcode-cn.com/problems/rotate-array/) | 2020-06-12 | 2020-07-06 | ✅✅✅ |  | k = k%len(nums)<br />三段翻转 |
| [杨辉三角 II](https://leetcode-cn.com/problems/pascals-triangle-ii/) | 2020-06-06 | 2020-07-06 | ✅✅ |  | 貌似正解是利用动态规划来实现 |
| [杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/) | 2020-06-06 | 2020-07-06 | ✅✅ |  |  递归递归<br />res.append([1]+[res[-1][i-1]+res[-1][i] for i in range(1, numRows-1)]+[1]) |
| [反转字符串](https://leetcode-cn.com/problems/reverse-string/) | 2020-02-07 | 2020-07-06 | ✅✅✅ |  | 递归，双指针。要求空间复杂度为O(1)，则只能用双指针实现 |
| [验证回文串](https://leetcode-cn.com/problems/valid-palindrome/) | 2020-06-20 | 2020-07-07 | ✅✅  |  | "".join(char.lower() for char in s if char.isalnum()) |
| [二叉树的前序遍历](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/) | 2020-06-06 | 2020-07-07 | ✅✅  |  |  |
| [二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/) | 2020-06-06 | 2020-07-07 |  |  |  |
| [二叉树的后序遍历](https://leetcode-cn.com/problems/binary-tree-postorder-traversal/) | 2020-06-06 | 2020-07-06 | ✅✅  |  | 涉及到打印，所以引入辅助函数helper(root, res) |
| [N叉树的后序遍历](https://leetcode-cn.com/problems/n-ary-tree-postorder-traversal/) | 2020-06-15 | 2020-07-07 | ✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：O(n) | for child in root.children:<br />     self.helper(root, res) |
| [N叉树的前序遍历](https://leetcode-cn.com/problems/n-ary-tree-preorder-traversal/) | 2020-06-15 | 2020-07-11 | ✅✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：O(n) | class Solution:<br />    def preorder(self, root: 'Node') -> List[int]:<br />        if not root: return []<br />        res, queue = [], [root]<br />        while queue:<br />            node = queue.pop()<br />            res.append(node.val)<br />            for child in node.children[::-1]:<br />                queue.append(child)<br />        return res |
| [N叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-n-ary-tree/) | 2020-06-25 | 2020-07-11 | ✅✅  | 时间复杂度：O(n)<br />空间复杂度：O(n) | if not root: return 0<br />if not root.children: return 1<br />return max(self.func(node) for node in root.children) + 1 |
| [从中序与后序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)<br /> | 2020-06-10 | 2020-07-10 | ✅✅✅ | 时间复杂度：O(n^2), index() 操作复杂度为O(n),遍历二叉树是O(n) 的。<br />空间复杂度：O(n)，要存储整棵树<br /> | if not inorder or not postorder: return None<br />root = TreeNode(postorder[-1])<br />root_index=inorder.index(postorder[-1])<br />root.left = self.fun(inorder[:root_index], postorder[:root_index])<br />root.right = self.fun(inorder[root_index+1:], postorder[root_index:-1]) |
| [从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 2020-06-10 | 2020-07-10 | ✅✅✅ | 时间复杂度：O(n^2), index() 操作复杂度为O(n),遍历二叉树是O(n) 的。<br />空间复杂度：O(n)，要存储整棵树<br /> | root.left = self.fun(preorder[1:root_index+1], inorder[:root_index])<br />root.right = self.fun(preorder[root_index+1], inorder[root_index+1:]) |
| [最大二叉树](https://leetcode-cn.com/problems/maximum-binary-tree/) | 2020-06-15 | 2020-07-07 | ✅✅✅ |  | python数组边界[ :max_num] [max_num+1: ] |
| [左叶子之和](https://leetcode-cn.com/problems/sum-of-left-leaves/) | 2020-06-15 | 2020-07-07 | ✅✅✅ |  | if root.left and not root.left.left and not root.left.right:<br />return root.left.val+self.func(root.right) |
| [翻转二叉树](https://leetcode-cn.com/problems/invert-binary-tree/) | 2020-06-20 | 2020-07-11 | ✅✅✅✅ | 时间复杂度：O(n) ,每个树节点只访问一次<br />空间复杂度：O(n)，调用栈n次 | if not root: return None<br />root.left, root.right = root.right, root.left<br />self.func(root.left)<br />self.func(root.right)<br />return root |
| [对称二叉树](https://leetcode-cn.com/problems/symmetric-tree/) | 2020-06-11 | 2020-07-11 | ✅✅✅✅ | 时间复杂度：O(n) ,每个树节点只访问一次<br />空间复杂度：O(n)，调用栈n次 | if not root: return True<br />def recur(left, right):<br />      if not left and not right: return True<br />      if not left or not right: return False<br />      if left.val != right.val: return False<br />      return self.recur(left.left, right.right) and self.recur(left.right, right.left)<br />return (root.left, root.right) |
| [路径总和](https://leetcode-cn.com/problems/path-sum/) | 2020-06-07 | 2020-07-07 | ✅✅✅ |  | if not root: return False<br />sum -= root.val<br />if not root.left and not root.right: return sum == 0<br />return self.haspath(root.left,sum) or self.haspath(root.right, sum) |
| [二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/) | 2020-06-07 | 2020-07-10 | ✅✅✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：最糟糕的情况下是二叉树不平衡，退化成一个链表，则调用栈的存储为O(n)，最好的情况下，二叉树是平衡二叉树，树的高度是log(N)的，所以此时空复为O(logN) |  |
| [二叉树的最小深度](https://leetcode-cn.com/problems/minimum-depth-of-binary-tree/) | 2020-06-16 | 2020-07-11 | ✅✅✅✅✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：O(n) | if  not root:return 0<br />if not root.left or not root.right:<br />return self.func(root.left)+self.func(root.right)+1<br />return min(self.func(root.left), self.func(root.right))+1 |
| [从上到下打印二叉树 II](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-ii-lcof/) | 2020-06-07 | 2020-07-10 | ✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：O(n) | BFS<br />res, queue = [], [root]<br />while queue:<br />tmp = []<br />for _ in range(len(queue)):<br />node = queue.**pop(0)**<br />**tmp.append(node.val)**<br />**if node.left: queue.append(node.left)**<br />**if node.right:queue.append(node.right)**<br />**注意：pop() 默认弹出最后一个元素，pop(0)弹出第一个** |
| [二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree/) | 2020-06-23 | 2020-07-11 | ✅✅✅✅ | 时间复杂度：O(n) ,每个树节点只访问一次<br />空间复杂度：O(n)，调用栈n次 | def deserialize(self, data):<br />           nodes = iter(data.split(','))<br />def recur():<br />node = next(nodes)<br />if node == '#':return None<br />else:<br />root = TreeNode(int(node))<br />root.left = recur()<br />root.right = recur()<br />return root<br />return recur()|
| [交换和](https://leetcode-cn.com/problems/sum-swap-lcci/) | 2020-07-06 | 2020-07-06 | ✅ |  |  |
| [分发饼干](https://leetcode-cn.com/problems/assign-cookies/) | 2020-07-02 | 2020-07-02 | ✅ |  |  |
| [买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/) | 2020-07-03 | 2020-07-04 | ✅✅ |  |  |
| [验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/) | 2020-06-26  | 2020-07-03 | ✅✅✅✅✅ |  |  |
| [二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | 2020-06-26  | 2020-07-03 | ✅✅✅✅✅✅✅ | 时间：O(n)<br />空间：O(n) | if not root or root==p or root == q: return root<br />left = self.func(root.left,p,q)<br />right = self.func(root.right,p,q)<br />if not left:return right<br />if not right: return left  |
| [二叉搜索树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | 2020-06-20 | 2020-07-11 | ✅✅✅✅ | 时间：O(n)<br />空间：O(n) | if p.val > root.val and q.val > root.val<br />elif p.val < root.val and q.val < root.val<br />return root |
| [买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/) | 2020-07-03 | 2020-07-03 | ✅✅ |  |  |
| [买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii/) | 2020-07-03 | 2020-07-03 | ✅✅ |  |  |
| [最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | 2020-07-04 | 2020-07-10 | ✅✅ | 时间复杂度：prices数组长度为n,所以为O(n)时间复杂度<br />空间复杂度：如果使用二维数组的话，则为O（n），但是存在优化的空间，就是使用变量代替二维数组，可以优化到O(1) | dp = [[None, None] for _ in range(n)]<br />dp[0][0] = 0<br />dp[0][1] = -price[0]<br />dp[1][0] = max()<br />dp[1][1] = max()<br />for i in range(2, n):<br />............... |
| [买卖股票的最佳时机含手续费](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | 2020-07-04 | 2020-07-04 | ✅ |  |  |
| [买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) | 2020-07-04 | 2020-07-04 | ✅ |  |  |
| [x 的平方根](https://leetcode-cn.com/problems/sqrtx/) | 2020-07-05 | 2020-07-05 | ✅ |  |  |
| [有效的完全平方数](https://leetcode-cn.com/problems/valid-perfect-square/) | 2020-07-05 | 2020-07-05 | ✅✅ |  |  |
| [搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/) | 2020-07-06 | 2020-07-06 | ✅ |  |  |
| [删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array/) | 2020-06-10 | 2020-07-07 | ✅✅✅ |  | if nums[slow] != nums[fast]:<br />slow+=1<br />nums[slow] = nums[fast] |
| [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/) | 2020-06-13 | 2020-07-07 | ✅✅✅ |  | while num1_index>0 and num2_index>0<br />num1[:nums2_index+1] = nums2[:nums2_index+1] |
| [合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists/) | 2020-03-02 | 2020-07-08 | ✅✅✅✅ |  | if not l1: return l2<br />if not l2: return l1 |
| [部分排序](https://leetcode-cn.com/problems/sub-sort-lcci/) | 2020-07-06 | 2020-07-06 | ✅ |  |  |
| [最小栈](https://leetcode-cn.com/problems/min-stack/) | 2020-06-06 | 2020-07-07 | ✅✅✅ |  | if not min_stack or self.min_stack[1] >= x:<br />self.min_stack.apped(x) |
| [ 柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/) | 2020-06-08 | 2020-07-08 | ✅✅✅✅ |  | heights.append(0)<br />stack = [-1]<br />are = 0<br />for index in range(len(heights)):<br />    while heights[index] < heights[stack[-1]] |
| [丑数 II](https://leetcode-cn.com/problems/ugly-number-ii/) | 2020-06-22 | 2020-07-08 | ✅✅✅ |  | 堆实现和动态规划实现 |
| [ 环形链表](https://leetcode-cn.com/problems/linked-list-cycle/) | 2020-02-04 | 2020-07-09 | ✅✅✅✅ | 两种情况：存在环和不存在环<br />不存在环：快指针遍历数组长度n结束，则O(N)<br />存在环：快指针遍历数组长度n进入环，快慢指针差速长度K，则O(N+K)，K为常数，则O(N)<br />空间复杂度：只使用了快慢指针，所以O(1) | if not head or not head.next:return False<br />slow, fast = head, head.next<br />while slow!=fast:<br />if not fast or not fast.next:<br />.......... |
| [环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii/) | 2020-06-07 | 2020-07-10 | ✅✅✅ | 时间：O(n)<br />空间：O(n) | if not head or not head.next:return <br />slow, fast = head, head<br />        while True: <br />            if not fast or not fast.next: return None<br />            slow, fast = slow.next, fast.next.next<br />            if slow == fast: break<br />fast = head<br />while slow != fast:<br />..................... |
| [有效的括号](https://leetcode-cn.com/problems/valid-parentheses/) | 2020-02-04 | 2020-07-10 | ✅✅✅✅ | 时间复杂度：O(n)<br />空间复杂度：O(n) |  |
| [子集](https://leetcode-cn.com/problems/subsets/) | 2020-06-25 | 2020-07-11 | ✅✅ | 时间复杂度：O(n*2^n)<br />空间复杂度：O(n*2^n) | def backtrack(index, tmp):<br />      res.append(tmp)<br />      for i in range(index, n):<br />          backtrack(i+1, tmp+[nums[i]])<br />backtrack(0, [])<br />return res<br /> |
| [子集 II](https://leetcode-cn.com/problems/subsets-ii/) | 2020-06-25 | 2020-07-11 | ✅✅ | 时间复杂度：O(n*2^n)<br />空间复杂度：O(n*2^n) |  |[子集 II](https://leetcode-cn.com/problems/subsets-ii/) | 2020-06-25 | 2020-07-11 | ✅✅ | 时间复杂度：O(n*2^n)<br />空间复杂度：O(n*2^n) |  |  |