cmake_minimum_required(VERSION 3.5)
project(ing-to-ynab-converter)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wextra")

set(SOURCE_FILES
    main.c)

add_executable(ing-to-ynab-converter ${SOURCE_FILES})

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "F:/Dropbox/Programmeren/Clion_output")
