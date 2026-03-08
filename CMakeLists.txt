cmake_minimum_required(VERSION 3.10)
project(paravia LANGUAGES C)

add_executable(paravia paravia.c)
set_property(TARGET paravia PROPERTY C_STANDARD 99)
