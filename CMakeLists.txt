cmake_minimum_required(VERSION 2.8)
project( cam )
find_package( OpenCV REQUIRED )
add_executable( cam cam.cpp 9.png)
target_link_libraries( cam ${OpenCV_LIBS} )
