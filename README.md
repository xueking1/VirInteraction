# VirInteraction: Enhancing Virutal-LiDAR Points Interaction by Using Image Semantics and Density Estimation for 3D Object Detection

This is the implementation of ***VirInteraction*** ,  a semantic-guided Virtual-LiDAR fusion method to enhance the interaction of virtual points and LiDAR points. This code is mainly based on [OpenPCDet](https://github.com/open-mmlab/OpenPCDet), some codes are from [Virconv](https://github.com/hailanyi/TED), [CompletionFormer](https://github.com/youmi-zym/CompletionFormer), [mmsegmentation](https://github.com/open-mmlab/mmsegmentation/tree/main) and [PointConv](https://github.com/DylanWusee/pointconv).

## Detection Framework

* VirInteraction: Enhancing Virutal-LiDAR Points Interaction by Using Image Semantics and Density Estimation for 3D Object Detection.

The detection frameworks are shown below.

![](./tools/image/total.png)

### Experimental results

#### KITTI dataset

| METHOD                                                        | EASY  | MOD   | HARD  |
| ------------------------------------------------------------- | ----- | ----- | ----- |
| [VirInteraction](tools/cfgs/models/kitti/VirInteraction.yaml) | 96.34 | 90.63 | 89.01 |

#### Visualization of voxel distribution of VirInteraction:

![loadingag1489](./tools/image/vision_difference.png)



#### Acknowledgement

* This work is built upon the `OpenPCDet`. Please refer to the official github repositories, [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) , [Focals Conv](https://github.com/dvlab-research/FocalsConv/tree/master)and [CenterPoint](https://github.com/tianweiy/CenterPoint) for more information.We use the KDE implementation from [PointConv](https://github.com/DylanWusee/pointconv).

* This README follows the style of [IA-SSD](https://github.com/yifanzhang713/IA-SSD).

## License

This project is released under the [Apache 2.0 license](LICENSE).

## Related Repos

1. [spconv](https://github.com/traveller59/spconv) ![GitHub stars](https://img.shields.io/github/stars/traveller59/spconv.svg?style=flat&label=Star)
2. [PointConv](https://github.com/DylanWusee/pointconv)
3. [Submanifold Sparse Conv](https://github.com/facebookresearch/SparseConvNet)
4. [VirConv](https://github.com/hailanyi/VirConv)
5. [mmsegmentation](https://github.com/open-mmlab/mmsegmentation/tree/main)
