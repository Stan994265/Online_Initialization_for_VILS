# Online Initialization for Monocular Visual-Inertial-LiDAR System with Extrinsic Calibration and Software Time Synchronization
##  Related Paper
Y. Wang and H. Ma, "Online Spatial and Temporal Initialization for a Monocular Visual-Inertial-LiDAR System," in IEEE Sensors Journal, vol. 22, no. 2, pp. 1609-1620, 15 Jan.15, 2022, doi: 10.1109/JSEN.2021.3133578.[Link](https://ieeexplore.ieee.org/document/9641839)
```
@ARTICLE{9641839,  
author={Wang, Yan and Ma, Hongwei},  
journal={IEEE Sensors Journal},   
title={Online Spatial and Temporal Initialization for a Monocular Visual-Inertial-LiDAR System},   
year={2022},  
volume={22},  
number={2},  
pages={1609-1620},  
doi={10.1109/JSEN.2021.3133578}}
```

##  Hardware introduction
Our VILS is a self-assembled handheld device, it consists of the following:
<img src="figure/device.png">
- MYNTEYE-D120 VI sensor                            https://www.mynteye.com/pages/mynt-eye-d
- LeiShen-C16 3d spinning LiDAR                     https://www.leishen-lidar.com/
- DJI-Manfold2-c mini PC with i7-8559U processor    https://www.dji.com/cn/manifold-2
- PocketLCD Screen                                  https://github.com/peng-zhihui/PocketLCD
- Battery                                           https://store.dji.com/cn/product/matrice-100-tb47d-battery

##  DataSets
### indoor
<img src="figure/indoor.png">

### outdoor
<img src="figure/outdoor.png">

### Description
| name | size |
| :-----| ----: |
| indoor.bag | 3.84G | 
| outdoor.bag | 7.56G | 
| FourMinuteIndoor.bag | 25.04G | 
### Topic:
- imu_topic: `/mynteye/imu/data_raw`        200hz
- image_topic: `/mynteye/left/image_mono`   30hz
- lidar_topic: `/lslidar_point_cloud`       5/10hz

The datasets are avaliable here:
Link：https://pan.baidu.com/s/1quMoph8gzQdlNboWlgLDZw 
pin：gwnm 

##  Demo
### indoor
<img src="gif/indoor1.gif">
<img src="gif/indoor2.gif">
<img src="gif/indoor3.gif">
<img src="gif/indoor4.gif">


### outdoor
<img src="gif/outdoor1.gif">
<img src="gif/outdoor4.gif">
<img src="gif/outdoor3.gif">
<img src="gif/outdoor2.gif">


##  comparison (VI)
<img src="gif/1.gif">
<img src="gif/2.gif">
<img src="gif/3.gif">
<img src="gif/4.gif">
<img src="gif/0.gif">

##  different installations 
<img src="gif/dif.png">
<img src="gif/dif1.gif">
<img src="gif/dif2.gif">
<img src="gif/dif3.gif">
