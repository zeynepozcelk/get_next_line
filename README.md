The "get_next_line" project is a function that reads a file descriptor line by line. This function is designed to be able to read any file, regardless of its size, and return one line at a time.

## Features
The "get_next_line" function includes the following features:

- Ability to read any file, regardless of its size.
- Returns one line at a time, as specified by the caller.
- Handles multiple file descriptors at the same time.
- Handles edge cases such as empty files and files with no newline characters.
## Usage
To use the "get_next_line" function, you must first include the "get_next_line.h" header file in your C program. You can then call the function, passing in the file descriptor of the file you want to read and a pointer to a string to hold the next line of input.

The function will read the file descriptor one line at a time, storing the line in the string buffer passed in by the caller. The function returns 1 if a line has been read successfully, 0 if the end of the file has been reached, or -1 if an error has occurred.

## Conclusion
The "get_next_line" function provides a useful tool for reading files line by line in C programs. By including the "get_next_line.h" header file and calling the function with the appropriate arguments, you can read any file, regardless of its size, and process it one line at a time.
