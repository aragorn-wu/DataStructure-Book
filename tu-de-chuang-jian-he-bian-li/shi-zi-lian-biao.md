对于有向图来说，邻接表是有缺陷的。关心了出度问题，想了解入度就必须要遍历整个图才知道，反之，逆邻接表解决了入度却不了解出度情况。下面介绍的这种有向图的存储方法：十字链表，就是把邻接表和逆邻接表结合起来的。

重新定义顶点表结点结构，如下所示。

![](/assets/26548237_1359379404626B.png)

其中firstin表示入边表头指针，指向该顶点的入边表中第一个结点，firstout表示出边表头指针，指向该顶点的出边表中的第一个结点。

重新定义边表结构，如下所示：

![](/assets/a.png)

其中，tailvex是指弧起点在顶点表的下标，headvex是指弧终点在顶点表的下标，headlink是指入边表指针域，指向终点相同的下一条边，taillink是指出边表指针域，指向起点相同的下一条边。如果是网，还可以增加一个weight域来存储权值。

