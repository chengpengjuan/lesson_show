[source](http://bubkoo.com/2014/01/14/sort-algorithm/heap-sort/)

不得不说的二叉树
每个节点最多有两个子树的树结点， 左子树， 右子树。 
二叉查找树和二叉堆
深度为k的二叉树至多有2^K -1 个结点

满二叉树
完全二叉树

二叉堆 除了最底层之外， 每一层都是满的， 使得堆可以利用数组来表示
某个结点下标i, 这个结点的父结点，孩子结点的下标
Parent(i) = floor(i/2)  父节点的下标
Left(i) = 2*i;
Right(i) = 2*i + 1