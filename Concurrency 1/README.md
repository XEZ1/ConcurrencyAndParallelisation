# Parallel Mean Computation

## Introduction

Welcome to the Parallel Mean Computation project, where we explore the efficiency of parallelising a task using threads to calculate the mean value of a list of numbers.

## Project Purpose

The primary goal of this project was to leverage the power of parallel computing to enhance the performance of calculating the mean of a large list of numbers. By splitting the task into smaller units and executing them concurrently, I aimed to demonstrate the benefits of parallelisation in optimising computation time.

## Key Features

**Thread-based Computation:** In this project, I utilised Java's threading capabilities to divide the input data into slices, each processed by a separate thread. This approach allows the computation of means to occur simultaneously, significantly reducing the overall execution time for large datasets.

**Data Slicing and Distribution:** To maximise parallelisation, I strategically sliced the input array into equal-length segments, distributing them to individual threads. This ensured balanced workloads for each thread, contributing to efficient resource utilisation.

**Performance Experimentation:** A crucial aspect of this project was experimenting with different thread counts to evaluate the extent of parallelisation efficiency. By running the computation with varying numbers of threads, I gathered timing data to empirically identify the optimal thread count that minimises the overall task runtime. These experiments provided insights into the performance characteristics of the underlying hardware and operating system.

## Getting Started

To replicate and explore the capabilities of this project, follow these steps:

1. Set up the input data using the provided class to generate a list of BigInteger numbers.
2. Create data slices by splitting the input array into equal segments, ready for parallel processing.
3. Instantiate threads, each responsible for calculating the mean of a data slice.
4. Start all threads concurrently and wait for their completion.
5. Combine the results from each thread to compute the overall mean of the entire list.
6. Output the calculated mean to the console.

## Extension and Performance Analysis

For an extended challenge, the project offers the ability to gather runtime data for multiple runs with varying thread counts. By analysing the runtimes for different thread configurations, we gain insights into the efficiency of parallelisation on different hardware and operating systems.