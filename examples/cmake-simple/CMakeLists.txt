cmake_minimum_required(VERSION 3.10.0)

# Set the project name
project(cmake-simple)

# Set the C standard to C99
set(CMAKE_C_STANDARD 99)

# Use the project name and define all the source files
add_executable(cmake-simple
        src/main.c
        # ...
)