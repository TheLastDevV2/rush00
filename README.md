# Rush00 – `rush01`

Small C exercise that draws a “rectangle” of characters on standard output, using only the
`write(2)` system call wrapped in `ft_putchar`. The implementation is split into a few
source files.

## Repository structure
```
This is the code block that represents the suggested code change:
````markdown
> **Note:** `header.h` may contain, for example, the prototypes of the functions
> (`void	ft_putchar(char c);` and `void rush(int x, int y);`), although it is not
> required for the current build.

## File descriptions

* **`ft_putchar.c`** – implements `ft_putchar`, which sends a character to `stdout` via
  `write(1, &c, 1)`.

```c
#include <unistd.h>

void	ft_putchar(char c)
{
    write(1, &c, 1);
}
```
`````
This is the code block that represents the suggested code change:
```markdown
void	rush(int x, y);

int	main(void)
{
    rush(5, 3);
    return (0);
}
```

to compile:
gcc -Wall -Wextra -Werror [ft_putchar.c](http://_vscodecontentref_/3) [rush01.c](http://_vscodecontentref_/4) [main.c](http://_vscodecontentref_/5) -o rush01

./rush01


/***\
*   *
\***/
