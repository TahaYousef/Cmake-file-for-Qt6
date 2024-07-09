This for MinGw 64bit
if you use code runer extension for cpp you add the folloing command 
"cpp": "mkdir build-mingw && cd build-mingw && cmake -G \"MinGW Makefiles\" -DCMAKE_C_COMPILER=gcc -DCMAKE_CXX_COMPILER=g++ .. && mingw32-make && start Cmake-file-for-Qt6.exe",
in fila named package.json, location is 

C:\Users\Taha\.vscode\extensions\formulahendry.code-runner-0.12.2

amend your path according to user



If you use MSVC++ compiler the above command not working , search for specification for cmake
