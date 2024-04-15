# Multithreading-102117102

The "Matrix Multiplication Performance Benchmark" project evaluates the impact of multi-threading on matrix multiplication tasks. Using Python libraries like NumPy, threading, and Pandas, the project generates random matrices and measures the execution time of matrix multiplication with varying numbers of threads (1 to 8). The results are analyzed and visualized to understand how concurrency affects performance. This project offers insights into optimizing computational tasks involving matrix operations.

Function explanation:
1. **generate_random_matrices(n, size)**:
   - Generates `n` random matrices of size `size x size`.

2. **multiply_matrices(matrices)**:
   - Multiplies a list of matrices together, starting with a constant matrix.

3. **perform_multiplication_with_threads(num_threads)**:
   - Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

