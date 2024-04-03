# Notes 4: Wildcards and Expansion

## There are 3 wild cards
* "*" is used when you do not know how man y characters there are. This matches anything and nothing- and matches any number of characters.
  * EX: "*.txt" will give you any file name with a txt extension
* "?" is used when you want to match one precise character. 
  * EX: "*.??" will give you a two character file extnesion
* "[]" is used when you want to match from a set.
  * EX: "[A-Z].*" will give you any file that has a captial letter

## Brace Expansion
Brace expansion is not a wildcard. It allows you to generate arbitrary strings to use with commands. This mean you can create multiple files or directories within them.
  * EX: touch music/{jazz,rock} will create two files in music called jazz and rock