cmake_minimum_required(VERSION 3.13)
include(pico_sdk_import.cmake)
project(recycler C CXX ASM)

pico_sdk_init()

add_executable(recycler
	src/main.cpp
)

target_link_libraries(recycler pico_stdlib)

pico_add_extra_outputs(recycler)
pico_enable_stdio_usb(recycler 1)
pico_enable_stdio_uart(recycler 0)
