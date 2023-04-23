# frequency
实验内容：（参考使用mlxtend库）
1.	面向Amazon.com评论的频繁K项集挖掘：
1)	数据库（transactionDB.txt）：我们使用的数据库是Amazon.com的评论者。具体来说，评论者ID是我们的项集。事务是一组评论者ID的集合。交易格式数据库遵循transactionDB.txt的标准格式：每行代表一个事务。对于给定的事务，项集（评论者ID）用空格字符分隔。
 
2)	实验目标：实现对最小支持度计数（min_sup_cnt）的频繁k项集的挖掘，并将对应的结果保存到“exp3_std_res”文件夹中。其中，s= min_sup_cnt，即最小支持度计数；k 即 频繁项集中项集的个数。
 
3)	算法实现：参考实验内容1中使用mlxtend的fpgrowth方法，完成评论数据集的频繁模式挖掘。其中，最小支持度计数=10、频繁项集2+项集的结果已经给出（out_s=10_k=2+.txt），格式与结果输出如下。
A20JYIHL1W1U54 A7Y6AVS576M03 (10)
A231WM2Z2JL0U3 A5JLAU2ARJ0BO (11)

附加实验：
3.	使用Apriori算法实现实验内容2的结果，并对比Apriori 和 FP Growth的运行时间。
