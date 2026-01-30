# unitree_interfaces
This is a ros2 package that contains ros2 messages of the unitree_interfaces type, which is not part of the unitree_ros2 package

So far the only message of this type on the unitree B2 is:
> /unitree_interfaces/msg/bmsstate \>
More messages will be added as more undocumented unitree message types are found

### How to install
```
colcon build --symlink-install
source install/setup.bash
```
Now you are able to read and compile code that have the unitree_interfaces type
