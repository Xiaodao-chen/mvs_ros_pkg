# MVS_ROS_PKG

quick start:

mvs sdk install [url](https://www.hikrobotics.com/cn/machinevision/service/download/?module=0)



```bash
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/opt/MVS/lib/64 >> ~/.bashrc
mkdir -p mvs/src && cd mvs/src
git clone git@github.com:Xiaodao-chen/mvs_ros_pkg.git
cd ..
catkin_make
```

change your SerialNumber in `left_camera.yaml`

```bash
source devel/setup.bash
roslaunch mvs_ros_pkg mvs_camera.launch
```