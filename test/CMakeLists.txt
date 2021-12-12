# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (Demo3)

#指定引用目录，以下两个子目录都会使用到，故放在最下面会有问题
include_directories(source)
# 添加 math 子目录
add_subdirectory(source)
add_subdirectory(user)
