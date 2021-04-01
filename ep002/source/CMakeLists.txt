cmake_minimum_required(VERSION 3.5)
project(helloApp
        VERSION 0.0.1
        DESCRIPTION "The leading Hello world app"
        LANGUAGES CXX)
add_executable(helloAppBynary main.cpp)
target_compile_features(helloAppBynary PRIVATE cxx_std_20)
