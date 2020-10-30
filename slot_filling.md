# Slot Filling

[TOC]

## 数据集

### SNIPS

[ Coucke et al. (2018)](https://arxiv.org/abs/1805.10190)提出，包含39种slot类型，每个领域有200条训练数据

| Models  | F1       | Paper                                                        | Code |    会议  |
| :------ | :------: | :----------------------------------------------------------: | :--: | :--: |
| [Coach](#coach) | 75.51(Few-shot on 50 (2.5%) samples) | [Coach: A Coarse-to-Fine Approach for Cross-domain Slot Filling](https://arxiv.org/abs/2004.11727) | https://github.com/zliucr/coach | ACL2020 |
|  |  |  |  |  |





## 论文解读

### <a id="coach"> Coach: A Coarse-to-Fine Approach for Cross-domain Slot Filling</a>

1. 创新点

   - 针对特定领域数据稀缺问题，提出一种从粗到细的cross-domain slot filling方法
   - 提出了一种模板正则化方法，通过基于话语模板**对话语表示进行正则化**来提高自适应鲁棒性

2. 模型

   <img src="pics/coach.png" alt="image-20201030164946741" style="zoom:100%;" />

3.  



