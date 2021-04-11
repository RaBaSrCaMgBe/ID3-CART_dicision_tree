# ID3-CART_dicision_tree
分别用ID3算法和CART算法实现了"创建决策树"以及"通过现有决策树模型对数据集进行分类"这两个功能
输入数据格式为
[[样本1真假值(只能取0或1),样本1属性1,样本1属性2,...,样本1属性n],
 [样本2真假值(只能取0或1),样本2属性1,样本2属性2,...,样本2属性n]，
 .
 .
 .
 [样本n真假值(只能取0或1),样本n属性1,样本n属性2,...,样本n属性n]]
 
 Continuous_attr这个参数为一个一维数组，里面存储了取值为连续值的属性下标(从0开始)，用以完成连续值的离散化处理
 
 由于技术限制，还没有完成剪枝功能......
