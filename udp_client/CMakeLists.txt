add_executable(client client.c)

if (WIN32)
    target_link_libraries(client w2_32)
endif()