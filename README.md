# recursion-program-to-find-flies

This Java program is designed to search for all files and folders in a specified directory and its subdirectories. It does this by recursively traversing the file system and checking whether each item encountered is a file or directory.

The program takes a file path as input, and then prints the absolute paths of all the files and directories it finds within that path. It also keeps track of the number of directories and files found, which are displayed at the end of the program.

The program works by using a recursive function called find, which takes a File object as its argument. If the File object represents a file, the program prints its absolute path and increments the Files count. If the File object represents a directory, the program prints its absolute path, increments the Dirs count, and recursively calls the find function on each file or directory found within the directory.

# Usage
To use this program, simply run the main method and pass in the file path you want to search as an argument. For example, if you want to search for files and directories in the directory "S:\Machine learning and Data science", you can run the program with the following command:

# Copy code
java FindFilesRecursion S:\Machine learning and Data science
This will print out the absolute paths of all files and directories found within the specified directory and its subdirectories, as well as the total number of directories and files found.

# Limitations
This program is designed to search for files and directories in a single directory and its subdirectories. It does not search for files or directories on a network or remote file system, or on multiple directories at once. Additionally, it does not differentiate between different types of files, such as text files or image files.

# Conclusion
The FindFilesRecursion Java program provides a simple and efficient way to search for files and directories within a specified directory and its subdirectories. Its recursive approach allows it to efficiently search through large file systems, while its simple interface makes it easy to use for a wide range of users.
