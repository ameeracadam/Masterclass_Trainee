#   Task 1: Shell Commands
Write a short series of shell commands in a single line to list out the processes that belong to the "root"directory and print out the PID, owner, and name of process

##  Create a BASH script
-   `cd` to an appropriate folder and create a new `.sh` file.
-   For Mac/ Ubuntu VM: `touch [name_of_script].sh`
-   For Windows: `new-item [name_of_script].sh`

##  Insert your code
-   You will need to type in the she-bang to indicate that the script will be running in bash
    `#!/bin/bash/`
-   List out the processes by PID
    `ps acxo pid`
-   Pipe to search in the root directory
    `| grep root`
-   Save your code

##  Run the script
-   In a terminal, `cd` to the file location and type in `bash [name_of_script].sh`

****
##  Annex

## If BASH is not installed in your machine:
- For Windows: Download Git for Windows using this [link](https://gitforwindows.org/)
- For Mac: 
  - If you have [Homebrew](https://brew.sh/) installed, you can use the command `brew install git` in the Terminal
  - Install bash by using the command `brew install bash` in the Terminal <br>

### A list of Linux Shell Commands can be found through this [link](https://ss64.com/bash/)
