# Cartographer-SLAM-for-Non-GPS-Navigation


sudo apt-get install python-catkin-tools

mkdir -p path_to_my_workspace/workspace_name/src

cd path_to_my_workspace/workspace_name/src

catkin_init_workspace

# Mavros install

sudo apt-get install ros-melodic-mavros ros-melodic-mavros-extras

wget https://raw.githubusercontent.com/mavlink/mavros/master/mavros/scripts/install_geographiclib_datasets.sh

chmod a+x install_geographiclib_datasets.sh

sudo ./install_geographiclib_datasets.sh

sudo apt-get install ros-melodic-rqt ros-melodic-rqt-common-plugins ros-melodic-rqt-robot-plugins


# https://ardupilot.org/dev/docs/ros-cartographer-slam.html

mkdir -p ca_catkin_ws/src

sudo apt-get update

sudo apt-get install -y python-wstool python-rosdep ninja-build stow

cd catkin_ws

catkin_init_workspace

cd src

git clone https://github.com/Slamtec/rplidar_ros.git

cd ..








----
----


src/cartographer/scripts/install_abseil.sh

sudo apt-get remove ros-${ROS_DISTRO}-abseil-cpp


sudo apt-get install python-catkin-tools

cd resizeSwapMemory

/setSwapMemorySize.sh -g 10


catkin build

sudo apt-get install ros-melodic-navigation

obal_costmap_params.yaml=====> /map -> map

### command)

cd ca_catkin_ws

source devel/setup.bash

sudo chmod -R 777 /dev/ttyUSB0 

roslaunch rplidar_ros rplidar.launch



cd ca_catkin_ws

source devel/setup.bash

roslaunch cartographer_ros cartographer.launch


roslaunch mavros apm.launch fcu_url:=udp://:14855@


cd ca_catkin_ws

source devel/setup.bash

roslaunch ap_navigation ap_nav.launch

