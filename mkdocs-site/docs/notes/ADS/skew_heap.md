# 斜堆

特殊的leftist heap，且满足父节点值小于子节点(最小堆)

轻的有可能变重，重的一定会变轻

## 合并
- 如果一个空斜堆与一个非空斜堆合并，返回非空斜堆
- 如果两个斜堆都非空，那么比较两个根结点，将较小的根结点的右孩子对应的子堆和另一个堆去合并，合并得到的新子堆的根结点作为新的右孩子
- **将当前根结点的左右孩子互换位置** 