
**图**(graph) $G=(V,E)$ 由**顶点**(vertex) 的集 V 和**边**(edge)的集 E 组成。每一条边就是一个点对 $(v,w)$ ，其中 $v,w \in V$。
有时也把边称作**弧**(arc)。如果点对是有序的，那么图就叫作**有向图**。当且仅当 $v,w \in V$，在一个具有边 (v,w)，称顶点 v 和 顶点 w 的**邻接**(adjacent)。
有时候边还具有第三种成分，称作**权**(weight)或**值**(cost)。

图中的一条**路径**是一个顶点序列 $w_1,w_2,w_3,\dots,w_n$，其中 $(w_i,w_{i+1}) \in E, 1\leqslant i \lt N$。这样一条路径的**长**是路径上的边数，等于 $N-1$ 。

如果图含有一条从一个顶点到它自身的边 $(v,v)$，那么路径被叫作**环**(loop)。我们要讨论的图一般是无环的。简单路径是指路径上的所有顶点都是互异的，但第一个顶点和最后一个顶点可能相同。

有向图中的**回路**是满足 $W_1=W_N$ 且长至少为 1 的路径；如果路径是简单路径，那么这个回路就是简单回路。如果一个有向图没有回路，则称为**无环的**(acyclic)。

- 完全图 (complete graph) 每一条顶点之间都存在一条边的图。
- 连通图 (connected graph) 每个顶点到每个其他顶点都存在一条路径的图。
- 稀疏图 (sparse graph) $|E|$ 远小于 $|V|^2$ 的图。
- 稠密图 (dense graph) $|E|$ 接近于 $|V|^2$ 的图。

## Reference

- [GeeksforGeeks - Graph Data Structure And Algorithms](https://www.geeksforgeeks.org/graph-data-structure-and-algorithms)
- [MathWorks - 图和网络算法](https://ww2.mathworks.cn/help/matlab/graph-and-network-algorithms.html)
