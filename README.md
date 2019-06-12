# hector-mapping
make sure ROS_MASTER is same

run radar in self-driving-car
```
roslaunch race auto.launch
```

put slam.launch  hector_mapping.launch  geotiff_mapper.launch in a package called "uprobotics"

edit slam.launch in  uprobotics
remark  line 6
<!-- args="-d $(find hector_slam_launch)/rviz_cfg/mapping_demo.vcg"/ -->


run hector mapping in ros local

```
roslaunch uprobotics slam.launch 
```

Reference source
http://answers.ros.org/question/64644/how-mapping-using-hokuyo-lidar-urg-04lx-and-hector_slam/
