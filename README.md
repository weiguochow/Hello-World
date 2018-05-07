# reading-record

This file mainly record the hand/human pose estimation from website and paper

手势识别的文献综述：

## 基于模型的

缺点： 初始化特别复杂而且模型的方法容易陷入局部最优

## 基于数据的

缺点：应对噪声的方法不太好

Human Pose Estimation categories:

1. Bottom-up approach
**先检测出基本单元，像limbs 和 joints， 然后再组装成人
**此方法的优点是，计算量不随场景的人数而改变
2. Top-down approach
**先检测出人，然后运用single person human pose estimation
**该方法的优点是，思路直观，易于理解，容易被大多数人接受


The goal of this week is to scan all the paper on the awesome website.

Modifiled the Preview network to study the usage of pytorch

1. To observer the loss decrease using the simple network such as lenet and so on

### next step

original epoches 20

Mean-error(mm): 21.0996508109
Max-error(mm): 152.71031124
Std-error(mm): 10.7448302578
MD-score(20mm): 0.0253635482307
MD-score(30mm): 0.0719259977379
MD-score(40mm): 0.14263208919
MD-score(50mm): 0.228877847794
MD-score(60mm): 0.316484892551
MD-score(70mm): 0.39464026037
MD-score(80mm): 0.461510845856
Joint-Mean-error(mm): [28.70244424243763, 17.373510875388313, 28.265029624836217, 13.734350648215912, 31.387715146397976, 16.562653388735622, 26.977958552614126, 16.65783501106259, 27.719118411695618, 23.21289470653092, 19.422062182609654, 17.936125989122583, 20.008555841561456, 7.434856731733034]
Joint-Max-error(mm): [114.89629505232013, 84.71179620519501, 114.30683559740977, 77.08168949654969, 108.95544015557327, 68.3730934712988, 105.6775672140089, 59.75482758522437, 152.71031123987393, 129.05997797687724, 93.80259705719037, 71.97151292016072, 69.53365474106383, 19.63168145248244]
JSAuC(20mm): 0.247800100409
JSAuC(30mm): 0.389918749856
JSAuC(40mm): 0.501230654041
JSAuC(50mm): 0.584535696974
JSAuC(60mm): 0.646937538952
JSAuC(70mm): 0.694451190559
JSAuC(80mm): 0.731339913268
