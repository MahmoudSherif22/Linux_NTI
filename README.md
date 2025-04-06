# Linux_NTI
This Repository have the Labs solution on Linux part

2- What is the difference between cat and more command?
 - cat is used for concatinate files , view or create files
 - more is used for diplaying large files onescreen at a time 
3- What is the difference between rm and rmdir using man?
  - rm is used for removing complete directories with its subdirectories and files
  - rmdir is used for deleting empty directories and rmdir -p( --parents)delete the directory and the ancessortes
4-
 a - rm need to be accessed by root so i used sudo
 b - sudo rmdir -p dir12
 c -absolute :/home/mahmoud1/docs/mycv
    relative : cd docs/mycv
5- first go to home directory 
    sudo cp etc/passwd mypasswd
6-mv mypasswd oldpasswd 
7- 
  1- cd ../../home (relative path)
  2- cd /home (absolute path)
  3- cd ~ /.. 
  4- cd
8- ls w*
9- head -5 etc/passwd
10-tail -7 etc/passwd
11- 
12-man passwd
13-man -k "passwd" {apropose searches for instance with "keyword", keyword is regularexpression
14- 
