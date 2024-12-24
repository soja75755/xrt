include_directories("${CMAKE_CURRENT_SOURCE_DIR}")

set(xrt_SRCS
    datareader.cpp)

set(LIBRARY_OUTPUT_PATH ${ncnn_lession1_BINARY_DIR/src_lib/})
add_library(xrt STATIC ${xrt_SRCS})
