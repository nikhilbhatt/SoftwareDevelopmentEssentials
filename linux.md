# linux Basic Commands:-

1. Create a new file:-
		* touch filename
2. delete a word in text editor:
		* use command ctrl+backspace/window+backspace
3. Open a software in Linux:-
		* just write the name of application/software. for e.g. codeblocks
		* if you want that opened application should not be connected to termincal use $applicationName &disown. then use CTRL+C.
4. Copy a Folder in Linux:- 
		* cp sourcefolder destinationfolder
		* for example copy a file(hello.txt) present in Doucments to Desktop folder:- username@username:~$ cp Documents/hello.txt Desktop
5. Move a folder in Linux:-
		* mv source destination/
6. Autocomplete folder name or a command in linux terminal:-
		* write half command name like for sudo write su than press tab, your command will autocompleted in terminal.
7. if you want to add numbering while listing few things use nl:-
		* Write | nl after writing the command.
		* for example while using ls command:- $ ls | nl	


8. How to read/ write using nano editor:-
		* Why to use Nano Editor:- suppose a file having read only permission than you can write on that file using sudo nano command.
		* example:- $sudo nano filename or $nano filename. (if file have read write permission)
		* now you can edit the file just write whatever you want to write in it.
		* Save a file:- press ctrl+o than follow the instruction.
		* QUIT Nano editor:-  press ctrl+x.
		* CUT:- select the text using keyboard(shift+arrow buttons) than press ctrl+k.
		* PASTE:- press ctrl+U
		* You can find other commands in down to terminal. 

9. Pipe, filter and other useful commands in linux:-
		* https://www.guru99.com/linux-pipe-grep.html

10. File Permissions in linux:-
		* https://www.guru99.com/file-permissions.html	
