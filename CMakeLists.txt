cmake_minimum_required(VERSION 2.8.3)
project(blurr_control)

set(CMAKE_CXX_STANDARD 11)

find_package(catkin REQUIRED COMPONENTS
  sensor_msgs
  nav_msgs
  roscpp
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES blurr_control
#  CATKIN_DEPENDS   sensor_msgs  nav_msgs  roscpp
#  DEPENDS system_lib
)

###########
## Build ##
###########

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)