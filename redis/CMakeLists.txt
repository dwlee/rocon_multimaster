##############################################################################
# CMake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(redis)

##############################################################################
# Catkin
##############################################################################

find_package(catkin REQUIRED)
catkin_package()

catkin_python_setup()
