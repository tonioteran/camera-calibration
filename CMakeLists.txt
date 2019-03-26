cmake_minimum_required(VERSION 3.13)
project(camera-calibration VERSION 0.0.0 LANGUAGES CXX)

find_package(OpenCV REQUIRED)

add_subdirectory(apps)
