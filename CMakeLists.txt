cmake_minimum_required(VERSION 3.0.2)
project(fetch_gazebo_visualservoing)

find_package(catkin REQUIRED COMPONENTS
    gazebo_ros
)


catkin_package(
    CATKIN_DEPENDS gazebo_ros
)

catkin_install_python(PROGRAMS scripts/simulation.py
    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

include_directories(
# include
${catkin_INCLUDE_DIRS}
)

