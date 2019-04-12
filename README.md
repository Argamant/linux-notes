# Linux Notes
For the basic [or infuriating] linux details I constantly find myself needing.

## File System

### chmod
change file permissions 
the octal goes like this: [user][group][others]  the user is the owner of the file. Is there a way to have multiple owners and multiple groups?   
You are setting bits using hexadecimals for three octals. Each one works the same way.  Each bit of the octal represents a permission 
that you can have, like read, write or execute.  It's easier just to use the letter designations for these 
like I did in the example below.

use `ls -l [filename]` to see what permissions there are already.

`chmod u+rwx file.txt`

### find
search for files by file name.
example: `find ./ -name "fishguy*"`

### grep

## Makemkv
when copying fails, delete the files in the Downloads folder using find and then download the latest version following the instructions on this page: https://makemkv.com/forum/viewtopic.php?f=3&t=224

## Text Editors
### Nano
* Cut: 		`Ctrl + k`
* copy: 	`Alt + ^` i.e. `Alt + Shift + 6`
* paste 	`Ctrl + u`
* save: 	`Ctrl + o`
* select all: `Alt + a`

### Vim
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAGH! [loads a bullet, spins the chamber.]
