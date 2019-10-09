# 1 Summarize the reasons of over-fitting and under-fitting

underfitting
1. 原因:
	1. 1. 模型过于简单
	1. 1. 数据太少
2. 解决方法：
	1.  数据：
		1.  清洗数据
	1.  特征：
		1. 增加特征
		2. 删除噪音特征
	1.  模型：
		1. 调低正则项的惩罚参数
		2. 换更“复杂”的模型（如把线性模型换为非线性模型）
		3. 多个模型级联或组合

Overfitting
1. 原因：
	1. 1. 模型过于复杂
	1. 1. 增加训练数据
2. 解决方法：
	1. 数据：
		1. 增加数据
	1. 特征：
		1. 进行特征选择
		2. 降维（如对特征进行聚类、主题模型进行处理等）
	1. 模型：
		1. 提高正则项的惩罚参数
		2. 减少训练迭代次数
		3. 换更“简单”的模型（如把非线性模型换为线性模型）
		
# 2 Writing down three sceneries that machine learning has been used now
数据挖掘
计算机视觉
自然语言处理
机器人决策
# 3 Come out with three new sceneries with which machine learning may be applied.
医疗诊断，机器人手术
艺术创作
编写程序