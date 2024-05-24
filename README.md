# whill_msgs

## About

The "whill_msgs" is a ROS2 package for WHILL Model CR2 interfaces. <br>
Please refer [whill](https://github.com/WHILL/ros2_whill) page for more information.

<img src="https://user-images.githubusercontent.com/2618822/44189349-e4f39800-a15d-11e8-9261-79edac310e6a.png" width="100px">

**Attention:** <br>
This package on `humble` branch only provides common functions for all models. <br>
If you want to use features that are only available in WHILL Model CR, you will need to use `crystal-devel` branch.


## Messages

| Message type | Explanation |
|:---|:---|
| [whill_msgs/ModelCr2State](./whill_msgs/msg/ModelCr2State.msg) | The dynamic states of WHILL |
| [whill_msgs/SpeedProfile](./whill_msgs/msg/SpeedProfile.msg) | The speed profile of WHILL |


## Services

| Message type | Explanation |
|:---|:---|
| [whill_msgs/SetPower](./whill_msgs/srv/SetPower.srv) | For service which turn WHILL power on/off |
| [whill_msgs/SetSpeedProfile](./whill_msgs/srv/SetSpeedProfile.srv) | For service which change the speed profile of WHILL |
