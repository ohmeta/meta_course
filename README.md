**以下所有任务需新建自己的分支和文件夹，完成后merge到主分支上。**

## 基础篇
### task 1 基因预测
1. 下载Bacillus subtilis (NC_000964.3)和Methanotorris igneus(NC_015562.1)的基因组序列文件。
2. 预测其CDS区域，将CDS提取出来生成cds.fna文件，并统计每条cds的相关信息。包括:基因组起始位置，终止位置，正负链信息，CDS长度。
3. 将cds区域翻译成蛋白序列，生成cds.faa文件。

2，3两步请使用python/perl以及相关包实现。

### task 2 熟悉流程
1. 学习Snakemake (https://snakemake.readthedocs.io/en/stable/tutorial/short.html) 的使用方法。
2. 使用meta_profile (https://biogit.cn/TianLiu/meta_profile) 流程，投任务分析20个舌苔样本和20个唾液样本的数据。
3. 将meta_profile流程改写为shell流程，从20个舌苔样本中每个样本中随机抽取1M paried reads做成新的数据集。跑shell流程得到结果。

集群账号及项目编号请联系项目经理或技术导师。
集群使用说明：https://biogit.cn/TianLiu/bgi_cluster_guideline

### task 3 R统计绘图
1. 舌苔和唾液样本中宿主reads所占的比例是多少？两者宿主率是否有显著差异？
2. 舌苔和唾液样本中的微生物群落是否存在差异？ (提示，可以做PcoA)
3. 挑选舌苔和唾液中的相对丰度存在显著差异且相对丰度在Top10的10个物种，使用热图可视化这些物种在样本中的相对丰度。
4. 再提2个值得探究的问题，使用该数据集或收集数据并尝试回答。
