# FileManager

An amazingly useless tool!

All operations can be foundin FileOperator.java--

list - 
The list command will show you a list of the files in a directory. When you call the command list, you will have to 
enter the directory path as a string parameter.
usage will look like this: list
"~/user/projects"


info -
The info command will print the information of a file. When you call the info command, you will have to enter the path 
to the file as a string parameter. It will print the Name, Absolute path, Relative path, file size, creation date, and 
the last time it was modified.
usage will look like this: 
info
"~/user/projects/casino.java"



mkdir - 
The createDir command will create a directory at the path which must be entered as a string parameter. There are 
limitations to which characters can be used in the directory name: \\ / : ? * \ < > |
usage will look like this: 
mkdir
"~/user/projects/casino"


rename -
The rename command will rename an existing file. A file cannot be renamed to a name that is already being used in that
directory. You have to enter the OLD name of the file, and then the NEW name of the file as string parameters.
Usage will look like this: 
rename
"oldfile", "newfile"


copy / move - 
Either command will have the same functions, this will either copy a file to a different directory, or move it without
copying.
Usage will look like this:
copy (or) move
"~/user/projects/casino.java"
"~/user/projects/newCasino/"


delete files
The delete command will delete a file or directory
Usage will look like this:
delete
"~/user/projects/casino.java" (OR) "~/user/projects/newCasino/"



quit -
Quits the program.
Usage will look like this: quit();