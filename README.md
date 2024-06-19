# DetectBench: Can Large Language Model Detect and Piece Together Implicit Evidence?

![intro.png](src%2Fintro.png)


[Arxiv paper](https://arxiv.org/abs/2406.12641)

## The example of DetectBench
![example.png](src%2Fexample.png)

## Statistic Information about DetectBench
| Name          | #Sample    | Avg #Token | Avg #Evidence | Avg #Jumps |
|---------------|------------|------------|---------------|------------|
| train         | 365        | 177        | 4.27          | 7.10       |
| dev           | 1,770      | 178        | 4.34          | 7.13       |
| test-noremal  | 1,193      | 179        | 4.24          | 7.03       |
| test-hard     | 300        | 261        | 7.79          | 13.83      |
| test-distract | 300        | 10,779     | 4.16          | 7.27       |
| **All**       | **3,928**  | **994**    | **4.55**      | **7.62**   |


## The detail comparsion of ``implicit evidence`` Among Other Works
![detail.png](src%2Fdetail.png)