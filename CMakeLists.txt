# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly

cmake_minimum_required(VERSION 3.8) # CPP 17 support starts at v3.8

set(CMAKE_CXX_STANDARD 17)

#set(EXTRA_COMPONENT_DIRS $ENV{IDF_PATH}/examples/common_components/protocol_examples_common application core)
set(EXTRA_COMPONENT_DIRS application core)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

project(greenGiant)