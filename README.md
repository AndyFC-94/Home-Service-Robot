# Home-Service-Robot
In this project a robot performs SLAM and navigation around a simulated environment in Gazebo and ROS.

[rviz]: ./images/robot-rviz.png

## Useful links
[Pick and Place Youtube Video](https://www.youtube.com/watch?v=GLFUglhAJU0)

## Installation

1. Download the catkin workspace. Copy the src folder into your own workspace or  work directly with this workspace (you need to modify the ~/.bashrc file)

2. Clone the following dependencies into you /src folder.

```sh
$ git clone https://github.com/ros-perception/slam_gmapping
$ git clone https://github.com/turtlebot/turtlebot
$ git clone https://github.com/turtlebot/turtlebot_interactions
$ git clone https://github.com/turtlebot/turtlebot_simulator
```

3.Install ROS kinect navigation package
```sh
$ sudo apt-get install ros-kinetic-navigation
```

4.Run catkin_make into your workspace 
5. At the end, you should have something like this:
[file tree]: ./images/file-tree.png


## Usage

1. Go to /src/shell_scripts folder and run home_service.sh
```sh
$ ./home_service.sh
```
