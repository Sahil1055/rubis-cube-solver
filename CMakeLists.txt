cmake_minimum_required(VERSION 3.25)
project(Rubik_s_Cube_Solver)

set(CMAKE_CXX_STANDARD 17)

add_executable(Rubik_s_Cube_Solver main.cpp GenericRubiksCube.cpp GenericRubiksCube.h cmake-build-debug/Solver/BFSSolver.h Solver/BFSSolver.h RubiksCube3dArray.cpp RubiksCube3dArray.cpp RubiksCube3dArray.cpp)
