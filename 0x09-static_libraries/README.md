This is a readme file for the 0x09-static_libraries project in the alx-low_level_programming course.
1. Copy the .c files into the project directory.
2. using gcc "-Wall -pedantic -Werror -Wextra -std=gnu89 -c *.c" get the main.o file for the .c file.
3.using ar -rc <libname>.a *.o convert it to archive
4.use ar -t <libname>.a to list the .o files
5.use ranlib <libname>.a to index it.