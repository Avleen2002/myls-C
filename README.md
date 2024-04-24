# myls Command Implementation

## Overview
The "myls" command is a custom implementation of the Unix/Linux "ls" command, developed specifically for the Linux environment. It provides functionality for listing files and directories with a limited set of options, adhering to strict specifications.

## Features
- Supports options such as "-i", "-l", and "-R" for customizing output format and behavior.
- Implements accurate sorting algorithms for lexicographical ordering of files and directories.
- Handles special paths, error conditions, and edge cases as specified in the requirements.

## Usage
To use "myls", clone the repository and compile the source code. Then, execute the compiled binary with the desired options and file list.

Example:
./myls -ilR /path/to/directory


## Testing
The project includes comprehensive test cases covering all permutations of options and various scenarios, ensuring robustness and reliability.

## Error Handling
"myls" provides meaningful error messages and gracefully handles unsupported options and nonexistent files/directories.

## Dependencies
No external dependencies are required. "myls" is self-contained and can be compiled and executed on any Linux system.

## Acknowledgements
Special thanks to the creators of the Unix/Linux "ls" command and to professor Hazra Imran, for inspiration and guidance.

