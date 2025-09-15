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

<img width="767" height="52" alt="image" src="https://github.com/user-attachments/assets/560b8387-978d-4199-a266-4ad7299c916c" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="314" height="75" alt="image" src="https://github.com/user-attachments/assets/d8a5bb23-ec6c-4ea6-8c85-27c555e3727c" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="302" height="50" alt="image" src="https://github.com/user-attachments/assets/abff5647-6deb-4a15-979a-f59b7b133ae7" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="260" height="87" alt="image" src="https://github.com/user-attachments/assets/0ad288fc-d6de-4ef8-b6f4-de2c19990c5f" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="372" height="109" alt="image" src="https://github.com/user-attachments/assets/9c173afc-9a7b-4363-9726-0d32e5fbfe1e" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="455" height="128" alt="Screenshot 2025-09-08 101149" src="https://github.com/user-attachments/assets/ab1cc9b6-2ecf-4ef5-9d9f-ef16ba66e732" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="280" height="292" alt="image" src="https://github.com/user-attachments/assets/86efc755-414c-4b6b-83b3-cd75559eac7b" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="400" height="51" alt="Screenshot 2025-09-08 112444" src="https://github.com/user-attachments/assets/d9645e4f-a74b-4243-864b-731d7446b538" />

<img width="646" height="455" alt="image" src="https://github.com/user-attachments/assets/65b7ccf3-4c15-4427-ae38-4e57fbb9024b" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="252" height="105" alt="image" src="https://github.com/user-attachments/assets/b131abd5-a939-4a39-9c2d-09c4e507018e" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="420" height="62" alt="Screenshot 2025-09-08 112431" src="https://github.com/user-attachments/assets/b327e709-5e3a-4534-8596-fa681e9ad2f5" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="607" height="113" alt="Screenshot 2025-09-08 112713" src="https://github.com/user-attachments/assets/9da356ce-6e17-4a29-abb4-c76828efae03" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="242" height="203" alt="Screenshot 2025-09-08 112852" src="https://github.com/user-attachments/assets/49f58cca-d40c-43f3-82c5-1c0160b56806" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 <img width="307" height="207" alt="Screenshot 2025-09-08 113003" src="https://github.com/user-attachments/assets/8576bc6d-41d0-483b-a783-8c6f4f05c167" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1679" height="83" alt="Screenshot 2025-09-08 113039" src="https://github.com/user-attachments/assets/28881c1c-d38e-4ef3-876c-3b88e129ce4c" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="250" height="65" alt="Screenshot 2025-09-08 113140" src="https://github.com/user-attachments/assets/7008c614-37d5-444b-9159-d1c83e1e3999" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="342" height="223" alt="Screenshot 2025-09-08 113351" src="https://github.com/user-attachments/assets/6ee33176-51f2-45ec-a6f2-4143cf311c73" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="355" height="48" alt="image" src="https://github.com/user-attachments/assets/a41ccad5-acae-46c5-89ec-4a474f7ad32c" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="279" height="152" alt="Screenshot 2025-09-15 100415" src="https://github.com/user-attachments/assets/1a55a52b-a9d8-4fcb-bb8e-ff823b736f7b" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="516" height="112" alt="image" src="https://github.com/user-attachments/assets/b974791e-2413-4840-a940-ee41c711a8d9" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="1446" height="326" alt="Screenshot 2025-09-15 101148" src="https://github.com/user-attachments/assets/61625b87-3b61-44b7-b2be-65928d483f89" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="708" height="98" alt="image" src="https://github.com/user-attachments/assets/b06468aa-866f-4d9d-95b6-97801583cdf1" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="497" height="107" alt="image" src="https://github.com/user-attachments/assets/c290453d-dfab-4b40-bfbf-43a828e535a6" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="315" height="65" alt="Screenshot 2025-09-08 114537" src="https://github.com/user-attachments/assets/4690b769-8ede-49d8-875b-f1f89b7aa9ac" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="326" height="122" alt="Screenshot 2025-09-08 113619" src="https://github.com/user-attachments/assets/8aa5cc99-d6d3-484d-8f61-30bfb13dd071" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="312" height="162" alt="Screenshot 2025-09-08 113657" src="https://github.com/user-attachments/assets/3038ebb2-189d-4ee0-bb64-bea391092ca1" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="760" height="221" alt="Screenshot 2025-09-08 113726" src="https://github.com/user-attachments/assets/ed41fde0-da39-474e-914c-7ea31815eafd" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
