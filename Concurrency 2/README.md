# Concurrent Matrix Multiplication

## Introduction

Welcome to the **Concurrent Matrix Multiplication** project, where we delve into parallel computing techniques to efficiently perform matrix multiplication.

## Project Purpose

The primary objective of this project was to harness the power of parallel computing to accelerate the matrix multiplication process. By utilising multithreading, I aimed to showcase the advantages of parallelisation in reducing execution time for matrix operations.

## Key Features

**Efficient Thread Management:** In this project, I implemented multithreading to perform parallel matrix multiplication. Each thread handles a designated portion of the matrix multiplication, allowing computations to occur concurrently and enhancing overall performance.

**Shared Buffer Strategy:** In Project 1, I introduced a mechanism to share the matrix data buffer between threads without causing interference. This approach enabled threads to operate on separate portions of the buffer simultaneously, eliminating data contention issues.

**Synchronisation Techniques:** Project 2 involved more advanced synchronisation. Threads dynamically request sections of the buffer to work on, ensuring efficient utilisation of resources while avoiding conflicts. Synchronisation mechanisms were strategically applied to ensure orderly access to shared resources.

## Getting Started

To explore the capabilities of this project, follow these steps:

1. Initialise the matrix buffer containing the matrices to be multiplied.
2. Create threads, assigning each a specific section of the matrix buffer and the number of matrices to process.
3. Implement matrix multiplication within each thread, storing the results in a designated internal buffer.
4. Monitor thread runtimes using timing mechanisms to analyse performance.
5. Evaluate the impact of different thread counts and buffer section sizes on execution time.
6. Analyse the efficiency of thread synchronization mechanisms.

## Discussion and Experimentation

For a comprehensive understanding of the project's outcomes, consider the following points:

1. **Thread Count Impact:** Experiment with varying thread counts to observe their effect on execution time. Compare results between different numbers of threads (e.g., 1000 vs. 10000) and analyse the reasons behind the outcomes.
2. **Matrix Dimensions:** Investigate the influence of matrix dimensions on execution time. Compare the performance of different matrix sizes, such as 4x4 and 8x8, and determine if the results align with expectations.
3. **Sleep Duration Experiment:** Explore the impact of introducing short sleep periods (e.g., 10ms) within threads. Assess whether this affects execution time and overall performance.

