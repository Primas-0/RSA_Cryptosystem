cmake_minimum_required(VERSION 3.27)
project(RSA_Cryptosystem)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Weffc++ -Werror")
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(RSA_Cryptosystem main.cpp RSA.h RSA.cpp LL.h LL.cpp)