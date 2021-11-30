cmake_minimum_required(VERSION 3.0.2)
project(rtabmap_robot2_fie)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
 ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY launch/ 
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

