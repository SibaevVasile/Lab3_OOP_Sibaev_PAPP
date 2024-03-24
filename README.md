User manual for my Python code:

This program is designed to monitor changes within a specific folder on your computer and provide information about the files within it. It detects modifications such as creations, deletions, and updates, and provides detailed information about file types including images, text files, Python files, and Java files.

Setup:
Environment Setup:
Ensure you have Python installed on your system.
The code is compatible with any Python compiler, such as Microsoft Visual Studio Code or any other Python compiler.

Code Integration:
Open your preferred Python compiler.
Create a new Python file and paste the provided code into it.

Folder Configuration:
Locate line 197 in the code, where the folder path is specified.
Replace the existing folder path with the location of the folder you want to monitor.
Usage:
Run the Program:
Execute the Python script in your compiler.

Interacting with the Program:
The program will continuously monitor the specified folder for changes.

You will be prompted to enter commands in the terminal:
info <filename>: Provides detailed information about a specific file within the monitored folder.
status: Displays the current status of the monitored folder, including new files, deleted files, and changes.
exit: Terminates the program.

Command Usage:
Enter info <filename> to retrieve information about a specific file within the monitored folder.
Enter status to view the current status of the monitored folder, including any changes detected since the last snapshot.
Enter exit to terminate the program.

Additional Notes:
The program automatically updates itself every 5 seconds to ensure real-time monitoring of the folder.
New files, deleted files, and changes to existing files are detected and reported.
Detailed information is provided for different file types, including image size, text file statistics (line count, word count, character count), Python file statistics (line count, class count, method count), and Java file statistics (line count, class count, method count).

Troubleshooting:
Ensure the folder path specified in the code is correct.
Make sure Python is installed and properly configured on your system.
If encountering issues, verify that the code is correctly pasted into your Python file.
