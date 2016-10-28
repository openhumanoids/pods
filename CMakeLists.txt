cmake_minimum_required(VERSION 2.8.3)
project(pods)

find_package(catkin REQUIRED)

catkin_package(
  CFG_EXTRAS pods.cmake
)
