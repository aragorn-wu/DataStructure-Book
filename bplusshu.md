# B+树

B+树是B-树的变体，也是一种多路搜索树。特点如下：
<ol>
<li>非叶子节点的个数和子树指针的个数相同</li>
<li>非叶子结点的子树指针P[i]，指向关键字值属于[K[i], K[i+1])的子树</li>
<li>为所有叶子结点增加一个链指针</li>
<li>所有关键字都在叶子结点出现</li>
</ol>
![B+树](http://p.blog.csdn.net/images/p_blog_csdn_net/manesking/5.JPG)


B+树在使用的时候特征如下：
<ol>
<li>所有关键字都出现在叶子结点的链表中（稠密索引），且链表中的关键字恰好是有序的</li>
<li>不可能在非叶子结点命中</li>
<li>非叶子结点相当于是叶子结点的索引（稀疏索引），叶子结点相当于是存储（关键字）数据的数据层</li>
<li>更适合文件索引系统<li>
</ol>