<div align="center">
  <img src="https://github.com/agengemb31/agengemb31/blob/main/Projects-Badges/get_next_linee.png" alt="get_next_line Badge" />
</div>

# get_next_line

The get_next_line function, implemented with a static list, allows reading a line from a file descriptor.  
Repeated calls to get_next_line() read the text file pointed to by the file descriptor, one line at a time.

[Subject](https://github.com/agengemb31/get_next_line/blob/master/en.subject.pdf)

## Usage

Create a main.c file that includes get_next_line.h so you can use the get_next_line function.
 
Prototype: `char *get_next_line(int fd);`  
- fd, the file descriptor to read from.
- Correct behavior, return read_line.
- If there is nothing else to read, or an error
occurred, return `NULL`.

Compilation: `gcc main.c get_next_line.c get_next_line_utils.c -D BUFFER_SIZE=42`
- BUFFER_SIZE can be set to any value you want.
