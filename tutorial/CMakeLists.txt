add_executable(client client.cpp)
add_executable(cloud cloud.cpp)
add_executable(client_ntt client_ntt.cpp)
add_executable(cloud_ntt cloud_ntt.cpp)
add_executable(verify verify.cpp)
target_link_libraries(client tfhe++)
target_link_libraries(cloud tfhe++)
target_link_libraries(client_ntt tfhe++)
target_link_libraries(cloud_ntt tfhe++)
target_link_libraries(verify tfhe++)