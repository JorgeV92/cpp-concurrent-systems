# C++ Concurrency Systems

This repository is dedicated to studying concurrency in C++ based on the textbook *"C++ Concurrency in Action: Practical Multithreading"* (1st Edition) by Anthony Williams. The goal is to dive deep into modern C++ multithreading and parallel programming concepts, exploring real-world examples and practice exercises.

## Table of Contents

1. [Introduction](#introduction)
2. [How to Use This Repo](#how-to-use-this-repo)
3. [Topics Covered](#topics-covered)
    - [Chapter 1: Hello, World of Concurrency](#chapter-1-hello-world-of-concurrency)
    - [Chapter 2: Managing Threads](#chapter-2-managing-threads)
    - [Chapter 3: Sharing Data Between Threads](#chapter-3-sharing-data-between-threads)
    - [Chapter 4: Synchronizing Concurrent Operations](#chapter-4-synchronizing-concurrent-operations)
    - [Chapter 5: The C++ Memory Model and Operations](#chapter-5-cpp-memory-model-and-operations)
    - [...]
4. [Building and Running Code](#building-and-running-code)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

This repository provides a hands-on approach to learning C++ concurrency, following the key topics and examples from the textbook *"C++ Concurrency in Action"*. Each section corresponds to a chapter in the book and includes code examples, exercises, and notes for further study.

## How to Use This Repo

- **Read the book**: Start by reading the corresponding chapters in *C++ Concurrency in Action*.
- **Follow the code**: Each chapter has a folder with code examples that align with the topics covered. Try running and modifying these examples to deepen your understanding.
- **Do the exercises**: In addition to book exercises, this repo includes extra challenges for you to practice C++ concurrency.
- **Contribute**: Feel free to submit pull requests with your own examples, improvements, or alternative solutions.

## Topics Covered

### Chapter 1: Hello, World of Concurrency

- Basics of C++ threads and multithreading.
- Creating and managing threads using `std::thread`.
- Simple "Hello, World" concurrent program.

**Example Code**:  
[chapter1/hello_world.cpp](./chapter1/hello_world.cpp)

### Chapter 2: Managing Threads

- Thread lifecycle management.
- Detaching and joining threads.
- RAII for thread management using `std::thread`.

**Example Code**:  
[chapter2/thread_management.cpp](./chapter2/thread_management.cpp)

### Chapter 3: Sharing Data Between Threads

- Sharing data safely between threads.
- Using mutexes (`std::mutex`), locks (`std::lock_guard`), and unique locks (`std::unique_lock`).
- Thread-safe data structures.

**Example Code**:  
[chapter3/sharing_data.cpp](./chapter3/sharing_data.cpp)

### Chapter 4: Synchronizing Concurrent Operations

- Synchronization techniques using condition variables (`std::condition_variable`).
- Avoiding race conditions and deadlocks.
- Designing concurrent algorithms.

**Example Code**:  
[chapter4/synchronization.cpp](./chapter4/synchronization.cpp)

### Chapter 5: The C++ Memory Model and Operations

- Introduction to the C++ memory model.
- Atomic operations and `std::atomic`.
- Memory ordering and synchronization guarantees.

**Example Code**:  
[chapter5/atomic_operations.cpp](./chapter5/atomic_operations.cpp)

[...]

## Building and Running Code

1. **Requirements**:  
   - C++11 or later compiler (e.g., g++, clang++)
   - CMake for building the examples

2. **Building**:  
   To build the code, use the following commands:

   ```bash
   mkdir build
   cd build
   cmake ..
   make
   ```

3. **Running**:  
   After building, run the examples by executing the compiled binaries:

   ```bash
   ./chapter1/hello_world
   ```

