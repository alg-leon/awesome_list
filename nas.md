# NAS
---

### DARTS

##### PDARTS
Progressive Differentiable Architecture Search:Bridging the Depth Gap between Search and Evaluation
*Xin Chen, Lingxi Xie, Jun Wu, Qi Tian (Huawei)*
* paper: [Arxiv 201904](https://arxiv.org/abs/1904.12760)
* code:
  * [Official Pytorch(111)](https://github.com/chenxin061/pdarts)
    * 基于DARTS.
* key:
  1. From DARTS.      
  2. Progressive search methods.

##### PCDARTS
Partial Channel Connections for Memory-Efficient Differentiable Architecture Search
*Yuhui Xu, Lingxi Xie, Xiaopeng Zhang, Xin Chen, Guo-Jun Qi, Qi Tian and Hongkai Xiong (Huawei)*
* paper: [Arxiv 201907](https://arxiv.org/abs/1907.05737)
* code:
  * [Official+Pytorch(111)](https://github.com/yuhuixu1993/PC-DARTS)
    * 基于darts.

##### Single-Path NAS
Single-Path NAS: Designing Hardware-Efficient ConvNets in less than 4 Hours.
*Dimitrios Stamoulis, Ruizhou Ding, Di Wang, Dimitrios Lymberopoulos, Bodhi Priyantha, Jie Liu, Diana Marculescu*
* paper: [Arxiv 201904](https://arxiv.org/abs/1904.02877)
* code:
  * [Official Tensorflow+TPU(111)](https://github.com/dstamoulis/single-path-nas)
      * 基于tpu的estimator，且只能用tpu，修改成gpu版本比较麻烦。

##### FBnet
FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search
*Bichen Wu1, Xiaoliang Dai, Peizhao Zhang, Yanghan Wang, Fei Sun, Yiming Wu, Yuandong Tian, Peter Vajda, Yangqing Jia, Kurt Keutzer (Fasebook Research)*
* paper: [Arxiv 201812](https://arxiv.org/pdf/1812.03443.pdf)
* code:
  * [Other Pytorch(111)](https://github.com/AnnaAraslanova/FBNet)
    * layer模块来自facebook.
    * 搜索模块来自DARTS.
