# C++ development

## gdb

Build with debug symbols!

Run gdb

    gdb [executable]

Run program

    r

Add breakpoint to file

    b source.cpp:[line]


## Cmake

### Linux

Build with debug symbols
    
    cmake -DCMAKE_BUILD_TYPE=DEBUG ..

### Windows

Configure for Windows 64 bit

    cmake -G "Visual Studio 15 2017 Win64" ..
