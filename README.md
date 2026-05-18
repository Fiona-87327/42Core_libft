# 42Core_libft

A comprehensive C library implementation created as part of the 42 School curriculum.

## Overview

`libft` is a foundational library that implements standard C library functions and provides utility functions commonly used in C programming. This project reinforces understanding of memory management, data structures, and function implementation in C.

## Features

- **Standard C Library Functions**: Implementations of functions from `<ctype.h>`, `<string.h>`, `<stdlib.h>`, etc.
- **String Manipulation**: Functions for string searching, copying, concatenation, and modification
- **Memory Management**: Custom memory allocation and manipulation functions
- **List Operations**: Linked list implementation with creation, deletion, and iteration functions
- **Character Type Checking**: Character classification functions

## Project Structure

```
libft/
├── libft.h           # Main header file with function declarations
├── Makefile          # Build configuration
├── ft_*.c            # Individual function implementations
└── ...
```

## Usage

Include the header file in your project:

```c
#include "libft.h"
```

## Key Functions

### String Functions
- `ft_strlen` - Get string length
- `ft_strcpy` - Copy string
- `ft_strdup` - Duplicate string
- `ft_strcat` - Concatenate strings
- `ft_substr` - Extract substring
- `ft_strtrim` - Trim whitespace

### Memory Functions
- `ft_memset` - Fill memory with a value
- `ft_memcpy` - Copy memory area
- `ft_memmove` - Move memory area
- `ft_bzero` - Zero out memory

### Character Functions
- `ft_isalpha` - Check if alphabetic
- `ft_isdigit` - Check if digit
- `ft_isalnum` - Check if alphanumeric
- `ft_toupper` - Convert to uppercase
- `ft_tolower` - Convert to lowercase

### Utility Functions
- `ft_atoi` - Convert string to integer
- `ft_itoa` - Convert integer to string
- `ft_split` - Split string into array
- `ft_strjoin` - Join two strings

### List Operations
- `ft_lstnew` - Create new list node
- `ft_lstadd_front` - Add node to front
- `ft_lstsize` - Get list size
- `ft_lstmap` - Apply function to list

## Requirements

- GCC or compatible C compiler
- Standard C library

## Installation

1. Clone the repository:
```bash
git clone https://github.com/jiyan-0525/42Core_libft.git
cd 42Core_libft
```

3. Link it with your projects by including `libft.h` and using `-lft` during compilation.

## Testing

To test individual functions, you can create test programs that call the library functions and verify their behavior against standard C library implementations.

## Learning Outcomes

Through this project, you'll gain:
- Deep understanding of C standard library functions
- Memory management practices
- Data structure implementation (linked lists)
- Makefile usage and compilation
- Code organization and modularization

## 42 School

This project is part of the 42 School curriculum, a project-based coding school that emphasizes peer learning and practical programming skills.

## License

Created as part of 42 School curriculum.

## Contributing

This is a personal school project. However, feedback and suggestions for improvements are welcome!

---
