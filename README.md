# Reflection_Summary

我觉得，一个合格的算法工程师，需要掌握：
- [扎实的数据结构能力](https://github.com/sladesha/LeetCode)
- [大量的机器学习实操经验](https://github.com/sladesha/machine_learning)
- [大量的深度学习项目经验](https://github.com/sladesha/deep_learning)
- 有一个相对精通的语言，比如python    
    - [靠谱底层机制的理解](https://github.com/sladesha/sladeRode2)
    - [动手做过一些demo](https://github.com/sladesha/PyTls)
    - [有一些成功的经验](https://github.com/sladesha/Frcwp)
    - [贡献过一些开源项目](https://github.com/brennerm/PyTricks)
- [靠谱的java编码能力](https://github.com/sladesha/sladeRode)
- [了解java工程](https://github.com/sladesha/sladeRode4)
- [了解C++](https://github.com/sladesha/sladeRode3)
- [总结表述沉淀能力](http://www.shataowei.com)

1. 以下内容为我作为面试管的提问，以及陪伴实习生同学@[tcandzq](https://github.com/tcandzq)参加2020届校招面试各类算法问题及个人理解的汇总
2. 各种解答均为我的理解和看法，一定有存疑和不完善的地方，欢迎大家补充和质疑打脸
3. 另外，恭喜[tcandzq](https://github.com/tcandzq)收割到腾讯UGC，阿里算法中台，头条广告推荐offer，:clap:

***
# 基础概念
- 方差和偏差
    - [解释方差](基础概念/方差与偏差/方差与偏差.md#L1)
    - [解释偏差](基础概念/方差与偏差/方差与偏差.md#L4)
    - [模型训练为什么要引入偏差和方差？请理论论证](基础概念/方差与偏差/方差与偏差.md#L7)
    - [什么情况下引发高方差](基础概念/方差与偏差/方差与偏差.md#L26)
    - [如何解决高方差问题](基础概念/方差与偏差/方差与偏差.md#L31)
    - [以上方法是否一定有效](基础概念/方差与偏差/方差与偏差.md#L36)
    - [如何解决高偏差问题](基础概念/方差与偏差/方差与偏差.md#L44)
    - [以上方法是否一定有效](基础概念/方差与偏差/方差与偏差.md#L51)
    - [遇到过的机器学习中的偏差与方差问题](基础概念/方差与偏差/方差与偏差.md#L56)
    - [就理论角度论证Bagging、Boosting的方差偏差问题](基础概念/方差与偏差/方差与偏差.md#L60)
    - [遇到过的深度学习中的偏差与方差问题](基础概念/方差与偏差/方差与偏差.md#L88)
    - [方差、偏差与模型的复杂度之间的关系](基础概念/方差与偏差/方差与偏差.md#L96)
- 生成与判别模型
    - [什么叫生成模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [什么叫判别模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [什么时候会选择生成/判别模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [CRF/朴素贝叶斯/EM/最大熵模型/马尔科夫随机场/混合高斯模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [我的理解](基础概念/生成与判别模型/生成与判别模型.md#L96)
- 先验概率和后验概率
    - [写出全概率公式&贝叶斯公式](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [说说你怎么理解为什么有全概率公式&贝叶斯公式](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [什么是先验概率](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [什么是后验概率](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [经典概率题](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
- 频率概率
    - [极大似然估计 - MLE](基础概念/频率概率/频率概率.md#L96)
    - [最大后验估计 - MAP](基础概念/频率概率/频率概率.md#L96)
    - [极大似然估计与最大后验概率的区别](基础概念/频率概率/频率概率.md#L96)
    - [到底什么是似然什么是概率估计](基础概念/频率概率/频率概率.md#L96)

# 数学
- 数据质量
    - [期望](数学/数据质量/期望、方差、标准差和协方差.md#L1)
    - [方差](数学/数据质量/期望、方差、标准差和协方差.md#L4)
    - [标准差](数学/数据质量/期望、方差、标准差和协方差.md#L9)
    - [协方差](数学/数据质量/期望、方差、标准差和协方差.md#L11)
    - [相关系数](数学/数据质量/期望、方差、标准差和协方差.md#L11)
- 最大公约数问题
    - [辗转相除法](数学/最大公约数问题/gcd.md#L1)
    - [其他方法](数学/最大公约数问题/gcd.md#L1)
- 牛顿法
    - [迭代公式推导](数学/牛顿法/牛顿迭代法求平方根.md#L1)
    - [实现它](数学/牛顿法/牛顿迭代法求平方根.md#L1)
- 拟牛顿法
- 概率密度分布
    - [均匀分布](数学/概率密度分布/概率密度分布.md#L1)
    - [伯努利分布](数学/概率密度分布/概率密度分布.md#L1)
    - [二项分布](数学/概率密度分布/概率密度分布.md#L1)
    - [高斯分布](数学/概率密度分布/概率密度分布.md#L1)
    - [拉普拉斯分布](数学/概率密度分布/概率密度分布.md#L1)
    - [泊松分布](数学/概率密度分布/概率密度分布.md#L1)
- 平面曲线的切线和法线
    - [平面曲线的切线](数学/平面曲线的切线和法线/平面曲线的切线和法线.md#L1)
    - [平面曲线的法线](数学/平面曲线的切线和法线/平面曲线的切线和法线.md#L1)
- 导数
    - [四则运算](数学/导数/导数.md#L1)
    - [常见导数](数学/导数/导数.md#L1)
    - [复合函数的运算法则](数学/导数/导数.md#L1)
    - [莱布尼兹公式](数学/导数/导数.md#L1)
- 微分中值定理
    - [费马定理](数学/微分中值定理/微分中值定理.md#L1)
    - [拉格朗日中值定理](数学/微分中值定理/微分中值定理.md#L1)
    - [柯西中值定理](数学/微分中值定理/微分中值定理.md#L1)
- 泰勒公式
    - [泰勒公式](数学/泰勒公式/泰勒公式.md#L1)
- 欧拉公式
    - [欧拉公式](数学/欧拉公式/欧拉公式.md#L1)
- 矩阵
    - [范数](数学/矩阵/矩阵.md#L1)
    - [特征值分解，特征向量](数学/矩阵/矩阵.md#L1)
    - [正定性](数学/矩阵/矩阵.md#L1)
- 概率论
    - [条件概率](数学/概率论/概率论.md#L1)
    - [独立](数学/概率论/概率论.md#L1)
    - [概率基础公式](数学/概率论/概率论.md#L1)
    - [全概率](数学/概率论/概率论.md#L1)
    - [贝叶斯](数学/概率论/概率论.md#L1)
    - [切比雪夫不等式](数学/概率论/概率论.md#L1)
    - [抽球](数学/概率论/概率论.md#L1)
    - [纸牌问题](数学/概率论/概率论.md#L1)
    - [棍子/绳子问题](数学/概率论/概率论.md#L1)
    - [贝叶斯题](数学/概率论/概率论.md#L1)
    - [选择时间问题](数学/概率论/概率论.md#L1)
    - [0~1均匀分布的随机器如何变化成均值为0，方差为1的随机器](数学/概率论/概率论.md#L1)
    - [抽红蓝球球](数学/概率论/概率论.md#L1)

# 数据预处理
- 数据平衡
    - [为什么要对数据进行采样](数据预处理/数据平衡/采样.md#L1)
    - [是否一定需要对原始数据进行采样平衡](数据预处理/数据平衡/采样.md#L6)
    - [有哪些常见的采样方法](数据预处理/数据平衡/采样.md#L11)
    - [能否避免采样](数据预处理/数据平衡/采样.md#L36)
    - [你平时怎么用采样方法](数据预处理/数据平衡/采样.md#L39)
- 异常点处理
    - [统计方法](数据预处理/异常点处理/异常点识别.md#L1)
    - [矩阵分解方法](数据预处理/异常点处理/异常点识别.md#L21)
    - [特征值和特征向量的本质是什么](数据预处理/异常点处理/异常点识别.md#L33)
    - [矩阵乘法的实际意义](数据预处理/异常点处理/异常点识别.md#L37)
    - [密度的离群点检测](数据预处理/异常点处理/异常点识别.md#L41)
    - [聚类的离群点检测](数据预处理/异常点处理/异常点识别.md#L52)
    - [如何处理异常点](数据预处理/异常点处理/异常点识别.md#L56)
- 缺失值处理
    - [是不是一定需要对缺失值处理](数据预处理/缺失值处理/缺失值处理.md#L1)
    - [直接填充方法有哪些](数据预处理/缺失值处理/缺失值处理.md#L4)
    - [模型插值方法有哪些？及方法的问题](数据预处理/缺失值处理/缺失值处理.md#L10)
    - [如何直接离散化](数据预处理/缺失值处理/缺失值处理.md#L14)
    - [hold位填充方法有哪些](数据预处理/缺失值处理/缺失值处理.md#L17)
    - [怎么理解分布补全](数据预处理/缺失值处理/缺失值处理.md#L22)
    - [random方法使用前提](数据预处理/缺失值处理/缺失值处理.md#L25)
    - [总结](数据预处理/缺失值处理/缺失值处理.md#L28)
- 特征选择
    - [为什么要做特征选择](数据预处理/特征选择/特征选择.md#L1)
    - [从哪些方面可以做特征选择](数据预处理/特征选择/特征选择.md#L6)
    - [既然说了两个方向，分别介绍一些吧](数据预处理/特征选择/特征选择.md#L10)
- 特征提取
    - [为什么需要对数据进行变换](数据预处理/特征提取/数据变换.md#L1)
    - [归一化和标准化之间的关系](数据预处理/特征提取/数据变换.md#L6)
    - [连续特征常用方法](数据预处理/特征提取/数据变换.md#L20)
    - [离散特征常用方法](数据预处理/特征提取/数据变换.md#L71)
    - [文本特征](数据预处理/特征提取/数据变换.md#L88)
    - [画一个最简单的最快速能实现的框架](数据预处理/特征提取/数据变换.md#L164)

# 机器学习
- 聚类
    - [请问从EM角度理解kmeans](机器学习/聚类/kmeans.md#L164)
    - [为什么kmeans一定会收敛](机器学习/聚类/kmeans.md#L164)
    - [kmeans初始点除了随机选取之外的方法](机器学习/聚类/kmeans.md#L164)
- 线性回归
    - [损失函数是啥](机器学习/线性回归/线性回归.md#L164)
    - [最小二乘/梯度下降手推](机器学习/线性回归/线性回归.md#L164)
    - [介绍一下岭回归](机器学习/线性回归/线性回归.md#L164)
    - [什么时候使用岭回归](机器学习/线性回归/线性回归.md#L164)
    - [什么时候用Lasso回归](机器学习/线性回归/线性回归.md#L164)
- 逻辑回归
    - [logistic分布函数和密度函数，手绘大概的图像](机器学习/逻辑回归/lr.md#L164)
    - [LR推导，基础5连问](机器学习/逻辑回归/lr.md#L164)
    - [梯度下降如何并行化](机器学习/逻辑回归/lr.md#L164)
    - [LR明明是分类模型为什么叫回归](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR可以用来做CTR预估](机器学习/逻辑回归/lr.md#L164)
    - [满足什么样条件的数据用LR最好](机器学习/逻辑回归/lr.md#L164)
    - [LR为什么使用sigmoid函数作为激活函数？其他函数不行吗](机器学习/逻辑回归/lr.md#L164)
    - [利用几率odds的意义在哪](机器学习/逻辑回归/lr.md#L164)
    - [Sigmoid函数到底起了什么作用](机器学习/逻辑回归/lr.md#L164)
    - [LR为什么要使用极大似然函数，交互熵作为损失函数？那为什么不选平方损失函数的呢](机器学习/逻辑回归/lr.md#L164)
    - [LR中若标签为+1和-1，损失函数如何推导？](机器学习/逻辑回归/lr.md#L164)
    - [如果有很多的特征高度相关或者说有一个特征重复了100遍，会造成怎样的影响](机器学习/逻辑回归/lr.md#L164)
    - [为什么要避免共线性](机器学习/逻辑回归/lr.md#L164)
    - [LR可以用核么？可以怎么用](机器学习/逻辑回归/lr.md#L164)
    - [LR中的L1/L2正则项是啥](机器学习/逻辑回归/lr.md#L164)
    - [lr加l1还是l2好](机器学习/逻辑回归/lr.md#L164)
    - [正则化是依据什么理论实现模型优化](机器学习/逻辑回归/lr.md#L164)
    - [LR可以用来处理非线性问题么](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR需要归一化或者取对数](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR把特征离散化后效果更好？离散化的好处有哪些](机器学习/逻辑回归/lr.md#L164)
    - [逻辑回归估计参数时的目标函数逻辑回归的值表示概率吗](机器学习/逻辑回归/lr.md#L164)
    - [LR对比万物](机器学习/逻辑回归/lr.md#L164)
    - [LR梯度下降方法](机器学习/逻辑回归/lr.md#L164)
    - [LR的优缺点](机器学习/逻辑回归/lr.md#L164)
    - [除了做分类，你还会用LR做什么](机器学习/逻辑回归/lr.md#L164)
    - [你有用过sklearn中的lr么？你用的是哪个包](机器学习/逻辑回归/lr.md#L164)
    - [看过源码么？为什么去看](机器学习/逻辑回归/lr.md#L164)
    - [谈一下sklearn.linear_model.LogisticRegression中的penalty和solver的选择](机器学习/逻辑回归/lr.md#L164)
    - [谈一下sklearn.linear_model.LogisticRegression中对多分类是怎么处理的](机器学习/逻辑回归/lr.md#L164)
    - [我的总结](机器学习/逻辑回归/lr.md#L164)
- 决策树
    - [常见决策树](机器学习/决策树/决策树.md#L164)
    - [简述决策树构建过程](机器学习/决策树/决策树.md#L164)
    - [详述信息熵计算方法及存在问题](机器学习/决策树/决策树.md#L164)
    - [详述信息增益计算方法](机器学习/决策树/决策树.md#L164)
    - [详述信息增益率计算方法](机器学习/决策树/决策树.md#L164)
    - [解释Gini系数](机器学习/决策树/决策树.md#L164)
    - [ID3存在的问题](机器学习/决策树/决策树.md#L164)
    - [C4.5相对于ID3的改进点](机器学习/决策树/决策树.md#L164)
    - [CART的连续特征改进点](机器学习/决策树/决策树.md#L164)
    - [CART分类树建立算法的具体流程](机器学习/决策树/决策树.md#L164)
    - [CART回归树建立算法的具体流程](机器学习/决策树/决策树.md#L164)
    - [CART输出结果的逻辑](机器学习/决策树/决策树.md#L164)
    - [CART树算法的剪枝过程是怎么样的](机器学习/决策树/决策树.md#L164)
    - [树形结构为何不需要归一化](机器学习/决策树/决策树.md#L164)
    - [决策树的优缺点](机器学习/决策树/决策树.md#L164)
- 贝叶斯
    - [解释一下朴素贝叶斯中考虑到的条件独立假设](机器学习/贝叶斯/贝叶斯.md#L164)
    - [讲一讲你眼中的贝叶斯公式和朴素贝叶斯分类差别](机器学习/贝叶斯/贝叶斯.md#L164)
    - [朴素贝叶斯中出现的常见模型有哪些](机器学习/贝叶斯/贝叶斯.md#L164)
    - [出现估计概率值为 0 怎么处理](机器学习/贝叶斯/贝叶斯.md#L164)
    - [朴素贝叶斯的优缺点](机器学习/贝叶斯/贝叶斯.md#L164)
    - [朴素贝叶斯与 LR 区别](机器学习/贝叶斯/贝叶斯.md#L164)
- 随机森林
    - [解释下随机森林](机器学习/随机森林/随机森林.md#L164)
    - [随机森林用的是什么树](机器学习/随机森林/随机森林.md#L164)
    - [随机森林的生成过程](机器学习/随机森林/随机森林.md#L164)
    - [解释下随机森林节点的分裂策略](机器学习/随机森林/随机森林.md#L164)
    - [随机森林的损失函数是什么](机器学习/随机森林/随机森林.md#L164)
    - [为了防止随机森林过拟合可以怎么做](机器学习/随机森林/随机森林.md#L164)
    - [随机森林特征选择的过程](机器学习/随机森林/随机森林.md#L164)
    - [是否用过随机森林，有什么技巧](机器学习/随机森林/随机森林.md#L164)
    - [RF的参数有哪些，如何调参](机器学习/随机森林/随机森林.md#L164)
    - [RF的优缺点](机器学习/随机森林/随机森林.md#L164)
- 集成学习
    - [介绍一下Boosting的思想](机器学习/集成学习/GBDT.md#L164)
    - [最小二乘回归树的切分过程是怎么样的](机器学习/集成学习/GBDT.md#L164)
    - [有哪些直接利用了Boosting思想的树模型](机器学习/集成学习/GBDT.md#L164)
    - [gbdt和boostingtree的boosting分别体现在哪里](机器学习/集成学习/GBDT.md#L164)
    - [gbdt的中的tree是什么tree？有什么特征](机器学习/集成学习/GBDT.md#L164)
    - [常用回归问题的损失函数](机器学习/集成学习/GBDT.md#L164)
    - [常用分类问题的损失函数](机器学习/集成学习/GBDT.md#L164)
    - [什么是gbdt中的残差的负梯度](机器学习/集成学习/GBDT.md#L164)
    - [如何用损失函数的负梯度实现gbdt](机器学习/集成学习/GBDT.md#L164)
    - [拟合损失函数的负梯度为什么是可行的](机器学习/集成学习/GBDT.md#L164)
    - [即便拟合负梯度是可行的，为什么不直接拟合残差？ 拟合负梯度好在哪里](机器学习/集成学习/GBDT.md#L164)
    - [Shrinkage收缩的作用](机器学习/集成学习/GBDT.md#L164)
    - [feature属性会被重复多次使用么](机器学习/集成学习/GBDT.md#L164)
    - [gbdt如何进行正则化的](机器学习/集成学习/GBDT.md#L164)
    - [为什么集成算法大多使用树类模型作为基学习器？或者说，为什么集成学习可以在树类模型上取得成功](机器学习/集成学习/GBDT.md#L164)
    - [gbdt的优缺点](机器学习/集成学习/GBDT.md#L164)
    - [gbdt和randomforest区别](机器学习/集成学习/GBDT.md#L164)
    - [GBDT和LR的差异](机器学习/集成学习/GBDT.md#L164)
    - [xgboost对比gbdt/boosting Tree有了哪些方向上的优化](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost和gbdt的区别](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost优化目标/损失函数改变成什么样](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost如何使用MAE或MAPE作为目标函数](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost如何寻找分裂节点的候选集](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost如何处理缺失值](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost在计算速度上有了哪些点上提升](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost特征重要性是如何得到的](机器学习/集成学习/Xgboost.md#L164)
    - [xGBoost中如何对树进行剪枝](机器学习/集成学习/Xgboost.md#L164)
    - [xGBoost模型如果过拟合了怎么解决](机器学习/集成学习/Xgboost.md#L164)
    - [xgboost如何调参数](机器学习/集成学习/Xgboost.md#L164)
    - [XGboost缺点](机器学习/集成学习/LightGBM.md#L164)
    - [LightGBM对Xgboost的优化](机器学习/集成学习/LightGBM.md#L164)
    - [LightGBM亮点](机器学习/集成学习/LightGBM.md#L164)
- FM/FFM
- SVM
    - [简单介绍SVM](机器学习/支持向量机/支持向量机.md#L164)
    - [什么叫最优超平面](机器学习/支持向量机/支持向量机.md#L164)
    - [什么是支持向量](机器学习/支持向量机/支持向量机.md#L164)
    - [SVM 和全部数据有关还是和局部数据有关](机器学习/支持向量机/支持向量机.md#L164)
    - [加大训练数据量一定能提高SVM准确率吗](机器学习/支持向量机/支持向量机.md#L164)
    - [如何解决多分类问题](机器学习/支持向量机/支持向量机.md#L164)
    - [可以做回归吗，怎么做](机器学习/支持向量机/支持向量机.md#L164)
    - [SVM 能解决哪些问题](机器学习/支持向量机/支持向量机.md#L164)
    - [介绍一下你知道的不同的SVM分类器](机器学习/支持向量机/支持向量机.md#L164)
    - [什么叫软间隔](机器学习/支持向量机/支持向量机.md#L164)
    - [SVM 软间隔与硬间隔表达式](机器学习/支持向量机/支持向量机.md#L164)
    - [SVM原问题和对偶问题的关系/解释原问题和对偶问题](机器学习/支持向量机/支持向量机.md#L164)
    - [为什么要把原问题转换为对偶问题](机器学习/支持向量机/支持向量机.md#L164)
    - [为什么求解对偶问题更加高效](机器学习/支持向量机/支持向量机.md#L164)
    - [alpha系数有多少个](机器学习/支持向量机/支持向量机.md#L164)
    - [KKT限制条件，KKT条件有哪些，完整描述](机器学习/支持向量机/支持向量机.md#L164)
    - [引入拉格朗日的优化方法后的损失函数解释](机器学习/支持向量机/支持向量机.md#L164)
    - [核函数的作用是啥](机器学习/支持向量机/支持向量机.md#L164)
    - [核函数的种类和应用场景](机器学习/支持向量机/支持向量机.md#L164)
    - [如何选择核函数](机器学习/支持向量机/支持向量机.md#L164)
    - [常用核函数的定义](机器学习/支持向量机/支持向量机.md#L164)
    - [核函数需要满足什么条件](机器学习/支持向量机/支持向量机.md#L164)
    - [为什么在数据量大的情况下常常用lr代替核SVM](机器学习/支持向量机/支持向量机.md#L164)
    - [高斯核可以升到多少维？为什么](机器学习/支持向量机/支持向量机.md#L164)
    - [SVM和逻辑斯特回归对同一样本A进行训练，如果某类中增加一些数据点，那么原来的决策边界分别会怎么变化](机器学习/支持向量机/支持向量机.md#L164)
    - [各种机器学习的应用场景分别是什么？例如，k近邻,贝叶斯，决策树，svm，逻辑斯蒂回归](机器学习/支持向量机/支持向量机.md#L164)
    - [Linear SVM 和 LR 有什么异同](机器学习/支持向量机/支持向量机.md#L164)
# 深度学习
- dropout
- batch_normalization
- bp过程
- embedding
- softmax
- 梯度消失/爆炸
- Attention
    - [Attention对比RNN和CNN，分别有哪点你觉得的优势](深度学习/Attention.md#L164)
    - [写出Attention的公式](深度学习/Attention.md#L164)
    - [解释你怎么理解Attention的公式的](深度学习/Attention.md#L164)
    - [Attention模型怎么避免词袋模型的顺序问题的困境的](深度学习/Attention.md#L164)
    - [Attention机制，里面的q,k,v分别代表什么](深度学习/Attention.md#L164)
    - [为什么self-attention可以替代seq2seq](深度学习/Attention.md#L164)
    - [维度与点积大小的关系是怎么样的，为什么使用维度的根号来放缩](深度学习/Attention.md#L164)
# 自然语言处理
- GloVe
    - [GolVe的损失函数](自然语言处理/GloVe.md#L164)
    - [解释GolVe的损失函数](自然语言处理/GloVe.md#L164)
    - [为什么GolVe会用的相对比W2V少](自然语言处理/GloVe.md#L164)
- Word2Vec 
    - [从隐藏层到输出的Softmax层的计算有哪些方法](自然语言处理/Word2Vec.md#L164)
    - [层次softmax流程](自然语言处理/Word2Vec.md#L164)
    - [负采样流程](自然语言处理/Word2Vec.md#L164)
    - [word2vec两种方法各自的优势](自然语言处理/Word2Vec.md#L164)
    - [怎么衡量学到的embedding的好坏](自然语言处理/Word2Vec.md#L164)
    - [word2vec和glove区别](自然语言处理/Word2Vec.md#L164)
    - [你觉得word2vec有哪些问题](自然语言处理/Word2Vec.md#L164)
- CRF
    - [阐述CRF原理](自然语言处理/Word2Vec.md#L164)
    - [线性链条件随机场的公式是](自然语言处理/Word2Vec.md#L164)
    - [CRF与HMM区别](自然语言处理/Word2Vec.md#L164)
    - [Bert+crf中的各部分作用详解](自然语言处理/Word2Vec.md#L164)
- LDA
    - [详述LDA原理](自然语言处理/LDA.md#L164)
    - [LDA中的主题矩阵如何计算](自然语言处理/LDA.md#L164)
    - [LDA的共轭分布解释下](自然语言处理/LDA.md#L164)
    - [PLSA和LDA的区别](自然语言处理/LDA.md#L164)
    - [怎么确定LDA的topic个数](自然语言处理/LDA.md#L164)
    - [LDA和Word2Vec区别？LDA和Doc2Vec区别](自然语言处理/LDA.md#L164)
- LSTM
- GRU
- Bert
    - [Bert的双向体现在什么地方](自然语言处理/Bert.md#L164)
    - [Bert的是怎样预训练的](自然语言处理/Bert.md#L164)
    - [在数据中随机选择 15% 的标记，其中80%被换位\[mask\]，10%不变、10%随机替换其他单词，原因是什么](自然语言处理/Bert.md#L164)
    - [为什么BERT有3个嵌入层，它们都是如何实现的](自然语言处理/Bert.md#L164)
    - [bert的损失函数](自然语言处理/Bert.md#L164)
    - [手写一个multi-head attention](自然语言处理/Bert.md#L164)
    - [长文本预测如何构造Tokens](自然语言处理/Bert.md#L164)
    - [你用过什么模块？bert流程是怎么样的](自然语言处理/Bert.md#L164)
    - [知道分词模块：FullTokenizer做了哪些事情么](自然语言处理/Bert.md#L164)
    - [Bert中如何获得词意和句意](自然语言处理/Bert.md#L164)
    - [源码中Attention后实际的流程是如何的](自然语言处理/Bert.md#L164)
    - [为什么要在Attention后使用残差结构](自然语言处理/Bert.md#L164)
    - [平时用官方Bert包么？耗时怎么样](自然语言处理/Bert.md#L164)
    - [你觉得BERT比普通LM的新颖点](自然语言处理/Bert.md#L164)
    - [elmo、GPT、bert三者之间有什么区别](自然语言处理/Bert.md#L164)

# 推荐
- DIN
- DeepFM
    - [DNN与DeepFM之间的区别](推荐/DeepFM.md#L164)
    - [Wide&Deep与DeepFM之间的区别](推荐/DeepFM.md#L164)
    - [你在使用deepFM的时候是如何处理欠拟合和过拟合问题的](推荐/DeepFM.md#L164)
    - [DeepFM怎么优化的](推荐/DeepFM.md#L164)
    - [不定长文本数据如何输入deepFM](推荐/DeepFM.md#L164)
    - [deepfm的embedding初始化有什么值得注意的地方吗](推荐/DeepFM.md#L164)
        - [Xavier初始化](推荐/DeepFM.md#L164)
        - [He初始化](推荐/DeepFM.md#L164)
- YoutubeNet
    - [变长数据如何处理的](推荐/YouTubeNet.md#L164)
    - [input是怎么构造的](推荐/YouTubeNet.md#L164)
    - [最后一次点击实际如何处理的](推荐/YouTubeNet.md#L164)
    - [output的是时候train和predict如何处理的](推荐/YouTubeNet.md#L164)
    - [如何进行负采样的](推荐/YouTubeNet.md#L164)
    - [item向量在softmax的时候你们怎么选择的](推荐/YouTubeNet.md#L164)
    - [Example Age的理解](推荐/YouTubeNet.md#L164)
    - [什么叫做不对称的共同浏览（asymmetric co-watch）问题](推荐/YouTubeNet.md#L164)
    - [整个过程中有什么亮点？有哪些决定性的提升](推荐/YouTubeNet.md#L164)
- Wide&Deep
- MLR
- Neural Network全家桶
- XDeepFM
    - [选用的原因](推荐/XDeepFM.md#L164)
    - [什么叫显示隐式？什么叫元素级/向量级？什么叫做高阶/低阶特征交互](推荐/XDeepFM.md#L164)
# 风控
- 孤立森林
- 评分卡

# 评价指标
- 二分类
- 多分类
- 回归指标
- 聚类指标
- 排序指标