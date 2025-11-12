# Libft
A custom C library recreating standard libc functions.  
This is the **first project at 1337 (42 Network) school**.

## Build
`make` → creates `libft.a` | `make clean/fclean/re` for cleanup.

## Functions
Reimplemented: `strlen`, `strcpy`, `atoi`, `memset`, etc.  
Added: linked list utilities (`ft_lstnew`, `ft_lstadd_front`, `ft_lstclear`, ...).

## Usage
`#include "libft.h"` then compile with `gcc main.c -L. -lft`
