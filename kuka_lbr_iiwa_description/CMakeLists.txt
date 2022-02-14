cmake_minimum_required(VERSION 3.5)
project(kuka_lbr_iiwa_description)

find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY config launch meshes urdf
  DESTINATION share/${PROJECT_NAME})