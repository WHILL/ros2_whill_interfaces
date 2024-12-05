cmake_minimum_required(VERSION 3.8)
project(whill_msgs)

find_package(ament_cmake REQUIRED)
find_package(rosidl_default_generators REQUIRED)

set(msg_files
  "msg/ModelCr2State.msg"
  "msg/SpeedProfile.msg"
)

set(srv_files
  "srv/SetBatterySaving.srv"
  "srv/SetBatteryVoltageOut.srv"
  "srv/SetPower.srv"
  "srv/SetSpeedProfile.srv"
)

rosidl_generate_interfaces(${PROJECT_NAME}
  ${msg_files}
  ${srv_files}
)

ament_export_dependencies(rosidl_default_runtime)

ament_package()
