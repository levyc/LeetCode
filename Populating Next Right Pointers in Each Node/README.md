#第一百一十六题
##Populating Next Right Pointers in Each Node
将完全二叉树的左子树next指向指向右子树，要求常数空间完成

###版本1
使用队列完成，但是不是常数空间完成

###版本2
使用递归完成，但是感觉这也不算常数空间。

###版本3
想了一下，发现当前节点的next指针可用，这样就可以在常数空间完成了。