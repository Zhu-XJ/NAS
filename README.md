# 模型自动压缩文献项目整理总结

## 目录
+ [基础模型CNN结构设计与训练](#基础模型CNN结构设计与训练)
  - [基础模型结构](#基础模型结构)
  - [基础模型训练方法](#基础模型训练方法)
  - [数据增广](#数据增广)
+ [AutoML学习与应用](#AutoML学习与应用)
  - [自动超参数学习](#自动超参数学习)
  - [神经网络结构搜索](#神经网络结构搜索)
  - [NAS在CV上应用](#NAS在CV上应用)
  - [NAS在模型剪枝方面应用](#NAS在模型剪枝方面应用)
+ [神经网络压缩方法](#神经网络压缩方法)
  - [模型剪枝](#模型剪枝)
  - [模型量化](#模型量化)
  - [模型蒸馏](#模型蒸馏)
  - [动态推理](#动态推理)
 
 
### 神经网络结构搜索
+ 2019 | HAQ: Hardware-Aware Automated Quantization with Mixed Precision  | CVPR | [`PDF`](https://arxiv.org/pdf/1811.08886.pdf) |[`code`](https://github.com/mit-han-lab/haq)
+ 2019 | ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware | ICLR | [`PDF`](https://arxiv.org/pdf/1812.00332.pdf) |[`code`](https://github.com/mit-han-lab/proxylessnas)
+ 2019 | Mixed Precision Neural Architecture Search for Energy Efficient Deep Learning | ICCAD | [`link`](https://www.researchgate.net/publication/337821437_Mixed_Precision_Neural_Architecture_Search_for_Energy_Efficient_Deep_Learning)
+ 2019 | Neural Architecture Search: A Survey  | [`PDF`](https://arxiv.org/pdf/1808.05377v2.pdf)
+ 2019 | DARTS: Differentiable Architecture Search  | ICLR | [`PDF`](https://arxiv.org/pdf/1806.09055.pdf) |[`code`](https://github.com/quark0/darts)
+ 2019 | PC-DARTS: Partial Channel Connections for Memory-Efficient Differentiable Architecture Search | [`PDF`](https://arxiv.org/pdf/1907.05737v1.pdf) |[`code`](https://github.com/yuhuixu1993/PC-DARTS)
+ 2019 | FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search | [`PDF`](https://arxiv.org/pdf/1812.03443v1.pdf) |[`code`](https://github.com/yuhuixu1993/PC-DARTS)
+ 2017 | Neural Architecture Search with Reinforcement Learning  | ICLR | [`PDF`](https://arxiv.org/pdf/1611.01578v2.pdf) |[`code`](https://github.com/titu1994/neural-architecture-search)

### 知乎
- 神经网络架构搜索-Survey -[NAS](https://zhuanlan.zhihu.com/p/97558421)
- 神经网络压缩综述 -[MC](https://zhuanlan.zhihu.com/p/58705979)
- 深度学习模型压缩与加速综述 -[MC](http://www.tensorinfinity.com/paper_167.html)
- 神经网络架构搜索(NAS)中的milestones -[NAS](https://zhuanlan.zhihu.com/p/94252445)
- CVPR 2019 神经网络架构搜索进展综述 -[NAS](https://zhuanlan.zhihu.com/p/75631943)
- 第一次胜过MobileNet的二值神经网络，-1与+1的三年艰苦跋涉 -[MC](https://zhuanlan.zhihu.com/p/103577082)
- 寻找最佳的神经网络架构，韩松组两篇论文解读 -[NAS](https://zhuanlan.zhihu.com/p/81302444)
- ICCV 2019 提前看 | 三篇论文，解读神经网络压缩 -[MC](https://zhuanlan.zhihu.com/p/87938736)
- ICLR 2019｜随机神经网络结构搜索 (SNAS) -[NAS](https://zhuanlan.zhihu.com/p/53920376)
- 网络搜索之DARTS, GDAS, DenseNAS, P-DARTS, PC-DARTS -[NAS](https://zhuanlan.zhihu.com/p/73740783)
- 薰风读论文：Deep Compression 神经网络压缩经典之作 -[MC](https://zhuanlan.zhihu.com/p/77737098)

### CDSN
- 深度学习模型压缩方法综述（一） -[MC](https://blog.csdn.net/wspba/article/details/75671573)
- 深度学习模型压缩方法综述（二） -[MC](https://blog.csdn.net/wspba/article/details/75675554)
- 深度学习模型压缩方法综述（三） -[MC](https://blog.csdn.net/wspba/article/details/76039135)
- HAQ：硬件感知自动化量化框架 -[NAS](https://blog.csdn.net/librahfacebook/article/details/95733314)
- 【论文阅读笔记】darts代码和论文结合阅读 -[NAS](https://blog.csdn.net/zxfhahaha/article/details/102747427?depth_1-utm_source=distribute.pc_relevant.none-task&utm_source=distribute.pc_relevant.none-task)

### Github
- Efficient Neural Architecture Search via Parameters Sharing -[ENAS](https://github.com/carpedm20/ENAS-pytorch)
- Direct Neural Architecture Search on Target Task and Hardware -[ProxylessNAS](https://github.com/mit-han-lab/proxylessnas)
- Hardware-Aware Automated Quantization with Mixed Precision -[HAQ](https://github.com/mit-han-lab/haq)
- Differentiable Architecture Search -[DARTS](https://github.com/quark0/darts)
- Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search -[FBNet](https://github.com/AnnaAraslanova/FBNet)
