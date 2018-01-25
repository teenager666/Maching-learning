mean_train 训练数据集的均值
std_train 训练数据集的方差

对测试数据集归一化的方法是根据 mean_train 和 std_train 对测试数据集进行归一化

原因 ：
      测试数据是模拟真实环境
      真实环境很有可能无法得到所有测试数据的均值和方差
      对数据的的归一化也是算法的一部分
      
      (x_test - mean_train) / std_train
      
保存训练数据集得到的均值和方差

scikit-learn 中使用 Scaler 对数据归一化

    from sklearn.preprocessing import StandardScaler
    standardScaler = StandardScaler()
    standardScaler.fit(X_train)
    standardScaler.mean_
    standardScaler.scale_
    standardScaler.transform(X_train)
