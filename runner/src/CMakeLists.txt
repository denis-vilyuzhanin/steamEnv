

file(GLOB_RECURSE src RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} *.cpp *.h)

include_directories ("${CMAKE_CURRENT_SOURCE_DIR}")
add_library (Runner ${src})
