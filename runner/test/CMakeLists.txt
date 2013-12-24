
include_directories (${SteamEnv_Runner_SOURCE_DIR})
link_directories (${StreamEnv_SOURCE_DIR}/Runner)

file(GLOB_RECURSE src RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} *.cpp *.h)

add_executable (Runner_Test ${src})
target_link_libraries (Runner_Test Runner)

