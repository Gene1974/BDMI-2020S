# 第四节课

## 1、找中位数

支点法：先取一支点，每个数与支点比较，小的数放在支点左边，大的右边，

选支点位于3n/10和7n/10之间（n为序列长度）：把序列分为m组，每组长度小于5，找每一组的中值p，再将每个p组成一个新的数组，再找新数组的中值，则这个中值满足上述范围条件。

## 2、2-3-4树

## 3、B+树

B树索引，调入调出代价最低的索引。

叶子节点指向数据，还有一个指针指向下一个叶子节点，非叶子节点指向下面的节点。

下一层节点数大于等于(n+1)/2

## 4、B树

与B+树相比没有重复的key，叶子节点不连续

## 5、哈希表

目的：快速插入，删除和查找
