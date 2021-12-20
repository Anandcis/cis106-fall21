In this lecture i learned cat, Tac, More, less, Head, Tail, Paste ,Sort wc, tr, Grep command

cat : this command use for displaying a content of a file ,  cat + file to display
                                                                                                   example, cat images

Display with line numers , use -n . cat -n /bin/bash

Tac : this command used for display the file in reverse order. 
More : This command used for displlaying the content of a file  1 page at time 
Less : this command used for content of  file 1 page at time.
Head : This command displays first number of a file. 
display first10 lines of a file :head  /etc/passwd

DIsplay first 5 lines of a file: head -5 /etc/passwd

Tail: This command use for last number of a file
display last 10 number of a file: tail /etc/pass 

Cut : this comand use for extract a specific section of each line of a  file
Display the first field of a each line  : cut -f1 llist1.txt

Paste: This command used for join files horizentally on columns. ,paste + option + files
Merge two files: paste list1.txt  list2.txt

Sort : This command used for sorting a files. you can sort a file by alphabetically, in reverse order , by number and by month. 
sort a file in reverse order : sort -r list1.txt

sort a file with numeric data : sort -n list1.txt

wc : This command is used for printing the number of lines , file and character. wc + option + file
Display the number of a file use option as "-l", display the number of character in a file use option as  "-m".

 Tr : This command used for translating charactrs from output. tr + output + set + set 
Translate one character to another : cat  list1.txt | tr  '.'  '.'  ',' list1.docx 

Diff : this command used for compare files, diff + option + file1 + file2 

Grep : This command used for match a stirng pattern form a file , grep + option + pattern to match + file

Rev : This command used for reversing the characters  position , rev + file 