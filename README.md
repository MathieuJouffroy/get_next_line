# get_next_line

int     get_next_line(const int file_descriptor, char **address_of_line);

Function that allows you to read a line ending with a newline character
from a file descriptor without knowing its size beforehand.

Return values :
.   0 End of file
.   1 A line has been read but the reading is not complete
.  -1 An error has happened

# Compiling library 
To compile
make
To remove objects:
make clean
To remove objects and binary file (program):
make fclean
To re-compile:
make re
