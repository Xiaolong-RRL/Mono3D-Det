## KITTI-3D Benchmarks
This benchmark follows the nice work: [3dodi-survey](https://github.com/xinzhuma/3dodi-survey/blob/master/docs/benchmark_kitti.md), thanks a lot! !


#### Standard Setting 

| Paper | Code | Venue | Easy | Moderate\* | Hard |
| :---: | :--: | :---: | :--: | :------: | :--: |
| [MonoDDE](https://arxiv.org/abs/2205.09373.pdf) | None | CVPR'22 | 24.93 | 17.14 |15.10|
| [MonoDETR](https://arxiv.org/abs/2203.13310) | [Pytorch](https://github.com/ZrrSkywalker/MonoDETR) | arxiv'22 | 25.00 | 16.47 | 13.58|
| [MonoCon](https://arxiv.org/pdf/2112.04628.pdf) | [Pytorch](https://github.com/Xianpeng919/MonoCon) | AAAI'22 | 22.50 | 16.46 |13.95|
| [IDMS](https://arxiv.org/abs/2212.01528.pdf) | None | arxiv'22 | 22.50 | 16.19 |13.49|
| [MonoJSG](https://arxiv.org/pdf/2203.08563.pdf) | [Pytorch](https://github.com/lianqing11/MonoJSG) | CVPR'22 | 22.69 | 16.14 |13.64|
| [DAE](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Dimension_Embeddings_for_Monocular_3D_Object_Detection_CVPR_2022_paper.pdf) | None | CVPR'22 | 23.62 | 16.10 |13.41|
| [OBMO](https://arxiv.org/abs/2212.10049.pdf) | [Pytorch](https://github.com/mrsempress/OBMO) | arxiv'22 |22.71 | 15.70 |13.23|
| [GPENet](https://arxiv.org/abs/2211.01556.pdf) | None | arxiv'22 | 22.41 | 15.44 |12.84|
| [HOMO](https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Homography_Loss_for_Monocular_3D_Object_Detection_CVPR_2022_paper.pdf) | None | CVPR'22 | 21.75| 14.94 |13.07|
| [MonoEdge](https://arxiv.org/abs/2301.01802.pdf) | None | WACV'23 |21.08 | 14.47 |12.73|
| [DEVIANT](https://arxiv.org/pdf/2207.10758.pdf) | [Pytorch](https://github.com/abhi1kumar/DEVIANT) | ECCV'22 | 21.88 | 14.46 |11.89|
| [MonoGround](https://openaccess.thecvf.com/content/CVPR2022/papers/Qin_MonoGround_Detecting_Monocular_3D_Objects_From_the_Ground_CVPR_2022_paper.pdf) | [Pytorch](https://github.com/cfzd/MonoGround) | CVPR'22 | 21.37 | 14.36 |12.67|
| [GUPNet](https://arxiv.org/pdf/2107.13931.pdf) | [Pytorch](https://github.com/SuperMHP/GUPNet) | ICCV'21 | 20.11 | 14.20 |11.77|
| [MonoFlex](https://arxiv.org/pdf/2104.02323.pdf) | [Pytorch](https://github.com/zhangyp15/MonoFlex) | CVPR'21 | 19.94 | 13.89 |12.07|
| [MonoRCNN](https://arxiv.org/pdf/2104.03775.pdf) | [Pytorch](https://github.com/Rock-100/MonoDet) | ICCV'21 | 18.36 | 12.65 |10.03|
| [MonoDLE](https://arxiv.org/pdf/2103.16237.pdf) | [Pytorch](https://github.com/xinzhuma/monodle) | CVPR'21 | 17.23 | 12.26 |10.29|
| [MonoPair](https://arxiv.org/pdf/2003.00504.pdf) | None | CVPR'20 | 13.04 | 9.99 |8.65|
| [SMOKE](https://arxiv.org/pdf/2002.10111.pdf) | [Pytorch](https://github.com/lzccccc/SMOKE) | CVPRW'20 | 14.17 |	9.88 | 8.63|
| [MonoGRNet](https://arxiv.org/pdf/1811.10247.pdf) | [Pytorch](https://github.com/Zengyi-Qin/MonoGRNet) | AAAI'19 | 9.61 | 5.74 |4.25|



#### LiDAR Signal [training]

|      | Code | Venue | Easy | Moderate\* | Hard |
| ---- | :---:| :---: | :--: | :------: | :--: |
| [CMKD](https://arxiv.org/pdf/2211.07171.pdf) | [Pytorch](https://github.com/Cc-Hy/CMKD) | ECCV'22 | 25.09 | 16.99 |15.30|
| [Shape-Aware](https://arxiv.org/abs/2204.08717.pdf) | None | arxiv'22 | 23.84 | 16.52 |13.88|
| [DID-M3D](https://arxiv.org/pdf/2207.08531.pdf) | [Pytorch](https://github.com/SPengLiang/DID-M3D) | ECCV'22 | 24.40 | 16.29 |13.75|
| [MonoDistill](https://arxiv.org/abs/2201.10830) | [Pytorch](https://github.com/monster-ghost/MonoDistill) | ICLR'22 | 22.97 | 16.03 |13.60|
| [MonoDTR](https://arxiv.org/pdf/2203.10981.pdf) | [Pytorch](https://github.com/kuanchihhuang/MonoDTR) | CVPR'22 | 21.99 | 15.39 |12.73|
| [CaDDN](https://arxiv.org/pdf/2103.01100.pdf) | [Pytorch](https://github.com/open-mmlab/OpenPCDet) | CVPR'21 | 19.17 | 13.41 |11.46|
| [MonoRUn](https://arxiv.org/abs/2103.12605.pdf) | [Pytorch](https://github.com/tjiiv-cprg/MonoRUn) | CVPR'21 | 19.65 | 12.30 |10.58|
| [Ouyang et al.](https://openaccess.thecvf.com/content/ACCV2020/papers/Ouyang_Dynamic_Depth_Fusion_and_Transformation_for_Monocular_3D_Object_Detection_ACCV_2020_paper.pdf) | None | ACCV'20 | 11.52 | 8.26 |6.97|
| [MonoPSR](https://arxiv.org/pdf/1904.01690.pdf) | None | CVPR'19 | 10.76 | 7.25 |5.85|


#### KD Method & LiDAR Signal [training]

|      | Code | Venue | Easy | Moderate\* | Hard |
| ---- | :---:| :---: | :--: | :------: | :--: |
| [CMKD](https://arxiv.org/pdf/2211.07171.pdf) | [Pytorch](https://github.com/Cc-Hy/CMKD) | ECCV'22 | 25.09 | 16.99 |15.30|
| [MonoDistill](https://arxiv.org/abs/2201.10830) | [Pytorch](https://github.com/monster-ghost/MonoDistill) | ICLR'22 | 22.97 | 16.03 |13.60|


#### CAD Model [training]

|      | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :------: | :--: |
| [DCD](https://arxiv.org/pdf/2207.10047.pdf) | ECCV'22 | 23.81| 15.09 |13.21|
| [AutoShape](https://arxiv.org/pdf/2108.11127.pdf) | ICCV'21 | 22.47 | 14.17 |11.36|



#### Stereo Pair [training]

|      | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :------: | :--: |
| [SGM3D](https://arxiv.org/pdf/2112.01914.pdf) | arXiv'21 | 22.46 | 14.65 |12.97|
| [DLE](https://www.bmvc2021-virtualconference.com/assets/papers/0299.pdf) | BMVC'21 | 24.23 | 14.33 |10.30|
| [Ground-Aware](https://arxiv.org/pdf/2102.00690.pdf) | RA-L'21 | 21.65 | 13.25 |9.91|
| [RTM3D](https://arxiv.org/pdf/2001.03343.pdf) | ECCV'20 | 14.41 | 10.34 |8.77|


#### External Data [training] 

|      | Aux. Data | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :--: | :------: | :--: |
| [DD3D](https://arxiv.org/pdf/2108.06417.pdf)                 |     DDAD-15M     |  ICCV'21   | 23.22 |   16.34    |14.20|
| [Lian et al.](https://arxiv.org/pdf/2104.05858.pdf)          |       COCO       |  CVPR'22   | 23.41 |   15.26    |12.80|
| [MonoEF](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Monocular_3D_Object_Detection_An_Extrinsic_Parameter_Free_Approach_CVPR_2021_paper.pdf) |  KITTI-Raw  |  CVPR'21   | 21.29 |   13.87    |11.71|
| [DFRNet](https://openaccess.thecvf.com/content/ICCV2021/papers/Zou_The_Devil_Is_in_the_Task_Exploiting_Reciprocal_Appearance-Localization_Features_ICCV_2021_paper.pdf) | KITTI-Depth  |  ICCV‘21   | 19.40 |   13.63    |10.35|
| [PCT](https://proceedings.neurips.cc/paper/2021/file/6f3ef77ac0e3619e98159e9b6febf557-Paper.pdf) | KITTI-Depth  | NeurIPS'21 | 21.00 |   13.37    |11.31|
| [DDMP-3D](https://arxiv.org/pdf/2103.16470.pdf)              | KITTI-Depth  |  CVPR'21   | 19.71 |   12.78    |9.80|
| [Demystifying](https://openaccess.thecvf.com/content/ICCV2021/papers/Simonelli_Are_We_Missing_Confidence_in_Pseudo-LiDAR_Methods_for_Monocular_3D_ICCV_2021_paper.pdf) | KITTI-Depth  |  ICCV'21   | 22.40 |   12.53    |10.64|
| [IAFA](https://arxiv.org/pdf/2103.03480.pdf) | COCO |  ACCV'20  | 17.81 |   12.01   |10.61|
| [D4LCN](https://arxiv.org/pdf/1912.04799.pdf)                | KITTI-Depth  |  CVPR'20   | 16.65 |   11.72    |9.51|
| [PatchNet](https://arxiv.org/pdf/2008.04582.pdf)             | KITTI-Depth  |  ECCV'20   | 15.68 |   11.12    |10.17|
| [AM3D](https://arxiv.org/pdf/1903.11444.pdf)                 | KITTI-Depth  |  ICCV'19   | 16.50 |   10.74    |9.52|
| [Neighbor-Vote](https://arxiv.org/pdf/2107.02493.pdf)        | KITTI-Depth  | ACM MM'21  | 15.57 |    9.90    | 8.89  |
| [MonoCInIS](https://arxiv.org/pdf/2110.00464.pdf) | Instance Mask |  ICCVW'20  | 11.08 |    7.02    | 5.63  |
| [Decoupled-3D](https://arxiv.org/pdf/2002.01619.pdf)         | KITTI-Depth  |  AAAI'20   | 11.08 |    7.02    | 5.63  |
| [MonoFENet](https://ieeexplore.ieee.org/abstract/document/8897727/) | KITTI-Depth  |  T-IP'19   | 8.35  |    5.14    | 4.10  |



#### CAD Model [training], External Dataset [training]

|      | Aux. Dataset | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :--: | :------: | :--: |
| [ROI-10D](https://arxiv.org/pdf/1812.02781.pdf) | KITTI-Depth  | CVPR'19 | 4.32 |    2.02    |1.46|



#### LiDAR Signal [training], External Dataset [training]

|      | Aux. Dataset | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :--: | :------: | :--: |
| [pseudo-Stereo](https://arxiv.org/pdf/2203.02112.pdf) | KITTI-Depth  | CVPR'22 | 23.74 |    17.74    |15.14 |
| [DA-3Ddet](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540018.pdf) | KITTI-Depth  | ECCV'20 | 16.77 |    11.50    |8.93|



#### Temporal Sequence [training&testing]

|      | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :------: | :--: |
| [DfM](https://arxiv.org/pdf/2207.12988.pdf) | ECCV'22 | 22.94 | 16.82 |14.65|
| [Kinematic3D](https://arxiv.org/pdf/2007.09548.pdf) | ECCV'20 | 19.07 | 12.72 |9.17|
| [QD-3DT](https://arxiv.org/pdf/2103.07351.pdf) | arXiv'21 | 12.91 | 9.33 |7.86|



#### Stereo Pair [training&testing]

|      | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :------: | :--: |
| [RTS3D](https://arxiv.org/pdf/2012.15072.pdf) | AAAI'21 | 58.51 |   37.38    | 31.12 |
| [Stereo CenterNet](https://arxiv.org/pdf/2103.11071.pdf) | Neurocomputing'22 | 49.94 |   31.30   | 25.62 |
| [SIDE](https://arxiv.org/pdf/2108.09663.pdf) | WACV'19 | 47.69 |   30.82   | 25.68 |
| [Stereo R-CNN](https://arxiv.org/pdf/1902.09738.pdf) | CVPR'19 | 47.58 |   30.23    | 23.72 |
| [TLNet](https://arxiv.org/pdf/1906.01193.pdf) | CVPR'19 | 7.64  |    4.37    | 3.74  |



#### CAD Model [training], Stereo Pair [training&testing]

|                                                             |   Venue   | Easy  | Moderate\* | Hard  |
| ----------------------------------------------------------- | :-------: | :---: | :--------: | :---: |
| [Disp R-CNN](https://jiamingsun.ml/docs/DispRCNN-TPAMI.pdf) | T-PAMI'20 | 67.02 |   43.27    | 36.43 |
| [Disp R-CNN](https://arxiv.org/pdf/2004.03572.pdf)          |  CVPR'20  | 58.53 |   37.91    | 31.93 |



#### LiDAR Signal [training], Stereo Pair [training&testing]

|                                                      |   Venue    | Easy  | Moderate\* | Hard  |
| ---------------------------------------------------- | :--------: | :---: | :--------: | :---: |
| [LIGA Stereo](https://arxiv.org/pdf/2108.08258.pdf)  |  ICCV'21   | 81.39 |   64.66    | 57.22 |
| [CDN](https://arxiv.org/pdf/2007.03085.pdf)          | NeurIPS'20 | 74.52 |   54.22    | 46.36 |
| [DSGN](https://arxiv.org/pdf/2001.03398.pdf)         |  CVPR'20   | 73.50 |   52.18    | 45.14 |
| [YOLOStereo3D](https://arxiv.org/pdf/2103.09422.pdf) |  ICRA'21   | 65.68 |   41.25    | 30.42 |



#### External Dataset [training], Stereo Pair [training&testing]

|      | Aux. Dataset | Venue | Easy | Moderate\* | Hard |
| ---- | :---: | :--: | :--: | :------: | :--: |
| [RT3DStereo](https://www.mrt.kit.edu/z/publ/download/2019/Koenigshof2019Objects.pdf) | SceneFlow | ITSC'19 | 29.90 | 23.28 |18.96|

