
set(target unittests)

add_executable(${target} ${CMAKE_CURRENT_SOURCE_DIR}/ExampleTest.cc)
target_link_libraries(${target} ${CONAN_LIBS})

add_test(NAME ${target} COMMAND ${target})
