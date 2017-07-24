DFS：deep first search

```
void DFS( Vertex v)
{
    visited[v]=true;
    for(v的每个临接点w)
    if(!visited[w])
        DFS(w)
}
```

与树的先序遍历有相似之处。

拯救007：

