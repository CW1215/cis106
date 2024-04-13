# Notes 4: Handling Text Files

## Cat
* The cat command is used for displaying the contents of a file. It is short for concatenate. There are many options for the cat command.
  * EX: "cat -n todo.md" displays the content of a file with line numbers
  * EX: "cat -b todo.md" excludes empty lines 

## Tac
* The tac command is used for displaying the content of a file in reverse order. It uses the same options as cat.

## Head
* The head command displays the top N number of lines of a given file. The default is the first 10 lines.
  * EX: "head n -5 todo.md" displays the first 5 lines
  * EX: "head -n 1 *.cvs" displays the first line of the files containing .cvs

## Tail
* The tail command displays the last N num,ber of lines of a given files. The default is the last 10 lines. It uses the same options as head.
  
## Cut
* The cut command is used to extract a specific section of each line of a file and display it to the screen.
  * EX: "cut -d":" -f1 /etc/passwd" will display a list of all the users in your system
  * EX: "cut -d":" -f1,7 /etc/passwd" will display a list of all the users in your system with their login shell

## Paste
* The paste command is used for joining files horizontally in columns
  * EX: "paste users.lst todo.md

## Sort
* The sort command is used for sorting files via alphabetically, reverse order, number, etc.
* EX: "sort -o users.txt" sorts file and saves the output as a new file
* EX: "sort -r users.txt" sort file in reverse order

## WC
* The wc command is used for printing the number of lines, characters, and bytes in a file
  * EX: "wc -m users.txt" displays the number of characters in a file
  * EX: "wc -l users.txt" displays the number of lines in a file
  * EX: "wc -w users.txt" displays the number of words in a file

## TR
* The tr command is used for translating or deleting characters from standard output
  * EX: "cat file.txt | tr '.'','" translates period ot comma
  * EX: "cat program.py | tr "[:space:]"'\t'" translates white space into tabs

## Diff
* The diff command compares files and displays differences between them
  * EX: "diff cars.csv carts-backup.csv" displays the difference between the two files

## Grep 
* Grep is used to search text in a given file
  * EX: "grep 'dracula' dracula.txt" search for the word dracula in dracula.txt
  There are many options, here are two:

  | Options | Explanation |
  |---------|-------------|
  | -i      | enables case insensitivity |
  | -n      | displays line number for every line matched |
