# Define test executable name
set(TEST_EXECUTABLE_NAME comms_protocol_test_harness_tests)

# Add test source files
set(TEST_SOURCES
    test.cpp
)

# Define test executable target
add_executable(${TEST_EXECUTABLE_NAME} ${TEST_SOURCES})
