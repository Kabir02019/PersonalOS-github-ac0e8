# Kabir OS - Basic Program Loader

## Overview

The Basic Program Loader is a fundamental component of **Kabir OS**, developed by **Kabir Khanna**. This implementation focuses on loading and executing 32-bit ELF executables, serving as the foundation for understanding program loading and memory management concepts.

## Features

- **ELF Executable Support**: Loads 32-bit ELF format programs
- **Memory Management**: Basic memory allocation and segment loading
- **Error Handling**: Robust error detection and reporting
- **Educational Design**: Clear implementation for learning OS concepts

## Building and Running

```bash
cd starter/without-bonus
make
./loader fib
```

## Architecture

This component implements core OS memory management concepts including:
- Program header parsing
- Memory segment allocation
- Entry point calculation
- Basic error handling

## Supported Programs

The loader can execute various test programs:
- `fib.c` - Fibonacci calculation
- Custom ELF executables

**Developed by: Kabir Khanna**
**Component: Basic Program Loader - Kabir OS**
