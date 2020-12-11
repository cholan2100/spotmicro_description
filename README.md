# spotmicro32_description

CHAMP controller description for ESP32 model of Spot Micro
https://github.com/michaelkubina/SpotMicroESP32

Champ Controller:
https://github.com/chvmp/champ

[![simulate](https://img.youtube.com/vi/VBxURF_wAiI/0.jpg)](https://youtu.be/VBxURF_wAiI "Simulate")

## Requirements
ROS Melodic

## Quick Start

You can view the model by running:

    roslaunch spotmicro_description view_urdf.launch

## Testing

You can modify the Xacro description and see the changes in the UDF file with this command:

    rosrun xacro xacro ceasar.urdf.xacro > ceasar.urdf

## TODO
Implement actuator interface ROS Node on RasPi4 to relay the servo angles to PCA9685
