NAME:KAMALESHWARAN.R

COMPANY:CODETECH IT SOLUTION

INTERSHIP ID:CT04DH2315

DURATION:08 JULY TO 08 AUGEST

MENTOR:NEELA SANTOSH KUMAR

Description:
            
This Java program demonstrates basic file operations:
Writing content to a text file.
Reading content from a text file.
Modifying specific lines within the text file.
The program provides a simple console-based menu that lets users select an operation and interact with a file named example.txt. It uses standard Java I/O classes like BufferedReader, BufferedWriter, FileReader, and FileWriter to handle file input/output operat
The goal of this program is to help beginners understand how file manipulation works in Java. It showcases how to:
Accept user input.
Store and retrieve data from files.
Modify the content by line numbers.
Use try-with-resources for safe file handling.
🔧 Functionalities
Write to File
The user is prompted to input text line by ine
Input continues until the user types "exit".
The lines are written to a file named example.txt.
If the file already exists, its content is overwritten.
Reads and displays all lines from example.txt.
Uses BufferedReader for efficient line-by-line reading.
Modify File
Displays all lines in the file with line numbers.
Prompts the user to select a line number to modify.
Asks for new content to replace that line.
Rewrites the entire file with the updated content.
Exit
Safely ends the program.



SAMPLE OUTPUT:
==== File Operations Menu ====

1. Write to File
   
3. Read from File
   
5. Modify File
   
7. Exit
Choose an option: 1
Enter text to write (type 'exit' to finish):
Hello World
This is a test file.
exit
File written successfully.

==== File Operations Menu ====
Choose an option: 2

--- File Content ---

Hello World

This is a test file.
---------------------

==== File Operations Menu ====

Choose an option: 3

--- Current File Content ---

1: Hello World

2: This is a test file.

Enter line number to modify: 2

Enter new content: This is a modified line.

File modified successfully.

==== File Operations Menu ====

Choose an option: 2

--- File Content ---

Hello World

This is a modified line.
---------------------

