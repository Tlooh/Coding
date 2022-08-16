# leetcode 刷题记录

## 数组
### 1. 二分查找
**区间计算：left、right、mid 取值**
    
```python
# python

mid = (left + right)//2 
# 注：// 为取整，用/号，结果出来会是浮点数
# 但有时可能因为 限制变量的数据长度
# 所以上式等价为：
mid = left + (right - left)//2

```

&emsp;
**思考：当处于开闭区间的时候，mid取值？**
`[left, right], [left, right), (left, right]`

&emsp;
**牛顿迭代法**
适用题目：
+ 69.x 的平方根
    + 二分查找法
    + [牛顿迭代法](https://leetcode.cn/problems/sqrtx/solution/niu-dun-die-dai-fa-by-loafer/)

   
### 2.  移除元素
    快慢指针

3. 两数之和
   先排序，再快慢指针