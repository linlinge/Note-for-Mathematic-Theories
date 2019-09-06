# Introduction of Common Nonlinear Optimization  

| Name | Propertis |
-|-|
最速下降法| 负梯度方向，收敛速度慢 |
Levenberg-Marquardt | 信赖域算法，解决H矩阵不满秩或非正定 |
Gradient Descent | （1）靠近极小值时收敛速度减慢，如下图所示；<br>（2）直线搜索时可能会产生一些问题；<br>（3）可能会“之字形”地下降。 |
Gauss-Newton Method| 目标函数的Jacobian 矩阵近似H矩阵，提高算法效率，但H矩阵不满秩则无法迭代 |


## Levenberg-Marquard (LM)
It is often used to solve nonlinear least square problem.
Main Application
* Curve fitting
* 

