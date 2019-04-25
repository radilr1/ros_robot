# ros_robot
ROS Application for a robot

# Building the Catkin WS

``` 
rosdep install --from-paths src --ignore-src --rosdistro lunar
catkin_make
. ~/walle/devel/setup.bash
```

# Running the app

`roslaunch default default.launch`

# Debugging

 - List all installed nodes `rosnode list   #status check`
 - Run a speicif pakcage `rosrun package action`	
 - Run core only `rescore`
 - Check dependencies `rospack depends1 {package_name} #dependencies check`
