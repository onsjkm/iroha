addtest(synchronizer_test synchronizer_test.cpp)
target_link_libraries(synchronizer_test
    synchronizer
    shared_model_cryptography
    shared_model_proto_backend
    )


