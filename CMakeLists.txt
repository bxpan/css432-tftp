cmake_minimum_required(VERSION 3.26)
project(css432_tftp)

set(CMAKE_CXX_STANDARD 17)

add_executable(css432_tftp main.cpp)
add_executable(TftpClient TftpClient.cpp)
add_executable(TftpServer TftpServer.cpp)
