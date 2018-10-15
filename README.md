# Babuino-Ballesta: CMD 0.0.0 (EagleXv2)
Software for the Command Center PC

This sofware communicate a joy with **~~Trajinera-Lupita~~** for teleoperation.
Also, data is received for display

## Hardware
- [PS4 controller](https://www.playstation.com/en-us/explore/accessories/gaming-controllers/dualshock-4/)
- ~~PC~~

## Sofware
- [Ubuntu 16.04 LTS](http://releases.ubuntu.com/16.04/)
- [ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)
  ### ROS Installation (Ubuntu 16.04)
  ```
  sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
  sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116
  sudo apt-get update
  sudo apt-get isntall ros-kinetic-desktop-full
  sudo rosdep init
  rosdep update
  echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc
  source ~/.bashrc
  sudo apt-get install python-rosinstall python-rosinstall-generator python-wstool build-essential
  ```
  To know how to use ROS go to [ROS Tutorials](http://wiki.ros.org/ROS/Tutorials)
