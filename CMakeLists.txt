cmake_minimum_required(VERSION 3.17)
project(tests LANGUAGES C ASM)

set(CMAKE_C_STANDARD 99)

if (IS_DIRECTORY ${STUDENT_DIR})
    add_subdirectory(${STUDENT_DIR})
endif()
