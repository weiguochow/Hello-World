# reading-record

This file mainly record the hand/human pose estimation from website and paper

手势识别的文献综述：

##基于模型的

缺点： 初始化特别复杂而且模型的方法容易陷入局部最优

##基于数据的

缺点：应对噪声的方法不太好

Human Pose Estimation categories:

1. Bottom-up approach
**先检测出基本单元，像limbs 和 joints， 然后再组装成人
**此方法的优点是，计算量不随场景的人数而改变
2. Top-down approach
**先检测出人，然后运用single person human pose estimation
**该方法的优点是，思路直观，易于理解，容易被大多数人接受
