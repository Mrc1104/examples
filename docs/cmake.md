Author: Ryan Conaway
Email: mc321015@ohio.edu
Date: 3/16/2021




1) What is CMake:


Cmake is a cross-platofrm tool that automates a build process for projects. CMake, in itself, is not a build system, but rather a build-system generator.
Cmake can be used to build makefiles, project files for IDEs, and various other build scripts 

2) What is the minimum possible setup to use cmake?


The most minimum cmake setup is compiling a lone executable. All you need is a CmakeLists.txt

CmakeLists.txt:

project( "project name" )

add_executable( "name" "sourcefile")

3) How to compile applications that use cmake?


i. Use the Cmake command pathed to the source dir: $cmake /path/to/source

ii. Then call the build files that were generated: $make 

iii. The cmake Program is now compiled 

