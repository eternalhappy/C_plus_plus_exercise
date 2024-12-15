# 设置最低的 CMake 版本要求
cmake_minimum_required(VERSION 3.10)

# 设置项目名称
project(StudentManagement)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 11)

# 包含源文件
set(SOURCE_FILES
    src/student.cpp
    src/studentmain.cpp
)

# 定义可执行文件
add_executable(student_management ${SOURCE_FILES})
