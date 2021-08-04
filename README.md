# MCS
a missile control system

1.tracking模块
使用拉格朗日插值和卡尔曼滤波方法分别跟踪导弹轨迹，轨迹的所有参数可以设置

2.tracking比较模块
对不同的导弹轨迹运行拉格朗日插值和卡尔曼滤波num_trials次，并获得两种方法的MSE

3.优化拦截optimisation_intercept模块
运行基于优化的框架，使用响应式拦截敌方导弹

4.数值拦截
运行基于数值的拦截框架。并行运行enemy模块 和response模块分别处理导弹轨迹和基于数值的响应
