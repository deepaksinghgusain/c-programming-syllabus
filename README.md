### C Programming Syllabus

## History of c programming
# Language	    Year	    Developed By
# Algol	        1960	    International Group
# BCPL	        1967	    Martin Richard
# B	            1970	    Ken Thompson
# Traditional C	1972	    Dennis Ritchie
# K & R C	    1978	    Kernighan & Dennis Ritchie
# ANSI C	    1989	    ANSI Committee
# ANSI/ISO C	1990	    ISO Committee
# C99	        1999	    Standardization Committee
# C11           2011        standardizes the semantics of multi-threaded programs
# C18           2018        ISO/IEC 9899:2018

## Features of C Language
# Simple (C is a simple language in the sense that it provides a structured approach (to break the problem into parts), the rich set of library functions, data types, etc.)

# Machine Independent or Portable (Unlike assembly language, c programs can be executed on different machines with some machine specific changes. Therefore, C is a machine independent language.)

# Mid-level programming language (Although, C is intended to do low-level programming. It is used to develop system applications such as kernel, driver, etc. It also supports the features of a high-level language. That is why it is known as mid-level language.)

# structured programming language(C is a structured programming language in the sense that we can break the program into parts using functions. So, it is easy to understand and modify. Functions also provide code reusability.)

# Rich Library (C provides a lot of inbuilt functions that make the development fast.)

# Memory Management (It supports the feature of dynamic memory allocation. In C language, we can free the allocated memory at any time by calling the free() function.)

# Fast Speed(The compilation and execution time of C language is fast since there are lesser inbuilt functions and hence the lesser overhead.)

# Pointers (C provides the feature of pointers. We can directly interact with the memory by using the pointers. We can use pointers for memory, structures, functions, array, etc.)

# Recursion (In C, we can call the function within the function. It provides code reusability for every function. Recursion enables us to use the approach of backtracking.)

# Extensible (C language is extensible because it can easily adopt new features.)

## Creating first program

## Comments

## The preprocessor

## #include statement

## Display output

## Reading input from the terminal

## Variables
# A variable is a name of the memory location. It is used to store data. Its value can be changed, and it can be reused many times.
# It is a way to represent memory location through symbol so that it can be easily identified.

## Rules for defining variables
# A variable can have alphabets, digits, and underscore.
# A variable name can start with the alphabet, and underscore only. It can't start with a digit.
# No whitespace is allowed within the variable name.
# A variable name must not be any reserved word or keyword, e.g. int, float, etc.

## Types of Variables in C
# local variable
- A variable that is declared inside the function or block is called a local variable.

# global variable
- A variable that is declared outside the function or block is called a global variable. Any function can change the value of the global variable. It is available to all the functions.

# static variable
- A variable that is declared with the static keyword is called static variable.
- It retains its value between multiple function calls.

# automatic variable
- All variables in C that are declared inside the block, are automatic variables by default. We can explicitly declare an automatic variable using auto keyword.

# external variable
- We can share a variable in multiple C source files by using an external variable. To declare an external variable, you need to use extern keyword.

## Data Types in C
# A data type specifies the type of data that a variable can store such as integer, floating, character, etc.

## Basic Data Type
- int, char, float, double

## Derived Data Type
- array, pointer, structure, union

## Enumeration Data Type
- enum

## Void Data Type
- void

## DATA TYPES           Memory Size     Range
#  char	                1 byte	        −128 to 127
#  signed char	        1 byte	        −128 to 127
#  unsigned char	    1 byte	        0 to 255
#  short	            2 byte	        −32,768 to 32,767
#  signed short	        2 byte	        −32,768 to 32,767
#  unsigned short	    2 byte	        0 to 65,535
#  int	                2 byte	        −32,768 to 32,767
#  signed int	        2 byte	        −32,768 to 32,767
#  unsigned int  	    2 byte	        0 to 65,535
#  short int	        2 byte	        −32,768 to 32,767
#  signed short int	    2 byte	        −32,768 to 32,767
#  unsigned short int	2 byte	        0 to 65,535
#  long int	            4 byte	        -2,147,483,648 to 2,147,483,647
#  signed long int	    4 byte	        -2,147,483,648 to 2,147,483,647
#  unsigned long int	4 byte	        0 to 4,294,967,295
#  float	            4 byte	
#  double	            8 byte	
#  long double	        10 byte

## limits.h
# CHAR_BIT	       8	                Defines the number of bits in a byte.

# SCHAR_MIN	       -128	                Defines the minimum value for a signed char.

# SCHAR_MAX	       +127	                Defines the maximum value for a signed char.

# UCHAR_MAX	       255	                Defines the maximum value for an unsigned char.

# CHAR_MIN	       -128	                Defines the minimum value for type char and its value will be equal to SCHAR_MIN if char represents negative values, otherwise zero.

# CHAR_MAX	       +127	                Defines the value for type char and its value will be equal to SCHAR_MAX if char represents negative values, otherwise UCHAR_MAX.

# MB_LEN_MAX	   16	                Defines the maximum number of bytes in a multi-byte character.

# SHRT_MIN	      -32768	            Defines the minimum value for a short int.

# SHRT_MAX	      +32767	            Defines the maximum value for a short int.

# USHRT_MAX	      65535	                Defines the maximum value for an unsigned short int.

# INT_MIN	     -2147483648	        Defines the minimum value for an int.

# INT_MAX	     +2147483647	        Defines the maximum value for an int.

# UINT_MAX	     4294967295	            Defines the maximum value for an unsigned int.

# LONG_MIN	     -9223372036854775808	Defines the minimum value for a long int.

# LONG_MAX	     +9223372036854775807	Defines the maximum value for a long int.

# ULONG_MAX	     18446744073709551615	Defines the maximum value for an unsigned long int.

