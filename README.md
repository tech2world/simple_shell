# Simple Shell

Simple Shell is a basic command-line interface that emulates the functionality of a Unix shell. It was developed as a part of the Alx Software Engineering Programme.

## Introduction

This simple shell project aims to replicate the basic functionality of a Unix shell. It provides users with a command-line interface where they can interact with their system by executing commands and running programs.

## Features

- Command execution
- Handling of built-in commands
- Environment variable manipulation
- PATH resolution for executing commands

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Built-in Commands](#built-in-commands)
- [File Descriptions](#file-descriptions)
- [Example](#example)
- [Project Scope](#project-scope)
- [Contribution](#contribution)
- [Authors](#authors)

## Installation

To install and run the simple shell on your system, follow these steps:

1. **Clone Repository**: Clone the repository to your local machine:

    ```bash
    https://github.com/tech2world/simple_shell.git
    ```

2. **Navigate to Directory**: Change to the directory containing the project files:

    ```bash
    cd simple_shell
    ```

3. **Compile Source Files**: Compile the source files into an executable:

    ```bash
    gcc -Wall -Werror -Wextra -pedantic *.c -o simple_shell
    ```

## Usage

To use the simple shell, follow these steps:

1. **Launch Shell**: Run the generated executable to start the shell:

    ```bash
    ./simple_shell
    ```

2. **Enter Commands**: Once the shell is running, you'll be prompted with a command prompt. Enter commands as you would in a regular shell.

## Built-in Commands

The shell supports the following built-in commands:

- `exit`: Exit the shell
- `env`: Print the current environment variables
- `setenv`: Set a new environment variable
- `unsetenv`: Unset an environment variable

## File Descriptions

- **authors**: Contains a list of individuals who contributed to the project.
- **README.md**: Overview of the project, including its purpose, features, and usage instructions.
- **builtins.c**: Implementation of built-in command functions.
- **builtins2.c**: Additional built-in command functions.
- **environment.c**: Functions for managing the shell environment.
- **errors.c**: Functions for printing error messages and handling errors.
- **memory_allocation.c**: Function for reallocating memory.
- **new_strtok.c**: Custom implementation of `strtok` function.
- **path.c**: Functions for executing commands in the PATH.
- **shell.h**: Header file containing function prototypes and struct definitions.
- **simple_shell.c**: Main source file containing the entry point of the shell.
- **strfunc.c**: String manipulation functions.
- **tokenize.c**: Function for tokenizing input.

## Example

Once the Simple Shell is running, you can perform various operations such as:

- Running executable files present in the current directory.
- Listing files in the current directory using the `ls` command.
- Creating directories using the `mkdir` command.
- Moving files between directories using the `mv` command.
- Running processes in the background using the `&` operator.

#### Example Session:

```bash
$ ls
AUTHORS      environment.c  memory_allocation.c  README.md    simple_shell.c
builtins2.c  errors.c       new_strtok.c         shell.h      strfunc.c
builtins.c   file           path.c               simpleshell  tokenize.c

$ mkdir test

$ ls
AUTHORS      environment.c  memory_allocation.c  README.md    simple_shell.c
builtins2.c  errors.c       new_strtok.c         shell.h      strfunc.c
builtins.c   file           path.c               simpleshell  test
```

## Project Scope

The Simple Shell project aims to provide a basic command-line interface similar to traditional Unix shells. While it may not support all features of advanced shells like Bash or Zsh, it includes essential functionalities such as executing commands, handling built-in commands, and basic error handling.

## Contribution

Contributions to the Simple Shell project are welcome! If you have ideas for improvements or bug fixes, feel free to open an issue or submit a pull request on GitHub.

## Authors

- Abdulazeez Ibrahim <abdulazeezibrahim847@gmail.com>
- Tejumade Adedoyin