cmake_minimum_required(VERSION 3.14)
project(dailyneighbours)

set(CMAKE_CXX_STANDARD 17)

add_executable(dailyneighbours main.cpp solver.h cell.h solver_helpers.cpp solver_backtrack.cpp solver_logic.cpp)