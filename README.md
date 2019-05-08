# get_next_line

int     get_next_line(const int file_descriptor, char **address_of_line);\n

Function that allows you to read a line ending with a newline character\n
from a file descriptor without knowing its size beforehand.\n

Return values :\n
.   0 End of file\n
.   1 A line has been read but the reading is not complete\n
.  -1 An error has happened\n

# Compiling library 
make\n

make clean\n
To remove objects and binary file (program):\n
make fclean\n
To re-compile:\n
make re\n
