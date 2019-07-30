cmake_minimum_required(VERSION 2.6)
project(feature_point_match)

add_executable(feature_point_match main.cpp)

install(TARGETS feature_point_match RUNTIME DESTINATION bin)
