# Cartographer-SLAM-for-Non-GPS-Navigation

# Mavros install

sudo apt-get install ros-melodic-mavros ros-melodic-mavros-extras

wget https://raw.githubusercontent.com/mavlink/mavros/master/mavros/scripts/install_geographiclib_datasets.sh

chmod a+x install_geographiclib_datasets.sh

./install_geographiclib_datasets.sh

sudo apt-get install ros-melodic-rqt ros-melodic-rqt-common-plugins ros-melodic-rqt-robot-plugins


# https://ardupilot.org/dev/docs/ros-cartographer-slam.html

mkdir -p ca_catkin_ws/src

sudo apt-get update
sudo apt-get install -y python-wstool python-rosdep ninja-build stow

----
----


src/cartographer/scripts/install_abseil.sh

sudo apt-get remove ros-${ROS_DISTRO}-abseil-cpp



catkin build
