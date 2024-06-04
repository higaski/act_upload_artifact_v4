cmake_minimum_required(VERSION 3.25 FATAL_ERROR)
include(FetchContent)

project(Pitchfork LANGUAGES C CXX)

add_executable(test_artifact_v4 src/main.cpp)
