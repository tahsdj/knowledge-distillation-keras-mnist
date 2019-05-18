# knowledge-distillation-keras-mnist
It is a simple demo for using knowledge distillation on mnist dataset.
Here is the original paper: https://arxiv.org/abs/1503.02531

# Results

* Temperature = 7
* Alpha = 0.9

| Teacher | Student | KD |
| -------- | -------- | -------- |
| 99.5(CNN)     | 98.41 (1 layer FC net)   | 98.89(+0.48)    |

![](https://i.imgur.com/YY2G5b4.png)