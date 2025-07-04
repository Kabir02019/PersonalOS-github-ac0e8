# Kabir OS - Advanced Program Loader

## Overview

The Advanced Program Loader is a sophisticated component of **Kabir OS**, developed by **Kabir Khanna**. This implementation employs lazy loading strategies similar to modern operating systems like Linux, loading program segments into memory only when needed during execution.

## Features

- **Lazy Loading**: Page-by-page allocation approach for efficient memory usage
- **Page Fault Management**: Advanced handling of multiple page faults
- **ELF Compatibility**: Works exclusively with 32-bit ELF executables
- **Zero Dependencies**: No standard glibc APIs required
- **Memory Optimization**: Avoids upfront bulk loading

## Building and Running

```bash
cd starter/without-bonus
make
./loader fib
```

## Architecture

This component implements advanced OS memory management concepts including:
- Demand paging
- Page fault handling
- Memory mapping
- Lazy allocation strategies

## Advanced Features

- **On-Demand Loading**: Programs are loaded only when accessed
- **Memory Efficiency**: Optimized memory usage through lazy allocation
- **Fault Tolerance**: Robust error handling for memory operations
- **Performance Optimization**: Reduced initial load times

## Supported Programs

The advanced loader can execute various test programs:
- `fib.c` - Fibonacci calculation
- `sum.c` - Sum calculation
- Custom ELF executables

**Developed by: Kabir Khanna**
**Component: Advanced Program Loader - Kabir OS** 