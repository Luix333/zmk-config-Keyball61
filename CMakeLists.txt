cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(zmk-config-keyball61)

# Add include path for dummy header
zephyr_include_directories(${CMAKE_CURRENT_SOURCE_DIR}/config/include)
