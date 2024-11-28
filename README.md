# Recursively Listing The Content of a Directory
1. Ensure you have the dependency "dirent.h" installed with vcpkg 
2. Replace #include <C:\Users\Facey\vcpkg\packages\dirent_x64-windows\include\dirent.h> with where dirent.h is located on your pc
3. Open a new command prompt and go to the folder where listdir.cpp is located using cd <"path\to\dirent.h"> 
4. type listdir <"dir"> and replace "dir" with any directory on your pc and hit enter
5. The program will begin recursively listing the contents of the selected directory