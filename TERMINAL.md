[Home](README.md) 
1. Other Notes
	1. [Markdown](markdown.md)
	1. [Text Editor](TEXTEDITOR.md)
	1. [Terminal](TERMINAL.md)
	1. [Git Guide - (_made in VS Code_)](VScode.md)
	1. [HTML](HTML.md)
	1. [CSS](CDD.md)
	1. [Git Guide - (1st VS made notes)](GitGuide-VS.md)
	1. [How Computers Work](how_computers_work.md)
	1. [JaveScript Notes](JavaScript.md)
	1. [JavaScript Programming](JavaScript-Programming.md)
  
# Linux Cheat Sheet

## Command Line or Terminal
> A text based interface, vs GUI.

__Example__ 
```
user@bash: ls -l /home/ryan
total 3
drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin
drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
user@bash: 
```
* Line 1:
  * __Prompt__: user@bash
  * __Command__: ls (_first thing you type_)
  * __Arguments__: -l /home/ryan (_seperated by spaces_)
   * __option__ (_modify the behavior of a command, typically start with a dash_)
* Lines 2-5
  * __Output__
* Line 6
  * __Prompt__ (again)

#### Opening a Terminal
Mac | Linux | Windows
--- | ----- | -------
Application > Utilities > Terminal | Applications > System | need SSH client ([Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html))

#### Shell - bash (Bourne again shell)
__echo__ - display a system variable stating your current shell:
```
user@bash: echo $SHELL
/bin/bash
user@bash: 
```

_*hint: use arrows up/down to scroll recent commands*_

##### pwd - "Print Working Directory"
##### ls - "list"

```
> ls [options] [location]
> the square brackets "[ ]" mean optional part of a command
```

* __"ls"__: list content of current directory
* __"-l"__: _long_ listing
 * "-" normal file vs. "d" directory file
 * *next nine charachters are permissions for*
 * next field = owner
 * next field is group belonging to
 * then file size
 * next is file modification time
 * finally the name of file or directory
* "/etc" = not to list current directory, instead the directory's contents.

#### Paths - absolute vs relative
* Absolute
 * __root__ directory noted by singl slash "/" and then subdirectories, of sub, etc.
* Relative
 * do NOT begin with a slash "/"
 * specify location in relation to where they are in the system (ie. "file1.txt")
* Other
 * ~ (tilde)- shortcut for home directory. 
  * ie. if your home directory is /home/ryan 
  * then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
  * . (dot)- a reference to your current directory. 
   * ie. It could also be written as ./Documents.
  * .. (dotdot)- a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. 
   * ie. if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
   
#### cd - Change Directory
> running this command without any arguments takes back to home directory.

_*hint: use tab to use autocompletion, and hit again for more possibilities*_

#### Linux is an extensionless system
> Linux is case sensative
