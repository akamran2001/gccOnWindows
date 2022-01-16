# gccOnWindows
A guide to using GCC and compiling C or C++ code on Windows (without Visual Studio)

- Install [Chocolatey](https://chocolatey.org/) - a package manager for Windows
- Install MINGW64 using chocolatey
  - Open powershell as admin and type ``` choco install mingw ```  
  - Your path will be autoatically set for g++ and gdb
- Create a file ending in .c or .cpp
- Compile the file using ```g++ <filename>.c``` or ```g++ <filename>.cpp``` replace ```<filename>``` with the actual filename
- Run the compiled exe file
