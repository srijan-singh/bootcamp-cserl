# Getting Familiar With Linux

## Exercises

### 1) Find the variant of the ls command (i.e. argument(s) to be used) to list contents of a folder including its hidden files, the variant of cp to copy folder and the command to rename a file.

1) To list contents of a folder including its hidden files
    
- $ ls -a : To show all the hidden files in the directory, use ‘-a option’. Hidden files in Unix starts with ‘.’ in its file name.It will show all the files including the ‘.’ (current directory) and ‘..’ (parent directory).

2) The variant of cp to copy folder and the command to rename a file.

- cp -i <source<so>><destination<ds>>: It will prompt a message if the file destination file already exists.

### 2) In this question, we will understand the hardware configuration of your working machine using the /proc filesystem.

- Processor is an electronic circuit inside that carries out instruction to perform arithmetic, logical, control and input/output operations while the core is an execution unit inside the CPU that receives and executes instructions.

- Info
    - Sockets : 2
    - Cores : 2
    - Processors : 4

- Frequency: 2592.007 MHz

- RAM : 3800 MB

    - Free : 177 MB 

    Free and Available RAM is the amount of memory that is not being used and can be use for execution of other file without altering other process.

- User Level Process
    - 45 pts/0 00:00:00
    - 94 pts/0 00:00:00

- Forks : 403

- Context Switches : 10

### 3) In this question, we will understand how to monitor the status of a running process using the top command. Compile the program cpu.c given to you and execute it in the bash or any other shell of your choice as follows.

- PID : 122
- CPU : 99.7
- State : Running
