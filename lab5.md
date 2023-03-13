# Exploring the ```less``` command
- The ```less``` command reduces the loading times of large text files by loading the content one screen at a time. However, it could be used in different ways on the linux command, here are some examples.


## 1: Using ```less -F```
- If you do not know wether the file is going to be too big, using the modifier ```-F``` allows the command to exit if the file's content can be displayed on the first screen.


## 2: Using ```less -N``` 
- If you want to know the line numbers of the test displayed on the screen, you could use ```less -N``` to display the line numbers of the content printed.

## 3: Using ```less -X```
- If you do not want the screen to exit after ```less``` exits as a way to display the content on the screen after, using ```-X``` keeps the content in the terminal.

## 4: Opening Multiple Files
- You could list multiple files by passing more files into ```less``` in the terminal

## 5: Eliminating blank lines with ```less -s```
- You could eliminate multiple bland lines using ```-s``` modifier that turns large blank plages into a single one



