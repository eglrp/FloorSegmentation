# FloorSegmentation

![KITTI Point Cloud](https://github.com/SmallMunich/FloorSegmentation/blob/master/image/origin.jpg)


This Code Is From The Paper: [Fast Segmentation of 3D Point Clouds for Ground Vehicles(2010 IEEE Intelligent Vehicles Symposium)](https://ieeexplore.ieee.org/document/5548059)

Implementation of the ground segmentation algorithm proposed in 
```
@inproceedings{himmelsbach2010fast,
  title={Fast segmentation of 3d point clouds for ground vehicles},
  author={Himmelsbach, Michael and Hundelshausen, Felix V and Wuensche, H-J},
  booktitle={Intelligent Vehicles Symposium (IV), 2010 IEEE},
  pages={560--565},
  year={2010},
  organization={IEEE}
}
```


This Code Is From The Paper: [Fast segmentation of 3D point clouds: A paradigm on LiDAR data for autonomous vehicle applications(2017 IEEE ICRA)](https://ieeexplore.ieee.org/document/7989591/)

Implementation of the ground segmentation algorithm proposed in 
```
@inproceedings{himmelsbach2010fast,
  title={Fast segmentation of 3D point clouds: A paradigm on LiDAR data for autonomous vehicle applications},
  author={D. Zermas, I. Izzat and N. Papanikolopoulos},
  booktitle={International Conference on Robotics and Automation (ICRA), 2017 IEEE},
  pages={5067--5073},
  year={2017},
  organization={IEEE}
}
```


## How To Use

Here are two folders, every folder have its floor segmentation algorithm. You can enter each folder, build it with cmake.


## How To Build 

```bash
 cd build 
 cmake ..
 make 

```

It's All.

## How To Run 

```bash
./test_floorseg 
```

And Then, You Can Find new pcd Files In The Build File.

### Visualize Floor & Not-Floor Point Cloud.

![Segmentation Floor Point Cloud](https://github.com/SmallMunich/FloorSegmentation/blob/master/image/floor.jpg)

![Segmentation No Floor Point Cloud](https://github.com/SmallMunich/FloorSegmentation/blob/master/image/nofloor.jpg)


### More Details Write In Blog Address

* analyze this algorithm: https://blog.csdn.net/Small_Munich/article/details/108086888 

* analyze this algorithm: 