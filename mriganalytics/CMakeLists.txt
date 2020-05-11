# CMakeList.txt : CMake project for mriganalytics, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (mriganalytics "mriganalytics.cpp" "mriganalytics.h")
include_directories ("F:\\Mrig Analytics\\cpp\\libpqxx\\include")
# TODO: Add tests and install targets if needed.
