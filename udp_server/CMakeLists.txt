add_executable(server server.c)

if (WIN32)
    target_link_libraries(server w2_32)
endif()