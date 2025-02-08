cmake_minimum_required(VERSION 3.10)
project(HelloWorld)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(main
    src/main.cpp

    # 其他源文件
    # src/other.cpp
    # src/another.cpp
)

# 如果有头文件目录，可以这样添加
# include_directories(include)