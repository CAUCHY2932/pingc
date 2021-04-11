# action for lowcase, words special for upcase
# project CMakeLists.txt for guide
cmake_minimum_required(VERSION 3.8) # version

set(This ping) # declare a var, this = ping

project(${This} C CXX)

set(CMAKE_C_STANDARD 99) # compile version
set(CMAKE_CXX_STANDARD 11) # compile version
set(CMAKE_POSITION_INDEPENDENT_CODE on) # position independent

enable_testing() # for testing

# add_subdirectory() # add subdirectory
# add_subdirectory(test/ut) # this will build and test
add_subdirectory(source)


