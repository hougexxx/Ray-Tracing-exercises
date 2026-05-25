#需求的最低cmake程序版本
cmake_minimum_required(VERSION 3.12)

#本工程的名称
project(OpenGL)

#本工程支持的C++版本
set(CMAKE_CXX_STANDARD 17)

#搜索当前目录下面的cpp文件用来合成为SRCS  
aux_source_directory(. SRCS)

#本工程主程序文件及输出程序名称
add_executable(Raytracing ${SRCS})

