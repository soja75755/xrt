macro(xrt_add_test name)
    add_executable(${name} ${name}.cpp)
    target_link_libraries(${name} PRIVATE xrt)
endmacro()

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../src)
xrt_add_test(test_datareader)
