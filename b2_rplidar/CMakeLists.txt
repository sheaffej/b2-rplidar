cmake_minimum_required(VERSION 2.8.3)
project(b2_rplidar)

find_package(catkin REQUIRED COMPONENTS)
catkin_package()

# Install files
install(DIRECTORY launch param
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

