# Index-Based-A-Star-Algorithm

<p align= "justify">Implementation of **[IBAS: Index Based A-Star](https://ieeexplore.ieee.org/document/8299426)** proposed by **Yan Li, Hongyan Zhang, Huaizhong Zhu, Jianwei Li, Wenjie Yan** and **Youxi Wu (Member, IEEE)**
The Research Paper aims to solve the shortest path problem in a weighted directed acyclic graph with unknown vertex coordinates and compared this algorithm with **IBAS-S** (which uses only static pruning), **A-Star** and **Dijsktra** algorithms to find its working efficiency. </p>

The main contributions of this study are threefold:
1. Proposed methods for constructing the earliest arrival index, reverse earliest arrival index, and latest arrival index in a weighted DAG.
2. Presented an index-based A-star algorithm, IBAS, which uses the earliest arrival index to construct the evaluation function of the A-star algorithm, and also employs the above three indexes to achieve effective pruning.
3. Through extensive experiments, demonstrated that IBAS can effectively boost the speed of traditional algorithms, and the efficiency of the reachability cost index is high.

![DAG23](https://user-images.githubusercontent.com/42888030/176465957-ec80bbef-69c2-41f2-b052-1d3964cd8d65.png)
![Comparison of Total No. of Iterations](https://user-images.githubusercontent.com/42888030/176466063-cfd720b8-decc-4c43-a1f9-3260c13520d4.png)
