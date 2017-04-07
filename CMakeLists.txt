cmake_minimum_required(VERSION 3.7)
project(MyTestHttpModule)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES ngx_http_mytest_module.c)
add_executable(MyTestHttpModule ${SOURCE_FILES})