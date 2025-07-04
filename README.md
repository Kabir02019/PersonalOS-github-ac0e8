# Kabir OS - Operating System Implementation

## Project Overview

**Kabir OS** is a comprehensive operating system implementation project developed by **Kabir Khanna** as part of a hands-on learning experience in system-level programming and operating systems concepts. This project demonstrates the implementation of core OS components from the ground up, providing a deep understanding of how modern operating systems function at their fundamental level.

---

### Process Scheduler

**Description:**
The Process Scheduler is a sophisticated CPU scheduler written in C, designed to simulate advanced CPU time-sharing by managing multiple processes across a limited number of CPU cores. It employs a priority-based scheduling policy where processes receive a set quantum of execution time before being placed back into the ready queue.

**Features:**
- Processes can be assigned a priority level from 1 to 4, with a default priority of 1 if none is specified.
- Uses an advanced heuristic to determine how a process's priority affects its execution order.
- Generates comprehensive statistical output to demonstrate how different priority levels impact job scheduling and execution.

**Usage:**
Detailed instructions on how to compile and run the Process Scheduler will be provided in the project directory.

---

### Command Shell

**Description:**
The Command Shell is a robust command-line interpreter that runs in a loop, processing user commands, executing them, and waiting for more input until a termination signal (Ctrl-C) is received. This project serves as a practical exercise in managing system calls related to process handling in a Unix-like environment.

**Features:**
- Executes existing Unix commands with full compatibility.
- Supports advanced pipeline implementation to facilitate the execution of multiple commands at once.
- Includes sophisticated functionality for creating daemon processes.

**Usage:**
Detailed instructions on how to compile and run the Command Shell will be provided in the project directory.

---

### Advanced Program Loader

**Description:**
The Advanced Program Loader enhances the basic loader implementation, evolving it into a sophisticated program loader. This loader is considered "advanced" because it employs a lazy loading strategy, similar to modern operating systems like Linux, loading program segments into memory only when needed during execution.

**Features:**
- Avoids upfront bulk loading, using a page-by-page allocation approach.
- Manages multiple page faults efficiently with advanced error handling.
- Works exclusively with 32-bit ELF executables without using any standard glibc APIs.

**Usage:**
Detailed instructions on how to compile and run the Advanced Program Loader will be provided in the project directory.

---

### Multithreading Framework

**Description:**
The Multithreading Framework is a comprehensive implementation of multithreading concepts in C. It demonstrates how to create, manage, and synchronize multiple threads within a program, providing a foundation for concurrent programming.

**Features:**
- Advanced creation and management of multiple threads.
- Robust synchronization mechanisms to avoid race conditions and ensure thread safety.
- Performance optimization techniques for thread management.

**Usage:**
Detailed instructions on how to compile and run the Multithreading Framework will be provided in the project directory.

---

### Basic Program Loader

**Description:**
The Basic Program Loader is a fundamental program loader that focuses on loading and executing 32-bit ELF executables. This project serves as an introduction to the concepts of program loading and memory management, providing the foundation for more advanced loader implementations.

**Features:**
- Loads program segments into memory for execution with proper error handling.
- Basic memory management without the advanced features of the Advanced Program Loader.
- Educational implementation for understanding program loading concepts.

**Usage:**
Detailed instructions on how to compile and run the Basic Program Loader will be provided in the project directory.

---

## Getting Started

### Prerequisites

- GCC Compiler
- Make (optional, for ease of compilation)
- Unix-like operating system (Linux, macOS, etc.)

### Installation

Clone the repository to your local machine:
```bash
git clone https://github.com/KabirKhanna/Kabir-OS
cd Kabir-OS
```

### Building Kabir OS Components

Each component can be built independently. Navigate to the respective directory and use the provided Makefiles:

```bash
# Build Process Scheduler
cd Process_Scheduler
make

# Build Command Shell
cd Command_Shell/OS-ASS-2-main
make

# Build Advanced Program Loader
cd Advanced_Loader/starter/without-bonus
make

# Build Multithreading Framework
cd multithreading/upload
make

# Build Basic Program Loader
cd Basic_Loader/starter/without-bonus
make
```

## Architecture Overview

Kabir OS implements the following core operating system concepts:

1. **Process Management**: CPU scheduling, process creation, and context switching
2. **Memory Management**: Program loading, memory allocation, and page fault handling
3. **I/O Management**: Command interpretation and system call handling
4. **Concurrency**: Thread creation, synchronization, and parallel execution

## Contributing

This project is developed by **Kabir Khanna** as an educational implementation of operating system concepts. The code is designed to be educational and demonstrate fundamental OS principles.

## License

This project is for educational purposes and demonstrates the implementation of core operating system concepts from the ground up.

---

**Developed by: Kabir Khanna**
**Project: Kabir OS - Operating System Implementation**
