cmake_minimum_required(VERSION 3.1)
project(intro)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    byteorder.c
    daytimetcpcli.c
    daytimetcpcli1.c
    daytimetcpcli2.c
    daytimetcpcli3.c
    daytimetcpcliv6.c
    daytimetcpsrv.c
    daytimetcpsrv1.c
    daytimetcpsrv2.c
    daytimetcpsrv3.c
    daytimetcpsrvv6.c)

add_executable(intro ${SOURCE_FILES})