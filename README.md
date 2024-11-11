# My Library (CPP)

A C++ library for utility functions including I/O, math, string manipulation, and file handling.

## Features

- **Input/Output Functions**: Simplified methods for handling standard input and output.
- **Mathematical Functions**: A collection of utilities for various mathematical calculations.
- **String Manipulation**: Functions for efficient string processing.
- **File Handling**: Easy methods for reading from and writing to files.

## Directory Structure
```
my_library_cpp/
│
├── include/          # Header files
│   ├── io.h
│   ├── math.h
│   ├── string.h
│   └── file.h
│
├── src/             # Implementation files
│   ├── io.cpp
│   ├── math.cpp
│   ├── string.cpp
│   └── file.cpp
│
└── README.md        # Project documentation
```

## Installation
Clone the repository:
```
git clone https://github.com/naifalhumaidi/my_library_cpp.git
```
## Usage
Include the necessary header files in your C++ project. Adjust the include paths based on your project structure. For example, if the library is in a subdirectory called my_library_cpp, you would include the headers like this:
```
#include "my_library_cpp/include/io.h"      // Adjust path as needed
#include "my_library_cpp/include/math.h"    // Adjust path as needed
#include "my_library_cpp/include/string.h"   // Adjust path as needed
#include "my_library_cpp/include/file.h"     // Adjust path as needed
```
Make sure to compile the .cpp files in your project:
```
g++ -o my_program my_library_cpp/src/io.cpp my_library_cpp/src/math.cpp my_library_cpp/src/string.cpp my_library_cpp/src/file.cpp main.cpp
```
## License
This library is licensed under the MIT License. You are free to use, modify, and distribute it for any purpose.
