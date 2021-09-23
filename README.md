# awesome-3d-multi-object-tracking-autonomous-driving
A summary and list of open source 3D multi object tracking and datasets at this stage.



## Open Source Solutions

|                           Solution                           |                        **Popularity**                        |                           Feature                            |                  Paper                   | Language |    Sensors     |       Dataset        |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------------------------------------: | :------: | :------------: | :------------------: |
| [AB3DMOT (IROS 2020)](https://github.com/xinshuoweng/AB3DMOT) | ![](https://img.shields.io/github/stars/xinshuoweng/AB3DMOT.svg?style=social&label=star) |     The baseline of a lot of 3D MOT framework since 2019     | [here](https://arxiv.org/abs/2008.08063) |  python  |     LIDAR      |        KITTI         |
| [mahalanobis_3d_mot (2019)](https://github.com/eddyhkchiu/mahalanobis_3d_multi_object_tracking) | ![](https://img.shields.io/github/stars/eddyhkchiu/mahalanobis_3d_multi_object_tracking.svg?style=social&label=star) | use mahalanobis distance based on AB3DMOT (the first place award in NuScenes Tracking Challenge) | [here](https://arxiv.org/abs/2001.05673) |  python  |     LIDAR      |        KITTI         |
| [3D-Multi-Object-Tracker](https://github.com/hailanyi/3D-Multi-Object-Tracker) | ![](https://img.shields.io/github/stars/hailanyi/3D-Multi-Object-Tracker.svg?style=social&label=star&size=Large) | Fast (700FPS), support online, near online and global implementation in 3D MOT, including **[visualization code](https://github.com/hailanyi/3D-Detection-Tracking-Viewer)** |                                          |  python  |     LIDAR      |     KITTI Waymo      |
| [EagerMOT (ICRA 2021)](https://github.com/aleksandrkim61/EagerMOT) | ![](https://img.shields.io/github/stars/aleksandrkim61/EagerMOT.svg?style=social&label=star) | Improve the online 3D multi-object tracking performance by using 2D detections to support tracking when 3D association fails. | [here](https://arxiv.org/abs/2104.14682) |  python  | LIDAR + camera |    KITTI Nuscenes    |
| [CenterPoint (2021)](https://github.com/tianweiy/CenterPoint) | ![](https://img.shields.io/github/stars/tianweiy/CenterPoint.svg?style=social&label=star) | 3D Object Detection and Tracking using center points in the bird-eye view | [here](https://arxiv.org/abs/2006.11275) |  python  |                |    Waymo Nuscenes    |
| [Monocular Quasi-Dense 3D Object Tracking (QD-3DT ,2021)](https://github.com/SysCV/qd-3dt) </br> [website](https://eborboihuc.github.io/QD-3DT/) | ![](https://img.shields.io/github/stars/SysCV/qd-3dt.svg?style=social&label=star) | an online framework detects and tracks objects in 3D using quasi-dense object proposals from 2D images. | [here](https://arxiv.org/abs/2103.07351) |  python  |     camera     | NuScenes KITTI Waymo |



## Dataset 

|                           Dataset                            |                         Tutorial                         |                  Paper                   |
| :----------------------------------------------------------: | :------------------------------------------------------: | :--------------------------------------: |
| [KITTI](http://www.cvlibs.net/datasets/kitti/eval_tracking_overview.php) |                                                          |                                          |
| [NuScenes](https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any) |   [tool](https://github.com/nutonomy/nuscenes-devkit)    |                                          |
|         [Waymo](https://waymo.com/open/challenges/)          |                                                          |                                          |
|   [Apollo Scape](http://apolloscape.auto/trajectory.html)    | [github](https://github.com/ApolloScapeAuto/dataset-api) | [here](https://arxiv.org/abs/1803.06184) |

