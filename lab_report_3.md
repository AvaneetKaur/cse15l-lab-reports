# Researching `less` Command

The `less` command is used to display contents of a file one screen at a time. The general syntax of this command is `less [options] file_path`. 

Some of the few options for using this command are:-
* `-W` highlights first new line after any forward movement. 
* `-N` displays line numbers at the beginning of each line.
* `-F` exit `less` if the entire file can be displayed on the first screen.
* `-p [pattern]` instruct `less` to start at the first occurrence of the specified pattern in the input file.

This information is sourced from [phoenixnap](https://phoenixnap.com/kb/less-command-in-linux).

## Examples
## `less -W`

Example 1
![Image](-W11.png)
Opens the file
![Image](-W12.png)

After pressing space to move forward it highlights the first line after the last of the previous window
![Image](-W13.png)

Example 2
![Image](-W21.png)
Opens the file
![Image](-W22.png)

After pressing space to move forward it highlights the first line after the last of the previous window
![Image](-W23.png)


## `less -N`

Example 1
![Image](-N11.png)

Opens the file with line numbers added to the begining of each line
![Image](-N12.pdf.png)

Example 2
![Image](-N21.png)

Opens the file with line numbers added to the begining of each line
![Image](-N22.png)


## `less -F`

Example 1
![Image](-F11.png)

Does not open the file instead prints the contents of the file in the terminal
![Image](-F12.png)

Example 2
![Image](-F21.png)

Does not open the file instead prints the contents of the file in the terminal
![Image](-F22.png)


## `less -p`

Example 1
![Image](-p11.png)

Highlites the string entered with command
![Image](-p12.png)

Example 2
![Image](-p21.png)

Highlites the string entered with command 
![Image](-p22.png)

