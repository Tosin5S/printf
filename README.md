## printf()
The printf project is a collaboration between Qudus Tosin Aileru and Oyindamola Olupitan, students of Software Engineering at Alx School.

## Prototype for _printf()

	int _printf(const char *format, ...)

------------

## Examples
**String**
* Input: ```_printf("%s\n", 'Hello World.');```
* Output: ```Hello World.```

**Character**
* Input: ```_printf("The first letter in the alphabet is %c\n", 'A');```
* Output: ```The first letter in the alphabet is A```

**Integer**
* Input: ```_printf("This is a integer: %i\n", 12);```
* Output: ```This is a integer: 12```

------------

## Mandatory Tasks
- [x] Write function that produces output with conversion specifiers ```c```, ```s```, and ```%```.
- [x] Handle conversion specifiers ```d```, ```i```.
- [x] Create a man page for your function.
## Advanced Tasks
- [x] Handle conversion specifier ```b```.
- [x] Handle conversion specifiers ```u```, ```o```, ```x```, ```X```.
- [x] Use a local buffer of 1024 chars in order to call write as little as possible.
- [x] Handle conversion specifier ```S```.
- [x] Handle conversion specifier ```p```.
- [ ] Handle flag characters ```+```, space, and ```#``` for non-custom conversion specifiers.
- [x] Handle length modifiers ```l``` and ```h``` for non-custom conversion specifiers.
- [ ] Handle the field width for non-custom conversion specifiers.
- [ ] Handle the precision for non-custom conversion specifiers.
- [ ] Handle the ```0``` flag character for non-custom conversion specifiers.
- [x] Handle the custom conversion specifier ```r``` that prints the reversed string.
- [x] Handle the custom conversion specifier ```R``` that prints the rot13'ed string.
- [ ] All above options should work well together.

------------

### Authors
[Qudus Tosin Aileru](https://github.com/Tosin5S) | [@Tosin5S](https://github.com/Tosin5S)

[Oyindamola Olupitan](https://github.com/Crystallie) | [@Crystallie](https://github.com/Crystallie)
