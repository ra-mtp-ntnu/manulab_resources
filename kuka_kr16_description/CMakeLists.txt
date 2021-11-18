cmake_minimum_required(VERSION 3.10.2)
project(manulab_resources_kuka_kr16_description)
find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY meshes urdf DESTINATION share/${PROJECT_NAME})
