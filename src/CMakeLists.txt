cmake_minimum_required(VERSION 3.0)
project(Test)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(main main.cpp)
target_link_libraries(main ${OpenCV_LIBS})


#set(LIBS -lopencv_core -lopencv_imgproc -lopencv_highgui)
#set(FLAGS -I/usr/local/include/opencv4 -L/usr/local/lib)
