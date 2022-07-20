# Project Title
Module Catalogue Search

# Project Description
The application facilitates the users to search through a module catalogue which contains thousands of modules with their respective module codes. Hence it makes a difficult task to find the relevent one at once. As a solution, Module Catalogue Search program will allow users to search the required module by entering a possible keyword containing in the catalogue and the program will output the matching results and results count accordingly. 

# Requirements
    - (g++)GNU C++ Compiler installed
    - Text Editor/IDE (Only if need to modify the original code)

# How to Run

If the target PC have a Text Editor/IDE well setuped with a compiler, then open the `bmh.cpp` and simply build and run. However for anyone interested in typing the command mannually; 

1. For Windows & Linux
   > - Compile with `g++ bmh.cpp`
   > - Run program with `a.exe`(For Windows) or `a.out`(For Linux)

2. For Linux(Using the Makefile)
    > - In terminal type `make` and run
Makefile is located in the same directory. To clean the directory by removing previous build files use

> `make clean`

# Usage :information_source:
Extract zip file to get the **module_search** directory which contains the `bmh.cpp` and several required files including the `modules.txt`. Make sure the `modules.txt` resides within the same directory along with the `bmh.cpp`.(If somewhat need to move to move the modules.txt away, then the original source code need to modifed and the respective path should be given inside the following segment)

> `module_list.open("modules.txt",ios::in);`

After a successful compilation, terminal window will pop-up will be shown to type the search phrase. 

> Remember: Search will be case insensitive

and the program will print the matched module informations for you!


# References
-	 [Boyer-Moore Horspool Algorithm - Wiki](https://en.wikipedia.org/wiki/Boyer%E2%80%93Moore%E2%80%93Horspool_algorithm)
