# 1. 规定 CMake 的最低版本要求 (防止旧版本不兼容)
cmake_minimum_required(VERSION 3.10)

# 2. 给你的项目起个名字 (作业叫 C2Cpp，我们就叫这个)
project(C2Cpp)

# 3. 设置 C++ 标准 (比如用 C++17，现代化一点)
set(CMAKE_CXX_STANDARD 17)

# 4. 核心命令：告诉 CMake，把 main.cpp 编译成一个叫 MyExe 的可执行程序
# 格式：add_executable(程序名 源代码文件1 源代码文件2 ...)
add_executable(MyExe main.cpp)