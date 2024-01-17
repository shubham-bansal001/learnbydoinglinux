# Basic commands to navigate in linux terminal

Whenever you login to linux terminal you will first come in home directory of user through which you logged in, so the directory shall be "/home/user_name"

## Now to navigate among different directories the most BASIC commands used in linux are:
1) CD: which stands for change directory to whatever directory you give the path.
```console
shubham@LAPTOP-OR1O9MJ3:~$ pwd
/home/shubham
shubham@LAPTOP-OR1O9MJ3:~$ cd /home
shubham@LAPTOP-OR1O9MJ3:/home$ ls
```
2) pwd: stands for present working directory is used to know exact where you are at the moment
output:
```console
shubham@LAPTOP-OR1O9MJ3:~$ pwd
/home/shubham
```
3) ls: list system files in the current directory or custom directory you specify.
```console
shubham@LAPTOP-OR1O9MJ3:~$ ls
file.txt
```

## Properties of files and directories using ls command:
```console
shubham@LAPTOP-OR1O9MJ3:~$ pwd
/home/shubham
shubham@LAPTOP-OR1O9MJ3:~$ ls -l
total 20
drwxr-xr-x 2 shubham shubham 4096 Jan 17 14:17 directory1
drwxr-xr-x 2 shubham shubham 4096 Jan 17 14:17 directory2
-rw-r--r-- 1 root    shubham 4267 Mar 16  2023 file.txt
-rw-r--r-- 1 shubham shubham 2826 Jan 17 14:17 file2.txt
```

first column in type of file like d for directory and - for file
second is for number of hard links which are links to subdirectory plus link to parent directory and directory itself.
third is for username
fourth is for groupname
fifth is for filesize in bytes
sixth is for month name 
seventh is for date of month
eigth is for time of day or year
ninth is for file/directory name
