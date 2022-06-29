# Index-Based-A-Star-Algorithm
**[Research Paper Link](https://ieeexplore.ieee.org/document/8299426)**
<p align= "justify">Implementation of <strong>IBAS: Index Based A-Star</strong> proposed by <strong>Yan Li, Hongyan Zhang, Huaizhong Zhu, Jianwei Li, Wenjie Yan</strong> and <strong>Youxi Wu (Member, IEEE)</strong>.
The Research Paper aims to solve the shortest path problem in a weighted directed acyclic graph with unknown vertex coordinates and compared this algorithm with <strong>IBAS-S</strong> (which uses only static pruning), <strong>A-Star</strong> and <strong>Dijsktra</strong> algorithms to find its working efficiency. </p>

The main contributions of this study are threefold:
1. Proposed methods for constructing the earliest arrival index, reverse earliest arrival index, and latest arrival index in a weighted DAG.
2. Presented an index-based A-star algorithm, IBAS, which uses the earliest arrival index to construct the evaluation function of the A-star algorithm, and also employs the above three indexes to achieve effective pruning.
3. Through extensive experiments, demonstrated that IBAS can effectively boost the speed of traditional algorithms, and the efficiency of the reachability cost index is high.

## Example
### Input
* Enter the number of vertices: 23
* Enter the number of edges: 27
* Enter the edges of DAG: 0 1 2 1 2 2 2 3 4 3 4 3 4 5 6 4 6 2 4 9 3 6 7 2 7 8 3 9 8 8 14 4 5 14 9 4 11 3 2 10 11 4 10 12 2 12 13 1 13 14 1 21 14 3 14 18 5 20 21 2 19 20 2 19 18 9 19 22 2 22 17 15 18 15 2 15 16 3 16 17 3
![DAG23](https://user-images.githubusercontent.com/42888030/176465957-ec80bbef-69c2-41f2-b052-1d3964cd8d65.png)

### Result
![Comparison of Total No. of Iterations](https://user-images.githubusercontent.com/42888030/176468481-fb86098a-b1cc-4e08-80e4-542f65cd4c3f.png)
