给定金融数据，预测贷款用户是否会逾期。（status是标签：0表示未逾期，1表示逾期。）

**Task1** - 构建逻辑回归模型进行预测（在构建部分数据需要进行缺失值处理和数据类型转换，如果不能处理，可以直接暴力删除）

**Task2** - 构建SVM和决策树模型进行预测

**Task3** - 构建xgboost和lightgbm模型进行预测

**Task4（模型评估）** - 记录五个模型关于accuracy、precision，recall和f1-score、auc、roc的评分表格，画出auc和roc曲线图

**Task5（数据预处理）** - 数据类型转换, 无用特征删除, 缺失值处理（尝试不同的填充看效果）及数据探索

**Task6（模型调优）** - 使用网格搜索对模型进行调优, 并采用五折交叉验证的方式进行模型评估

**Task7（模型融合）** - 对Task6调优后的模型, 进行模型融合。例如, 用目前评分最高的模型作为基准模型, 和其他模型进行stacking模型融合, 得到最终模型和评分。