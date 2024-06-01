# ft_printf

ft_printf is a project developed as part of the 42 École curriculum, which involves implementing a simplified version of the standard C library printf function.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Format Specifiers](#format-specifiers)
- [Return Value](#return-value)
- [Contact](#contact)

## Introduction

ft_printf is a custom implementation of the printf function in C, which allows formatting and printing data to the standard output stream or a character string. It supports various format specifiers for printing different data types and modifiers for customizing output formatting.

## Features

- Support for basic format specifiers (`%s`, `%d`, `%c`, `%x`, `%u`, etc.).
- Variable argument handling using the `<stdarg.h>` library.
- Custom flags for formatting output (`-`, `0`, `+`, `#`, `space`).
- Width and precision specifiers for controlling output width and precision.

## Installation

To use the ft_printf function in your project, follow these steps:

1. **Clone the repository**
   ```
   git clone https://github.com/your_username/ft_printf.git
   cd ft_printf

   Include the header file

   #include "ft_printf.h"

Compile your project with the ft_printf function

    gcc -Wall -Wextra -Werror -I./includes your_source_files.c libftprintf.a -o your_executable


## Usage
To use the ft_printf function in your project, call it with a format string and optional arguments:
```
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s!\n", "world");
    return (0);
}
```
## Format Specifiers

ft_printf supports various format specifiers for printing different data types:

    %s: String
    %d or %i: Signed decimal integer
    %c: Character
    %x: Unsigned hexadecimal integer (lowercase)
    %X: Unsigned hexadecimal integer (uppercase)
    %u: Unsigned decimal integer
    %p: Pointer address

Refer to the ft_printf.h header file for a full list of format specifiers and modifiers.

## Return Value
The ft_printf function returns the number of characters printed (excluding the null byte used to terminate output strings). If an error occurs, it returns a negative value.

## Contact
Your Name - your_email@example.com
