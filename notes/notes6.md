# Notes 6: Handling Text Files

## AWk
A scripting language for processing and displaying text.
* EX: awk + '{print $1} ~/Documents/Csv/cars/csv - prints the first column of every line of cars.csv

## SED
A stream editor that can search, find and replace, insert, and delete
* EX: sed 's/pizza/rice/' shopping-list.lst - Replaces pizza for rice in shopping-list.lst

## Less
A paper program used for reading 1 page at a time
* EX: less ~/Documents.Books/dracula.txt

## Alias
A shorthand for a more complicated command
* EX: alias update="sudo apt update; sudo apt upgrade -y"

## >
ls -lA ~ > all-files-in-home.txt - saves the out put of the ls command to all-files-in-home.txt

## >>
ls -lA >> allmyfiles.lst - keeps all the old data

## |
man ls | grep "human-readable" - allows you ro redirt output of a command to the input of another