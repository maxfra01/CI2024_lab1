# CI2024_lab1 - Set Cover Problem

## Results

This table summarizes the results obtained with the different algorithms and parameters.
The greedy costs are the starting point for the RMHC.
The 'Number of evaluations' is the number of evaluations needed to reach the final solution (remaining evaluations are not counted).

| Algorithm | Universe size | Number of sets | Density | Final cost | Number of evaluations|
|-----------|---------------|----------------|---------|------------|----------------------|
| Greedy    | 100           | 10            | 0.2    |    255        |       2               |
|           | 1000          | 100           | 0.2     |   33994         |        21              |
|           | 10000        | 1000           | 0.2     |  4276165          |       44              |
|           | 100000           | 10000            | 0.2     |  2809394          |   53                  |
|           | 100000         | 10000         | 0.1     |    2816360        |         114             |
|           | 100000         | 10000         | 0.3     |    3990011        |            48          |
| RMHC (single mutation)      | 100           | 10            | 0.2     |    255        |          Same as greedy            |
|           | 1000          | 100           | 0.2     |    7102        |          263            |
|           | 10000        | 1000           | 0.2     |   124235         |         4429             |
|           | 100000           | 10000            | 0.2     |    2173244        |         6433             |
|           | 100000         | 10000         | 0.1     |   2002333         |    9456                  |
|           | 100000         | 10000         | 0.3     |   2329157         |           9129           |
| RMHC (activate/deactivate) | 100           | 10            | 0.2     |      255      | Same as greedy                     |
|           | 1000          | 100           | 0.2     |  6812          |        8521              |
|           | 10000        | 1000           | 0.2     |  126062          |         9696             |
|           | 100000           | 10000            | 0.2     |   2120137         |      9963                |
|           | 100000         | 10000         | 0.1     |  1901967          |      643                |
|           | 100000         | 10000         | 0.3     |   2162164         |     6428                 |

