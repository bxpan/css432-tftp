cmake_minimum_required(VERSION 3.26)
project(css432_tftp)

set(CMAKE_CXX_STANDARD 17)

add_executable(tftp-client TftpClient.cpp)
add_executable(tftp-server TftpServer.cpp)
