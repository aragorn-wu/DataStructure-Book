# 堆

不是堆栈的堆

完全二叉树：
除最后一层外，每一层上的节点树均达到最大值，只在最后一层上缺少右边的节点．

ADT:  
类型名称：最大堆（MaxHeap）
对象数据集：
<ol>
<li>完全二叉树</li>
<li>每个节点的元素值不小于其子节点的元素值</li>
</ol>
操作集：
<ul>
<li>MaxHeap create(int MaxSize)创建一个空的最大堆</li>
<li>Boolean isFull(MaxHeap H)判断最大堆是否已满</li>
<li>Insert(MaxHeap H,ElementType item)将元素插入最大堆Ｈ</li>
<li>Boolean IsEmpty(MaxHeap H)判断最大堆是否为空<li>
<li>ElementType DeleteMax(MaxHeap H)</li>
</ul>

