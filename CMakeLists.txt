cmake_minimum_required(VERSION 3.12)

project(img-dup)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_AUTOMOC ON)

find_package(Qt5Widgets CONFIG REQUIRED)
find_package(Boost COMPONENTS filesystem REQUIRED)
find_package(OpenCV REQUIRED)

include_directories(include)
add_subdirectory(src)