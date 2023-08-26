# Concurrent Access Control and Semaphore Usage

## Introduction

Welcome to the **Concurrent Access Control and Semaphore Usage** project, where we explore the efficient control of concurrent access using semaphores. In this project, I demonstrate practical implementation of synchronisation mechanisms and explore the producer-consumer pattern to manage shared resources.

## Project Purpose

The main objective of this project was to leverage semaphores for concurrent access control, demonstrating the advantages of utilising synchronisation techniques to manage shared resources effectively. 

## Key Features

**Semaphore-based Control:** Through this project, I showcase the use of semaphores to facilitate controlled access in concurrent scenarios. By employing semaphores, I ensure orderly access to shared resources, preventing data conflicts and enhancing the overall reliability of the application.

**Dining Philosophers Solution:** In Project 1, I implement the dining philosophers problem using binary semaphores for fork access control. I present a solution that allows philosophers to acquire forks while ensuring only one philosopher can access a fork at a time. I extend this solution to demonstrate philosophers' ability to both think and eat concurrently.

**Producer-Consumer Pattern:** Project 2 explores the producer-consumer pattern, a common scenario in concurrent programming. I implement a system where producers generate computations and consumers evaluate them. The key challenge is to control access to a shared buffer using semaphores, managing the concurrent interaction between producers and consumers.

## Getting Started

To delve into the features of this project, follow these steps:

1. Study the conversion of the dining philosophers solution to use binary semaphores for fork access control.
2. Explore the implementation of the producer-consumer pattern using semaphores to manage shared buffer access.
3. Experiment with different buffer sizes, numbers of producers and consumers, and other parameters to observe their impact on system throughput.

## Discussion and Experimentation

To gain a comprehensive understanding of the project's outcomes, consider these points:

1. **Semaphore Efficiency:** Observe how the use of semaphores enhances concurrent access control. Analyse the behavior of philosophers in the dining philosophers problem and producers-consumers in the producer-consumer pattern.
2. **Impact of Parameters:** Experiment with various parameters such as buffer sizes, numbers of producers and consumers, and numbers of slices. Evaluate the influence of these parameters on system throughput and overall performance.
