cmake_minimum_required(VERSION 3.16)
project(findpackage)
message(STATUS "CMAKE_MODULE :${CMAKE_MODULE_PATH}")
find_package(CUDA REQUIRED)
if(CUDA_FOUND)
message(STATUS "CUDA INCLUDE PATH :${CUDA_INCLUDE_DIRS}")
else()

endif()
