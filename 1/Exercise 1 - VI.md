#1 - VI

VI - pronounced vee-eye, is a text editor created in the 1970s, not unlike this author. It is extremely powerful and found almost everywhere there are files to be edited in linux/unix/posix systems.

##Command Mode vs. Insert Mode

Vi starts in command mode. The positioning commands
operate only while vi is in command mode. You switch vi to input mode by **typing i** or entering any one of several vi input commands. Once in input mode, any character you type is added to the file. 

**You cannot execute any commands until you exit input mode.**

**To exit input mode, press the escape (Esc) key.**


open a file in vim vi file.txt
navigation
h left 
j down one line
k up on line
i right one space
how to quit vi (:q)

saving files in vim, and other ways of exiting

Insert line above
insert line below

how to delete a single line with vim (dd)
how to delete multiple lines with vim (#dd, e.g. 5dd)

how to undo changes in vim (u)
how to 'redo' changes (ctrl-r)

searching text in vim ( /yourtext + ENTER)
how to find and replace text in vim ( :%s/yourtext/replacetext/g (+c))

