cmake_minimum_required(VERSION 3.10)
project(comms_protocol_test_harness)

# Set C++ standard to c++11
set(CMAKE_CXX_STANDARD 11)

# Add subdirectory for source code
add_subdirectory(src)

# Add subdirectory for tests
add_subdirectory(tests)

# Add subdirectory for external dependencies
add_subdirectory(include)
