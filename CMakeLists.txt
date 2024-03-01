cmake_minimum_required(VERSION 3.27)
project(LBMTopo CUDA)

set(CMAKE_CUDA_STANDARD 17)

add_executable(LBMTopo main.cu)

set_target_properties(LBMTopo PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
