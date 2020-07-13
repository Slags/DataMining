# 包含数据分析和数据挖掘的学习代码和实战代码

> 本项目很多内容属于边学边试。参考了书籍，但是很多代码存在过时和错误均被我修改。

数据挖掘是最近几年才出现的一个名词，其归根到底的目的就是经过一系列手段处理数据得到一个适合的建模数据，利用建模数据建立模型挖掘已有数据的隐含价值。
## 一般步骤（详细内容子目录有叙述，且后面的**实战项目**我会严格按照这个步骤进行）
- 数据获取
	- 利用各种手段获取数据，数据样式不限制，但一般而言是形如excel或者csv这样的表格格式。
- 数据探索
	- 对数据进行初步探索，得到数据特征（如每一列的平均值，分位数，最大最小值，空值数目）。
- 数据预处理
	- 毫不夸张，这是整个数据挖掘过程中最费时间的部分。对原始数据进行处理，得到合适的建模数据（如处理异常值，属性规约，数据清洗，数据变换，数据标准化）。
- 数据挖掘建模
	- 如果任务明确，模型的选择是指定的，但是算法的优化，准确率的考究等是需要处理的。（如分类预测、关联规则获取。
- 后续处理
	- 一般是指模型的实际应用。
