cmake_minimum_required(VERSION 3.21)
project(CUDA-Easier-Introduction CUDA)

set(CMAKE_CUDA_STANDARD 23)

add_executable(CUDA-Easier-Introduction main.cu)

set_target_properties(CUDA-Easier-Introduction PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
