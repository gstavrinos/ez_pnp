cmake_minimum_required(VERSION 2.8.3)
project(ez_pnp)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  std_msgs
  std_srvs
  geometry_msgs
  manipulation_msgs
  household_objects_database_msgs
)

catkin_package(
  CATKIN_DEPENDS std_msgs geometry_msgs
)

