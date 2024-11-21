# B+树

## 特点
1. 所有非叶子节点只存储键值信息，不存储数据
2. 所有叶子节点包含所有数据记录
3. 叶子节点用指针相连，形成有序链表
4. 所有叶子节点具有相同的深度

## 与B树的区别
1. B+树非叶子节点不存储数据，只存储键值
2. B+树叶子节点包含所有数据
3. B+树叶子节点相连形成有序链表
4. B+树查询更稳定，都是从根到叶子的过程

## 应用
主要应用于数据库索引和文件系统中 