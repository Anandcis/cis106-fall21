* In this lecture i learned new text editor. its called VIM. 
start vim the text editor will start in normal mode. if you want to insert text press letter i.  now, you type whatever you need it. for normal mode press esc key.
* for save the text file you first go the normal mode then use the :w key . now,your file will be save.
*  if you want to save file and quit from vim press :wq key.     
Also, you can edit your file with vim by this command :e file name. 
* you navigating a file by this key : H=left ,j=down , K=up , L=right . if you want to move 15 character to the left press 15H. 

  ##### In this lecture i also learned Archiving utilities.
* Tar: creates archive for convert combining files to 
 * CPIO: using this command you creates archive , restores file from archive 
* Ar: this command use for creates,modifies and extracts from archive. 
Examples for tar command: 
* creates archive : tar -cf list1.tar file1 file2 file3
* extract archive : tar -xf list1.tar 
*  you can archive list of files by cpio.
ls | cpio -ov > list1.cpio
* you extract file by cpio using this command:
cpio -iv < list1.cpio

* ar program creates,modifies and extracts. 
  archive file with ar using this command:
  ar r test.a *.docx
  for delete a member from archive use "d" as option .
  * File compression gzip, bzip2 and xz used in this class:
  compress file by using this class: gzip animated.txt
  decompress file using this class:
  gzip -d animated.txt
  * 
* ls -l comaand shoes file owner and group owner . if we want to change a group owner name ,use the chown command.
* chown anand file.docx
