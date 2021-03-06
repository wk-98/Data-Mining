实验二    《数据统计和可视化》

题目
基于实验一中清洗后的数据练习统计和视化操作，100个同学（样本），每个同学有11门课程的成绩（11维的向量）；那么构成了一个100x11的数据矩阵。以你擅长的语言C/C++/Java/Python/Matlab，编程计算：
1. 请以课程1成绩为x轴，体能成绩为y轴，画出散点图。
2. 以5分为间隔，画出课程1的成绩直方图。
3. 对每门成绩进行z-score归一化，得到归一化的数据矩阵。
4. 计算出100x100的相关矩阵，并可视化出混淆矩阵。（为避免歧义，这里“协相关矩阵”进一步细化更正为100x100的相关矩阵，100为学生样本数目，视实际情况而定）
5. 根据相关矩阵，找到距离每个样本最近的三个样本，得到100x3的矩阵（每一行为对应三个样本的ID）输出到txt文件中，以\t,\n间隔。
提示：
计算部分不能调用库函数；画图/可视化显示可可视化工具或API实现。

实验摘要：
  本次实验采用实验一的数据进行，为方便统计，规定体测成绩差为50分，普通为65分，良好为80分，优为90分
  根据实验结果已经生成实验要求所需要的散点图，直方图和热力图，文件在实验二/散点图.png和实验二/直方图.png以及实验二/相关矩阵热力图.png
  实验5生成出来的排序矩阵，需要剔除首个数据（因为首个数据是自己本身），处理过后存放在result.txt中
