# URDF tutorial

Commands:

## render the urdf file in Rviz
```
roslaunch urdf_tutorial display.launch model:=urdf/01-myfirst.urdf
```

## refactor to xacro
```
rosrun xacro xacro urdf/refactor.xacro >! model.urdf
```