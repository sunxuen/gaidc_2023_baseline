# gaidc_2023_baseline
和鲸社区：《2023 全球人工智能开发者先锋大会—AI 人才学习赛》解决方案
## top20 方案：
### 基于比赛数据集日内连续，日间不连续的特性，融合两种不同的数据处理思路：其一是打乱日间数据，其二是保证日间数据连续性，每种处理方式均基于时间特征生成一系列时序特征，两种数据处理方式的结果做模型融合生成最后的提交结果。
具体实现代码见：[baseline文件](gaidc_2023_baseline/开源.ipynb)