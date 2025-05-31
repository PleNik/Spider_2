cmake_minimum_required(VERSION 3.20)

add_executable(HttpClientApp httpClient.cpp httpClient.h)

#target_compile_features(httpClientApp PRIVATE cxx_std_17)