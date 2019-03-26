add_executable(stereoCalib stereoCalib.cpp)
target_link_libraries(stereoCalib PRIVATE ${OpenCV_LIBS})
