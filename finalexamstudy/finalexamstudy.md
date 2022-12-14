---
Name: Angel Larsen
Course: CIS 106
Semester: Fall 2022
---

** Question One

For every command in this list, include the following:
- Description
- Formula/syntax
- 3 Examples that you understand well

  ## Awk
  * Description: Awk is a scripting language used for processing and displaying text. Awk can work with a text file or fro standard output.
  * Usage: 
  * `awk + options + {awk command} + file + file to save` (optional)
  * Examples:
    * awk -F: `{print $1}` /etc/passwd
    * awk -F: `{print $NF}` /etc/passwd
    * awk -F: `{print $1,"=",$NF}` /etc/passwd

  ## Cat
  * Description: The cat command is used for displaying the contect of a file. Cat is short for concatenate which is its command intended use.
  * Usage:
  * `cat + option + file(s) to display`
  * Example:
  * `cat -n ~/Documents/todo.md`
  * `cat -b ~/Documents/todo.md`
  * `cat -s ~/Documents/todo.md`

## Cp
  * Description: Cp copies files/directories from a source to a destination
  * Usage: 
  * `cp + files to copy + destination`
  * `cp -r + directory to copy + destination`
  * Example:
  * `cp Downloads/wallpapers.zip Pictures/`
  * `cp -r ~/Downloads/wallpapers ~/Pictures/`
  * `cp Downloads/wallpapers/* ~/Pictures/`

  ## Cut
  * Description: The cut command is used to extract a specific section of each line of a file and display it to the screen.
  * Usage:
  * `cut + option + file(s)`
  * Example:
  * `cut -b 1-5 usernames.txt`
  * `cut -d ':' -f1,7 --output-delimiter=' => ' /etc/passwd`
  * `ls -1 | cut -d ' ' -- complement -s -f1`

  ## Grep
* Description: Grep is used to search text in given file. Grep works line by line basis (it matches the search criteria in a line by line basis)
* Usage:
* `grep + option + search criteria + file(s)`
* Example
* `grep -i 'dracula' ~/Documents/Books/dracula.txt`
* `grep -in 'dracula' ~Documents/Books/dracula.txt`
* `grep -o 'dracula' ~/Documents/Books/dracula.txt`

## Head
* Description: The head command displays the top N number of lines of a given file. It prints the first 10 lines. If more than one file name is provided then data from each file is preceded
* Usage: `head + option + file(s)`
* Example
* `head ~/Documents/Book/dracula.txt`
* `head -5 ~/Documents/Book/dracula.txt`
* `head -15 ~/Documents/Book/dracula.txt`

## Ls
* Description: Used for listing the content of a given directory or the file/directory itself
* Usage: `ls + option + directory to list`
* Example
* `ls cis106/`
* `ls -a ~/cis106/`
* `ls -1R ~/Pictures`

## Man
* Description: Man (manual) pages are documentation files that describe linux shell commands, executable programs, system calls, special files, etc
* Usage: man ls
* Example
* `man passwd`
* `man 5 passwd`
* `man -f passwd`

## mkdir
* Description: Used for creating a single directory or multiple directories
* Usage: `mkdir + the name of the directory`
* Example:
* `mkdir wallpapers`
* `mkdir wallpapers/sword`
* `mkdir ~/wallpapers/forest`

## mv
* Description: moves and rename directories
* Usage: `mv + source + destination`
* Example
* `mv Downloads/homework.pdf Documents/`
* `sudo mv ~/Downloads/theme /usr/share/themes`
* `mv games/ wallpapers/ rockmusic/ /media/student/flashdrive`

## tac
* Description: The tac command is used for displaying the content of a file in reverse order
* Usage:
* tac + option + file(s) to display
* Example
* `tac todo.md`
* `tac ~/Documents/todo.md`
* `tac -b`

## Tail
* Description: The tail command displays the last N number of lines of a given file.
* Usage:
* `tail + option + file`
* Example
* Displys the last 10 lines of a file:
  * `tail ~/Documents/Book/dracula.txt`
* Displays the last 5 lines of a file:
  * `tail -5 ~/Documents/Book/dracula`

## Touch
* Description: Touch is used for creating files
* Usage: `touch + fileName`
* Example
* `touch list`
* `touch list_of_cars.txt script.py names.csv`
* `touch ~/Downloads/games.txt`

## Tr
* Description: The tr command is used for translating or deleting characters from standard output
* Usage: `Standard output | tr + option + set + set`
* Example
* Translate one character to another
  * `cat file.txt | tr '.' ','`
* Translate white space into tabs
  * `cat program.py | tr "[space:]" '\t'`
* Translate tabs into space
  * `cat file.py |tr -s "[:space:]" ' '`

## Tree
* Description: Outputs the directory path and files in each sub-directory and a summary of a total number of sub-directories and files
* Usage:
* Example

## Vim
* Description: The Vi command-line text editor is included in all POSIX compliant operating system
* Usage: 
* Example


## Question 2

* How to work with multiple terminals open?
open one terminal the open another terminal and set them side by side. Or user tillix and split the terminal as needed.

* How to work with manual pages?
  
* How to parse (search) for specific words in the manual page
  
* How to redirect output (> and |)
  
* How to append the output of a command to a file
  
* How to use wildcards (For copying and moving multiple files at the same time)
  
* How to use brace expansion (For creating entire directory structures in a single command)