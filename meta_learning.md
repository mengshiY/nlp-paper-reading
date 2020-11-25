# Meta Learning



## Hypernymy Detection

### Hypernymy Detection for Low-Resource Languages via Meta Learning(ACL 2020)

1. 创新点

   - 利用高资源语言数据解决低资源上下位词识别问题
   - 实验验证了meta learning能有效缓解在低资源任务上的过拟合问题

2. 方法

   - Cross-lingual Training

     - 一对语言（高资源和低资源语言）间的训练

   - Multilingual Training

     - 训练过程中将所有语言中可用的pairs结合在一起

   - Meta-learning

     - MAML

     <img src="./pics/ml_acl20.png" alt="image-20201125155014195" style="zoom:50%;" />

3. 优缺点

   - Meta learning不会偏向于高资源语言的任务
   - 能有效缓解在低资源语言中的过拟合

4. 

