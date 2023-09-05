cmake_minimum_required(VERSION 3.0.0)
project(tjalib VERSION 0.1.0 LANGUAGES C CXX)

include(CTest)
enable_testing()

file(GLOB_RECURSE TJALIB_SOURCE src/*.cpp src/*.h)
add_library(tjalib ${TJALIB_SOURCE})

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
