# Kabir OS - Command Shell

## Overview

The Command Shell is a robust command-line interpreter component of **Kabir OS**, developed by **Kabir Khanna**. This implementation demonstrates advanced command processing, pipeline execution, and system call management in a Unix-like environment.

## Features

- **Command Execution**: Full compatibility with existing Unix commands
- **Pipeline Support**: Advanced implementation for command chaining
- **Daemon Process Creation**: Sophisticated background process management
- **Signal Handling**: Robust termination and interrupt handling

## Building and Running

```bash
# Basic version
gcc -o shell without_bonus.c
./shell

# Advanced version with bonus features
gcc -o shell_advanced with_bonus.c
./shell_advanced
```

## Architecture

This component implements core OS I/O management concepts including:
- Command interpretation and parsing
- Process creation and management
- File descriptor handling
- Signal processing

## Example Usage

```bash
# Basic command execution
ls -la

# Pipeline execution
ls | grep .c | wc -l

# Background process
sleep 10 &
```

**Developed by: Kabir Khanna**
**Component: Command Shell - Kabir OS**