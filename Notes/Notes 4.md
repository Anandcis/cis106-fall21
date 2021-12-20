
mkdir command:- mkdir making single directory or multiple directories.

 create directory by this type: mkdir + the name of directory

create directory with present directory: mkdir images

create directory with relative path: mkdir images/christmas

create directory with absolute path: mkdir ~/images/christmas

create directory with parent directory: mkdir -p images/thanksgiving 

if you want creating a files , use "touch" command

create a file list: touch list

create several files: touch list1 list2 list.pdf

if you want to Delete a files and directrories use the rm command

remove a file: rm list1

remove file and promopt confirmation: rm -i list1

remove non empty directory: rm -r Downloads/games

if you want to moving a files and directories ,use mv cmmand

mv + source + destination ,

using mv command you also change the renaming the files and directories

rename  a file using this command: mv  list1.pdf    list5.pdf

if you want to copying a files and directories

copy a fille : cp Downloads/list1.pdf     Notebook/

how to get a inode number of a file

ls -i list1 or  exa -i list1

### Wildcards


* = mathches zero or more chraracters for filename  example, file. txt = ls *.txt

? = matches any one character example, 

[acf] = matches multiple characters , ls i[acf]*

To match vowel and  that donot have a letter, ls  f[!aeiou]  and ls   f[!acf]*

to match number , ls *[0-9]*

Using Brace  Expansion

create a directory structure, mkdir -p images/{adventure,action}/{2010,2015,2020}

remove a multiple files in a directory : rm -r  images/{adventure,action}/{2010,2015,2020}






