TensorFlow  霍宁肖  2016011504
对x_train，y_train进行训练，对x_test进行预测，是否和y-test标签是否一样
KNN算法：某一个样本在特征空间中的k个最相邻的样本中的大多数都属于某个类别，则该样本也属于这个类别
利用循环，计算每两个样本点之间的距离，平方求和开根号，对距离进行排序后取前k个，出现次数最多的类别
即为预测类别，再与真实类别进行比较，计算准确率
