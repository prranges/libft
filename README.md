# libft

## Challenge

Create your own personal library. 

## Part 1 
#### (Mandatory Functions)

- ft_memset
- ft_bzero
- ft_memcpy
- ft_memccpy
- ft_memmove
- ft_memchr
- ft_memcmp
- ft_strlen
- ft_strdup
- ft_strcpy
- ft_strncpy
- ft_strcat
- ft_strncat
- ft_strlcat
- ft_strchr
- ft_strrchr
- ft_strstrs
- ft_strnstr
- ft_strcmp
- ft_strncmp
- ft_atoi
- ft_isalpha
- ft_isdigit
- ft_isalnum
- ft_isascii
- ft_isprint
- ft_toupper
- ft_tolower

## Part 2 
#### (Mandatory Functions)

**ft_memalloc** <br />
>Allocates with ```malloc``` and returns a “fresh” memory area. The memory allocated is initialized to 0. If the allocation fails, the function returns NULL.

**ft_memdel** <br />
>Takes as a parameter the address of a memory area that needs to be freed with ```free```, then puts the pointer to NULL

**ft_strnew** <br />
>Allocates with ```malloc``` and returns a “fresh” string ending with ’\0’. Each character of the string is initialized at ’\0’. If the allocation fails the function returns NULL.

**ft_strdel** <br />
>Takes as a parameter the address of a string that need to be freed with ```free```, then sets its pointer to NULL.

**ft_strclr** <br />
>Sets every character of the string to the value ’\0’.

**ft_striter** <br />
>Applies the function **f** to each character of the string passed as argument. Each character is passed by address to **f** to be modified if necessary

**ft_striteri** <br />
>Applies the function **f** to each character of the string passed as argument, and passing its index as first argument. Each character is passed by address to **f** to be modified if necessary.

**ft_strmap** <br />
>Applies the function **f** to each character of the string given as argument to create a “fresh” new string (with ```malloc```) resulting from the successive applications of **f**.

**ft_strmapi** <br />
>Applies the function **f** to each character of the string passed as argument by giving its index as first argument to create a “fresh” new string (with ```malloc```) resulting from the successive applications of **f**.

**ft_strequ** <br />
>Lexicographical comparison between s1 and s2. If the 2 strings are identical the function returns 1, or 0 otherwise.

**ft_strnequ** <br />
>Lexicographical comparison between s1 and s2 up to n characters or until a ’\0’ is reached. If the 2 strings are identical, the function returns 1, or 0 otherwise.

**ft_strsub** <br /> 
>Allocates (with ```malloc```) and returns a “fresh” substring
from the string given as argument. The substring begins at
indexstart and is of size len. If start and len aren’t refering
to a valid substring, the behavior is undefined. If the
allocation fails, the function returns NULL.

**ft_strjoin** <br />
>Allocates (with ```malloc```) and returns a “fresh” string ending
with ’\0’, result of the concatenation of s1 and s2. If
the allocation fails the function returns NULL.

**ft_strtrim** <br />
>Allocates (with ```malloc```) and returns a copy of the string
given as argument without whitespaces at the beginning or at
the end of the string. Will be considered as whitespaces the
following characters ’ ’, ’\n’ and ’\t’. If s has no whitespaces
at the beginning or at the end, the function returns a
copy of s. If the allocation fails the function returns NULL.

**ft_strsplit** <br />
>Allocates (with ```malloc```) and returns an array of “fresh”
strings (all ending with ’\0’, including the array itself) obtained
by spliting s using the character c as a delimiter.
If the allocation fails the function returns NULL. Example
: ft_strsplit("*hello*fellow***students*", ’*’) returns
the array ["hello", "fellow", "students"].

**ft_itoa** <br />
>Allocate (with ```malloc```) and returns a “fresh” string ending
with ’\0’ representing the integer n given as argument.
Negative numbers must be supported. If the allocation fails,
the function returns NULL.

**ft_putchar** <br />
>Outputs the character c to the standard output.
 
**ft_putstr** <br />
>Outputs the string s to the standard output.

**ft_putendl** <br /> 
>Outputs the string s to the standard output followed by a
’\n’.

**ft_putnbr** <br />
>Outputs the integer n to the standard output.

**ft_putchar_fd** <br />
>Outputs the char c to the file descriptor fd.

**ft_putstr_fd** <br />
>Outputs the string s to the file descriptor fd.

**ft_putendl_fd** <br />
>Outputs the string s to the file descriptor fd followed by a
’\n’.

**ft_putnbr_fd** <br />
>Outputs the integer n to the file descriptor fd.
