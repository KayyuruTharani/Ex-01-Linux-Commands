# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls




 <img width="528" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/d730c031-3eb3-47d1-bbd2-4b8846d2e898">





### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="529" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/3cbf0886-ee44-4565-b5aa-f086a8d45fe1">







 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>




<img width="662" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/b828ef63-8042-4d02-bba7-f70c75eeb11f">






### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>



<img width="458" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/4a6c21b3-c2a2-4e42-a309-ada22b2ac23c">




### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


<img width="477" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/0e8536d3-2330-463a-a82b-d90943f5ff2f">






### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="467" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/c4416e18-74b1-49d7-a307-6826af24facb">



 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>



<img width="467" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/67298c27-4f56-4dda-801a-e8823a3cf6c8">





### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name



<img width="469" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/a603b5af-3be8-4da9-80a2-039ab7c5adf4">





### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


<img width="462" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/01032b57-2907-4e08-87db-deffc84c890e">






### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


<img width="478" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/e38d57d7-c88b-4fdd-8ac1-def135ede86e">




 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files





<img width="452" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/333cafdb-8307-4e98-be1a-37adcc028f97">





### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>



<img width="465" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/a592f819-4d25-4819-9c0b-55980c0d134c">




### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>



<img width="419" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/9f9bc915-b1c6-43bd-b392-c9957fbc9e84">



 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id



<img width="458" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/c6b478f8-c693-4462-a0c2-fdcb1dc0032d">




### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


<img width="471" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/acdfa684-cd2e-4807-a4ec-71e364ef5d41">



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>



<img width="459" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/574b62a2-44c9-4a43-bda5-36c8c7dc3219">



### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name




<img width="444" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/a9a00d62-ed08-474a-a08c-9a4b74b4fc7f">




### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….




<img width="465" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/983fa3c0-7883-4251-89e5-52f7a23e9cdd">



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="460" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/146955ca-bd91-4b89-904a-0caaf6023108">



### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="268" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/a6e3ca84-94b6-45b3-b552-bab16d791cd9">



 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>



<img width="464" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/2032bd43-4f79-4c94-8c35-8bdc230e5c9a">




### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..



<img width="458" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/052b92d0-4d89-4d5e-a38b-045fde4059c8">



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>



<img width="473" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/111990ab-ea10-4931-9165-d9eba07d87df">


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="464" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/f289ef38-ae80-4f6e-9684-3fe9bd685df3">




### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear




<img width="463" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/d7cee187-1b62-4782-96a0-3c70c24843f4">



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


<img width="481" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/e71d6080-239f-4cb6-aa75-8413854e6e28">


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df





<img width="460" alt="image" src="https://github.com/KayyuruTharani/Ex-01-Linux-Commands/assets/142209319/d2d25573-41bd-4b1a-99ed-2f359bc8f4d9">



### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
