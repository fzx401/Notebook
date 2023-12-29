# MVar

:star: **MVar可以理解为Gurobi向量化接口（ndarray化变量）**

1. tolist() 返回一个和原MVar维度大小相同的list
2. MVar * 1 将MVar转化为MLinExpr表达式，用于添加约束or设置目标函数