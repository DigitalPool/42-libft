# Libft: Your Essential C Toolbox for 42 Projects 🛠️

Welcome to **Libft**, your very own custom C library that will serve as the foundation for many future projects in the 42 curriculum! Think of it as your ultimate toolkit, filled with hand-crafted functions that simplify your coding life. This library covers everything from handling characters and strings to managing memory, plus advanced features like linked lists. Get ready to conquer C with your unique set of tools!

## 🚀 Project Structure

### `.c` Files  
Where the magic happens! Every function you build goes into a `.c` file, each designed to perform a specific task efficiently. These functions will be your go-to helpers as you progress through 42.

### `libft.h` (Header File)  
The heart of organization. This file includes your function prototypes and imports standard libraries all in one place, so you can simply `#include "libft.h"` in your `.c` files to access all your functions seamlessly. It keeps everything clean, organized, and modular.

### `Makefile`  
This file automates the compilation process. No more typing out long GCC commands; just type `make` to compile the library, `make clean` to remove object files, or `make fclean` to clean everything, including the compiled library. Simple, right?

## 📚 What's Inside? — The Functions

### Character Handling (from `<ctype.h>`)  
- **ft_isalpha** – Checks if a character is alphabetic.
- **ft_isdigit** – Checks if it's a digit (0-9).
- **ft_isalnum** – Checks if it’s alphanumeric.
- **ft_isascii** – Validates if the character is in the ASCII set.
- **ft_isprint** – Determines if it’s a printable character.
- **ft_toupper / ft_tolower** – Converts to uppercase/lowercase.

### String Manipulation (from `<string.h>`)  
- **ft_strlen** – Measures string length.
- **ft_memset** – Fills memory with a constant byte.
- **ft_bzero** – Zeros out memory.
- **ft_memcpy / ft_memmove** – Copies blocks of memory.
- **ft_strlcpy / ft_strlcat** – Copies/concatenates to a specific size.
- **ft_strchr / ft_strrchr** – Locates characters in strings.
- **ft_strncmp** – Compares strings up to a limit.
- **ft_memchr / ft_memcmp** – Scans and compares memory areas.
- **ft_strnstr** – Finds a substring.
- **ft_strdup** – Duplicates a string.

### Memory and Conversion (from `<stdlib.h>`)  
- **ft_atoi** – Converts a string to an integer.
- **ft_calloc** – Allocates and zeroes memory.

### Custom Utility Functions  
- **ft_substr** – Extracts a substring.
- **ft_strjoin** – Joins two strings.
- **ft_strtrim** – Trims specified characters from both ends.
- **ft_split** – Splits a string into an array by delimiter.
- **ft_itoa** – Converts an integer to a string.
- **ft_strmapi / ft_striteri** – Applies a function to each character in a string.
- **ft_putchar_fd / ft_putstr_fd / ft_putendl_fd / ft_putnbr_fd** – Outputs characters, strings, and numbers to file descriptors.

### Linked List Functions  
For data structures and list management:
- **ft_lstnew** – Creates a new linked list element.
- **ft_lstadd_front / ft_lstadd_back** – Adds elements to the beginning/end of a list.
- **ft_lstsize** – Counts the elements in a list.
- **ft_lstlast** – Finds the last element.
- **ft_lstdelone / ft_lstclear** – Deletes elements or clears the list.
- **ft_lstiter / ft_lstmap** – Applies functions across list elements.

## 📖 Resources

Want to dive deeper? Check out this helpful guide: [Libft Project Guide](https://www.asidesigned.com/project-libft.html).

---

Happy coding! Now, get in there, explore your functions, and build your C expertise—function by function, compile by compile.
