0x11.C - printf group project- which is bformated output conversion funtio. #include "main.h" int_printf(const char format, ,,,);

The _printf() fnction produce output according to a format as described. it also write output to stdout, the _printf() finction write the format output under the format string that specifies how subsequent are converted for output.

Conversion is done in each data type, each conversion specification is introduced by the character % and ends with conversion specifier.
Conversion specifier is a character that specifies the type on conversion to be applied.The specifiers and their meaning are:
 d:for integer data type
 c:for character data type
 s:for string data type
 f:for float data type

 functions
int _write(char c): This functio gets a char parameter and the parameter to the standad output stream(stdoput)

int _print_a_string (va_list args): This functions gets a variadic arguments list, traverse the list, printseach string and returns the length of the string

int _print_a_char (va_list args): This functions gets a variadic arguments list, traverse the list, prints each char type and returns the length of the character

int_print_a_integer (va_list args): this function gets a variadic arguments list, traverse the list, prints each number of the int type and returns the lenghth of the integer.

int_print_format(const char *format, Va_list args): Thiiis function gets a format to be printed and a variadic arg7ument list, next to be checked if the format is valid or invalid and according with the verification of the resulting output is written to  the standard output stream and returns format lenght

int _print_spec(char format, va_list args): This functions gets a format valid to beprimnted and a variadic arguments list to find the format inthelist and selects appropriate function to execute  and  writes the format to stdout and  returns the lenght of the valid format

int _print_invalid_spec (char prev_format, char format,int count): This function gets previous format of the current format, the actual format and the current count of printed characters.The invalid format is written to the stdout and returns length of then invalid format

void _recursion_integer(int a): This functions gets an integer and prints  the last  digit of the number as recursion is applied.

int _validate_char(char _type): gets a type and checks if the passed parameter is present im a structure of valid conversation specifiers, then returns if the parameter is valid or invalid.

Return Value: Upon successful return, the _printf()  function return the number of chsracters printed, if an output error is encountered, a negative value is returned.

Author _printf() is written and maintained by Asbel Kipkosgei and Kiuvert Igbe.

