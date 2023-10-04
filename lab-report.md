# Lab Report 1

Krishna Rastogi
***
## cd Command With No Arguments
> ![Image](abspath1.png)

The working directory when the code was run was /home.

When there are no arguments given to the command cd it just means that there is no path given to change directory to so we stay in the same directory. This is not an error because leaving the argument blank is the same as the argument "./" being inputted which is just the relative path to the current directory.

## cd Command With Path to a Directory
> ![Image](abspath2.png)

The working directory when the code was run was /home.

The argument given is a relative path from home into the lecture1 directory and then into the messages directory. The lecture1 directory is in the home directory and the messages directory is in the lecture1 directory so the path given was valid and therefore no errors occurred.

## cd Command With Path to a File
> ![Image](abspath3.png)

The working directory when the code was run was /home/lecture1/messages.

The argument given is a relative path from messages to the text file inside it named en-us.txt. However, since cd stands for change _directory_ and we used a files location as the argument, an error occurred stating that the path specified was not a directory.



