# ISP

### DeepISP ☆
**[Paper]** (TIP 2018) DeepISP: Learning End-to-End Image Processing Pipeline <Br>
**[Author]** [Eli Schwartz](https://elischwartz.github.io/publications/), [Raja Giryes](http://web.eng.tau.ac.il/~raja/),  [Alex M. Bronstein](https://bron.cs.technion.ac.il/) <Br>
大致浏览, 一个end-to-end的网络, 分为保持分辨率的low level部分和逐层下采样的high level部分. 使用了conv+relu, conv+tanh, 直连三个分支并行的设计, 比较少见

### Learning to See in the Dark ★★
**[Paper]** (CVPR 2018) Learning to See in the Dark <Br>
**[Author]** [Chen Chen](http://cchen156.web.engr.illinois.edu/), [Qifeng Chen](https://cqf.io/), [Jia Xu](http://pages.cs.wisc.edu/~jiaxu/), [Vladlen Koltun](http://vladlen.info/)  <Br>
**[[Project](http://cchen156.web.engr.illinois.edu/SID.html)]** **[[TF-Code](https://github.com/cchen156/Learning-to-See-in-the-Dark)]**<Br>
1) 提出了SID数据集, 包括RGB和Raw数据 <Br>
2) 提出了一个end-to-end的isp网络, 以RAW和增益信息为输入, 输入RGB图像, 代替传统ISP流程

### PyNet ★
**[Paper]** (arXiv 2002) Replacing Mobile Camera ISP with a Single Deep Learning Model <Br>
**[Author]**   Andrey Ignatov, Luc Van Gool, Radu Timofte  <Br>
**[[Code](https://github.com/aiff22/pynet)]**<Br>
1) 提出了一个端到端的深度学习网络, 用以代替现有的ISP处理流程. <Br>
2) 提出了一个华为P20 RAW 和Canon 5D的RAW-RGB图像对, 用以训练ISP模型.<Br>
3) 提出的算法与自带的ISP流程相比, 色彩上有一定提升, 但没有明显优势, 且存在晕影. 另外速度也是个问题. 因此对于用一个DL模型代替ISP流程的方案可行性还是有待确认. <Br>
