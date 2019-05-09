# get_next_line

int     get_next_line(const int file_descriptor, char **address_of_line);<br/>

Function that allows you to read a line ending with a newline character<br/>
from a file descriptor without knowing its size beforehand.<br/>

Return values :<br/>
0 : end of file<br/>
1 : line has been read but the reading is not complete<br/>
-1 : error has happened<br/>

# Compiling library 
To compile:<br/>
make<br/>
To remove objects:<br/>
make clean<br/>
To remove objects and binary file (program):<br/>
make fclean<br/>
To re-compile:<br/>
make re<br/>

Compile with libft.a main.c and get_next_line.c
