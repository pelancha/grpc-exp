cmake_minimum_required(VERSION 3.8)
project(grpc_exp VERSION 0.1.0 LANGUAGES C CXX)


include(./cmake/common.cmake)
add_subdirectory(proto)
add_subdirectory(apps)


