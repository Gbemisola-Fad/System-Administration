# System-Administration
 Introducing System Administration with Python

Using Linux to do many administrative tasks from the terminal, or the Bash command line. 
Python provides several modules that you can also use to run commands on the command line. 
In this lab, you will use os.system() and subprocess.run() to run Bash commands from Python.

In this lab, I will:

Use os.system() to run a Bash command
Use subprocess.run() to run Bash commands

This project demonstrates how to leverage Python for system administration tasks by executing Bash commands directly from Python scripts. 
It provides a practical introduction to using the os and subprocess modules for running shell commands, making it easier to automate and manage system operations.

Technologies Used

Python - The primary programming language used for scripting

Linux - The operating system environment where the Bash commands are executed

os module - A built-in Python module used to interact with the operating system, allowing for command execution

subprocess module - A more powerful module than os for spawning new processes, connecting to their input/output/error pipes, and obtaining their return codes

Implementation Details

os.system() - This function is used to run simple Bash commands. It executes the command in a subshell and returns the exit status of the command

subprocess.run() - This function provides more control over command execution, allowing for better error handling and output management

It can capture standard output and error, making it suitable for more complex command executions
