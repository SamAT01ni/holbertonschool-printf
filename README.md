# Welcome to the first group project, _printf

## Description

Code written by Lachlan Luchetti and Sam Thompson. 

lachlan.luchetti@holbertonstudents.com and sam.thompson@holbetonstudents.com

This project is a basic version of the printf function replicated to handle the conversion specifies:
- %c : chars
- %s : strings
- %% : percentage signs
- %d : digits
- %i : integers

---

## Compilation

Used gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o _printf to compile all files

---

## Requirements
- Ubuntu 2-.04 LTS
- only allowed vi, vim and emacs editors
- compiled using -Wall -Werror -Wextra -pedantic -std=gnu89
- no more than 5 functions per file
- header file names main.h

## Examples of using the code

Hello world
```
#include "main.h"

int main(void)
{
	_printf("Hello %s\n", "world");
	return (0);
}
```
Output will be 
```
Hello world
```

The code sees the %s and can pass it as a string, writing each character in it using stdout.
