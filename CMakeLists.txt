cmake_minimum_required (VERSION 3.2)
project (StatsdClient)

set (StatsdClient_VERSION_MAJOR 1)
set (StatsdClient_VERSION_MINOR 0)

include_directories ("src")
add_subdirectory ("src")

target_compile_features(StatsdClient PRIVATE cxx_nullptr)
