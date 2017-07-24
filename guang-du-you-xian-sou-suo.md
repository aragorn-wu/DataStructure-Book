BFS:breath first search

* 最简单的图搜索算法之一，也是许多重要的图算法的原型。如prim最小生成树/dijkstra单源最短路径。
* 给定图G=\(V,E\)和一个可以识别的源节点。

```
void BFS( Vertex v)
{
    visited[v]=true;
    Enqueue(V,Q);
    while(!IsEmpty(Q)){
        V=Dequeue(Q)
        for(V 的每个临接点 W){
            if(!visited[w]）{
                visited[w]=true;
                Enqueue(w,q);
            }
        }
    }
}
```



