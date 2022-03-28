# VI

VI - pronounced vee-eye, is a text editor created in the 1970s, not unlike this author. It is extremely powerful and found almost everywhere there are files to be edited in linux/unix/posix systems.

## Command Mode vs. Insert Mode

Vi starts in command mode. The positioning commands
operate only while vi is in command mode. You switch vi to input mode by **typing i** or entering any one of several vi input commands. Once in input mode, any character you type is added to the file. 

**You cannot execute any commands until you exit input mode.**

**To exit input mode, press the escape (Esc) key.**

### Activities:
#### open a file:

`vi cars.md`

#### navigate your file:

`H` left one space
`J` down one line
`K` up on line
`L` right one space

#### change between command mode and insert mode

`i` insert mode 
`ESC` command mode

#### Exiting files:

Exit without saving:

`:q!`

Save and exit:

`:x` or `:wq`

#### Insert line above

`O`

#### insert line below

`O`

#### how to delete a single line 

`dd`

#### how to delete multiple lines 

To delete 5 lines:
`5dd`

#### how to undo changes

`u`

#### how to 'redo' changes

`ctrl-r`

#### Searching for text 

Try searching for Ferrari

`/Ferrari + ENTER`

You can use `n` to move to the next search result. 

#### Find and replace text in vi 

Try replacing "Ferarri" with "Magnum PI car"

`:g/Ferrari/s//Magnum PI car/g `

