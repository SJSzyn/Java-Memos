- [https://gist.github.com/riipandi/3097780](https://gist.github.com/riipandi/3097780)
- [https://github.com/RehanSaeed/Bash-Cheat-Sheet](https://github.com/RehanSaeed/Bash-Cheat-Sheet)
- [https://raw.githubusercontent.com/bobbyiliev/introduction-to-bash-scripting/main/ebook/en/export/introduction-to-bash-scripting-dark.pdf](https://raw.githubusercontent.com/bobbyiliev/introduction-to-bash-scripting/main/ebook/en/export/introduction-to-bash-scripting-dark.pdf)

## Fun stuff

- `tab` After a command we can check the files within
- `clear` Clear terminal text
- `history` Show the history of input commands

## File Commands

- `ls` List directory
    - `ls -a` List all files in directory (show hidden)
    - `ls -l` List logs the rights of the files in folder
    - `ls -F` Lists files and directories with special symbols

- `cd` Change directory
    - `cd ../../` To take steps back
    - `cd /soso/soso` To dive into multiple folders

- `pwd` Print working directory will show path

- `mkdir <folder>` Makes a new directory

- `rm <file>` Deletes the file

- `cp <file1> <file2>` Copy file1 to file 2
    - `cp -r dir1 dir2` Copies directory 1 to directory2; will create folder if none

- `scp [OPTION] [user@]SRC_HOST:]file1 [user@]DEST_HOST:]file2` SCP is a secure file transfer protocol that uses SSH for data transfer and provides the same authentication and security as SSH.

- `mv` Moves or renames a file
    - `mv <file1> <file2>` Will rename the file
    - `mv <file1> <stuff/stuff>` Will move the file to the destination folder

- `touch <file.txt>` Creates a file

- `cat <file>` Concatenates selected files, gives us a view of what's inside

- `head <file>` Output the first 10 lines

- `tail <file>` Output the last 10 lines.
    - `tail -2` We can precise the number of lines

- `ln` - Create links between files, symlink (symbolic). Links can be hard (two names for the same file) or soft (a shortcut of the first file).

## SSH

- `ssh user@host` Connect to host as user

## Searching

- `grep` Search for a specific value in files

## Sorting

- `sort` Rearranges in alphabetical order
    - `sort -n` Rearranges in numeric order

## System Info

- `whoami` Who you are logged in as

## Editing Files

- `nano` To edit a file
    - `ctrl + O` To save modifictions
    - `ctrl + X` To exit nano

## Transforming

- `alias` Create an alias, a shortcut that references a command
    - `alias ls='ls -F'` Create an alias, a shortcut that references a command
    - `alias ls='ls -F --color=auto'` To change color

## Script

- `./`  To execute a script

## Variables

- `export` Used to set an environment/global variable
    - `I=amulet` VARIABLE_NAME=VALUE

- `let` - Used to perform integer arithmetic on shell variables
## information/help

- `man <command>` - shows all the options
- `<command> --help` shows info