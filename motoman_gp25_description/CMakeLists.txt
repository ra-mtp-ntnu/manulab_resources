cmake_minimum_required(VERSION 3.10.2)
project(motoman_gp25_description)

find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY launch meshes urdf DESTINATION share/${PROJECT_NAME})
