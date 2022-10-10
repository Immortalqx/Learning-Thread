cmake_minimum_required(VERSION 3.20)
project(thread_test)

set(CMAKE_CXX_STANDARD 11)

link_libraries(pthread)

#add_executable(thread_test std_thread/std_thread_demo.cpp)
#add_executable(thread_test pthread/pthread_demo.cpp)
#add_executable(thread_test pthread/pthread_demo1.cpp)
#add_executable(thread_test pthread/pthread_demo2.cpp)
#add_executable(thread_test pthread/pthread_demo3.cpp)
#add_executable(thread_test other/pthread_with_std_thread.cpp)
add_executable(thread_test singleton/test_1.cpp)
#add_executable(thread_test singleton/test_2.cpp)
#add_executable(thread_test singleton/test_3.cpp)
#add_executable(thread_test singleton/test_4.cpp)
