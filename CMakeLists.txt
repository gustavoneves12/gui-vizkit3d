# CMakeLists.txt has to be located in the project folder and cmake has to be
# executed from 'project/build' with 'cmake ../'.
cmake_minimum_required(VERSION 2.6)
find_package(Rock)
rock_init(vizkit3d 1.0)

rock_find_cmake(Boost REQUIRED COMPONENTS thread system)
rock_standard_layout()
