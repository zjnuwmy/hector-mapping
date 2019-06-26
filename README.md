# hector-mapping

download from this page
```
cd catkin_ws/src
git clone https://github.com/zjnuwmy/hector-mapping.git
cd ..
catkin_make
source devel/setup.bash
```

make sure ROS_MASTER is same

run radar in self-driving-car
```
roslaunch race auto.launch
```

put slam.launch  hector_mapping.launch  geotiff_mapper.launch in a package called "uprobotics"




run hector mapping in ros local

```
roslaunch hector_mapping mapping_default.launch 
roslaunch uprobotics slam.launch 
```

Reference source
http://answers.ros.org/question/64644/how-mapping-using-hokuyo-lidar-urg-04lx-and-hector_slam/
