cmake_minimum_required(VERSION 3.0.0)
project(Ex1 VERSION 0.1.0)

include(CTest)
enable_testing()

set(C_STANDARD C99)
<<<<<<< HEAD
add_compile_options(-Wall -Wextra -pedantic -Werror)
=======
>>>>>>> f5eaa17efad45512c6522c201732c97bca09d70d
add_library(Ex1 SHARED Matrix.c ErrorCode.c)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
