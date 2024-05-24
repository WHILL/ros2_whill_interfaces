# whill_msgs

## About

The "whill_msgs" is a ROS2 package for WHILL Model CR2 interfaces. <br>
Please refer [whill](https://github.com/WHILL/ros2_whill) page for more information.

<img width=22% title="WHILL Model CR2" src="https://github.com/WHILL/Model_CR_Technical_Support/assets/129816934/387a8aac-3808-4727-895d-9857059ee342">
<img width=24% title="Wheeled Robot Base" src="https://github.com/WHILL/Model_CR_Technical_Support/assets/129816934/6a63ed45-9e0c-40ca-b71c-8dff614af141">

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
