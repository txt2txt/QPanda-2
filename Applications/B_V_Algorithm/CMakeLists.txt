cmake_minimum_required(VERSION 3.1)
project(B_V_Algorithm)
file(GLOB_RECURSE BV_CPP ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp )
add_executable(${PROJECT_NAME} ${BV_CPP})
target_link_libraries(${PROJECT_NAME} ${LIB_QALG})
