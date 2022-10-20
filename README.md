Team project, _printf
This project seeks to implement a customized printf, _printf. This project involve the use of C programming knowledge learned by the cohort 9 in 2022 at Holberton School.

Prototype: int _printf(const char *, ...);

File Descriptions

	_printf.c

		it contains the _printf function with protype int _printf(const char *, ...);. The format parameter is an array of elemenst for formating the strings that will be written to the stdout by _printf function.
	
	main.h
		it contains the prototypes of the all the functions that were used in the project. The functions are found in different files.
	functions.c functions1.c functions2.c
		they contain all the function of each specifier used for _printf and have descriptions of the functions in them.

	_putchar.c
		contains the function _putchar, which writes a character to stdout.
	handle_print.c
		contains arguments types used for _printf.
	get_flags.c
		contains all function for each flag use for _printf.
	utils.c
		contains some necessary functionalities for _printf.
	get_width.c
		contains functions to get width for spcifics spcifiers.
	write_handlers.c
		contains write functions.
	get_size.c
		contains function for computing the size to cast argument.
	get_precision
		contains functin to ensure precise printing of strings.

Authors
	Gideon Okyere | Prince Otuya
