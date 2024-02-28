# Operating the Linux File System

## Mounting and Unmounting 

Mount - Device ko kissi specific directory k saath connect karna
Unmount - Device ko remove kar dena uss directory se 

Video explains quiet well

https://youtu.be/ssdFIWbVKZ4?si=L2M9xi7SrwiWtlxt


---

### lsof and fuser

lsof - list open files, has a broader scope providing information about a wide variety of open resources
fuser - Find User of a file or socket. Focuses on specific files, directories and sockets

---

### GREP

Global Regular Expression Print

Here's a real-world example of using grep to help you understand its functionality better:

Scenario: You're working on a personal project and need to find all occurrences of the word "bug" in your code files (located in the "my_project" directory) to identify potential issues.

grep "bug" *.py


    Explanation:
        grep: The command itself.
        "bug": The pattern you want to search for (quoted to avoid conflicts with special characters in filenames).
        *.py: This searches all files with the .py extension (wildcard character * matches any character sequence).

Output: The command will search all Python files in the directory and display any lines containing the word "bug." For example:

file1.py:15: This line has a potential bug.
file2.py:27: if statement might cause a bug.

---







