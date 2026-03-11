cmake_minimum_required(VERSION 3.21)
project(SetoPlugins VERSION 1.0)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(JUCE)
add_subdirectory(plugins/smack/generated)
