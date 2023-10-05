![Image](cd(no argument).png)

The working directory when the cd command was run was /home/lecture1\
This output was produced because given no argument cd returns the user back to the home directory.\
There were no errors

![Image](ls (no args).png)

The working directory when the ls command was run was /home\
This output was produced because given no argument ls returns the different files or other directories within the directory it currently is in\
There were no errors

![Image](cat (no args).png)

The working directory when the cat command was run was /home\
This output was produced once I had given the terminal an input and end of file signal via the ENTER button\
There were no errors

![Image](cd (with directory).png)

The working directory when "cd lecture1" command was run was /home\
This output is a changed current directory (that of lecture1). With an existing directory, cd will take the user to the desired directory\
The output is not an error; it was the expected result.

![Image](ls (with directory).png)

The working directory when "ls lecture1" command was run was /home\
This output is the contents in the directory of lecture1. The contents were README, Hello.java, Hello.class, and directory named messages.\
The output is not an error; it was the expected result.

![Image](cat (with directory).png)

The working directory when "cat lecture1" command is run was /home\
The output is a message stating that "lecture1 is a directory"\
The output was an error; cat was expecting a readable file

![Image](cd (with file).png)

The working directory is /home\
The output is a bash message stating that "lecture1/README is not a directory"\
The output was an error; cd was expecting a directory

![Image](ls (with file).png)

The working directory is /home\
The output of the command is "lecture/README". Which is returning the path of the file\
The output is not an error; ls listed what was in the directory, which was the current directory

![Image](cat (with file).png)

The working directory is /home
The output of the command is the contents of the README file
The output is correct; cat printed the contents of the file onto the terrminal
