# get_next_line

int     get_next_line(const int file_descriptor, char **address_of_line);<br/>

Function that allows you to read a line ending with a newline character (\n)<br/>
from a file descriptor without knowing its size beforehand.<br/>

Return values :<br/>
- 0  : end of file<br/>
- 1  : line has been read but the reading is not complete<br/>
- -1 : error has happened<br/>

# Compiling library (my own library)
To compile: make<br/>
To remove objects: make clean<br/>
To remove objects and binary file (program): make fclean<br/>
To re-compile: make re<br/>

Compile with libft.a  main.c and get_next_line.c
