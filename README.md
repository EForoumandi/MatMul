# MatMul

Implement and evaluate the performance of different versions of matrix-matrix multiplication algorithms on a GPU. This reposetory contains:
1- Implementation of a naïve version of the matrix-matrix multiplication algorithm in C++ and measure the performance on a single CPU core.
2- The cblas_dgemm function provided by the Intel MKL library instead of the naïve matrix-matrix multiplication algorithm.
3- Implementation of a simple matrix-matrix multiplication kernel for execution on a GPU.
4- Implementation of the shared memory version of the matrix-matrix multiplication kernel for execution on a GPU.
5- Using the cublasDgemm function provided by the cuBLAS library to perform the matrix-matrix multiplication algorithm on the GPU.
