cmake_minimum_required(VERSION 3.0.0)

project(tcpClient)

add_executable(${PROJECT_NAME}
./main.cpp
)

target_include_directories(${PROJECT_NAME} PUBLIC
)

target_link_libraries(${PROJECT_NAME} PUBLIC
    -lwiringPi
)

target_compile_options(${PROJECT_NAME} PUBLIC
    -Wall
)