add_library(ttddbg_test_dll SHARED test_dll.cc)
target_compile_features(ttddbg_test_dll PRIVATE cxx_std_17)

add_executable(ttddbg_test_multithread test_multithread.cc)
target_compile_features(ttddbg_test_multithread PRIVATE cxx_std_17)

add_executable(ttddbg_test_exceptions test_exceptions.cc)
target_compile_features(ttddbg_test_exceptions PRIVATE cxx_std_17)
