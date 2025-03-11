# Ex-01-Linux-Commands
# NAME:pavithra s
#REG NO:212223230147

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
![276809803-14313087-1efa-4ac2-9f64-f6cd0b93b145](https://github.com/user-attachments/assets/ab422181-719e-4b65-b059-d2a84c6f2f8f)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![276809856-324ded1a-70f3-4150-bcb2-b4a9d6ad1fd6](https://github.com/user-attachments/assets/6cd07e44-1b18-4ba5-90e7-4e6ee76419ac)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![276809884-78b77518-86db-41df-a320-aa463fb9c546](https://github.com/user-attachments/assets/fef8b509-03b0-4856-a57a-65b137cc9f9d)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![276809915-c01cbdc7-8259-49ad-b5f5-c00346e4ec78](https://github.com/user-attachments/assets/59f23650-63a7-4f44-8ac8-7af62c2cdb4d)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![276809943-19fe100a-f515-4866-9573-6879fa277ef3](https://github.com/user-attachments/assets/298b5c15-fc7f-438e-8048-abfcaefc9fec)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![276809963-eab5eaf1-5752-4910-b8fd-e417b3980fbb](https://github.com/user-attachments/assets/bfe97b21-e1e3-4bd9-a47d-580aab3a7184)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![276809983-914e3c44-960e-4951-b314-e1ecebadcc51](https://github.com/user-attachments/assets/6a33293c-7e81-484e-83dd-08af68413870)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![276810016-7a544174-c379-4e25-aa5c-b63fbc43e69c](https://github.com/user-attachments/assets/7003e715-db57-464e-9699-423074cf271c)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![276810048-5eb89bea-c625-431f-82c6-349496ca4ea5](https://github.com/user-attachments/assets/e1ab4949-44c8-4952-bece-8aa0b4c3f40d)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![276810186-29b4bc14-34c2-45c9-9a58-0d6de4c7114a](https://github.com/user-attachments/assets/61fec5a5-c99f-45ee-a7f7-e5fb261e2583)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![276810227-89e68de2-8aef-4415-a6b7-b1d03eed9c71](https://github.com/user-attachments/assets/b3d3704f-fcbd-47ae-8a7b-e2ce933f932d)


### 13)	tail Command


The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![276810290-6b9ea3ba-a82b-45ac-93fc-f4e94fbd6e61](https://github.com/user-attachments/assets/3ff9e86b-551a-4a7a-b52e-7194190b9e86)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![276810341-698d86b6-121f-49e8-b792-37dddf2bc0b3](https://github.com/user-attachments/assets/a9b2afb5-9ce2-4878-85e1-dac74c80f5d7)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![276810436-f630a18b-99d1-4c1b-887b-e0dec6c95d3e](https://github.com/user-attachments/assets/b292513b-8c1e-4e46-b23c-719096843296)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![276810480-a8edd60a-3083-4f91-97b1-03794f9ce777](https://github.com/user-attachments/assets/d6066e28-f55a-4002-9f39-42ae46b08e3c)


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

![276810579-72cb380a-d600-477f-b3b5-51168408c952](https://github.com/user-attachments/assets/410f9355-48d1-4b79-a1ab-2ded3650d4da)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![276810637-c6330223-124c-4c9b-a69d-d8c18dce6984](https://github.com/user-attachments/assets/90749fa9-ab08-4a23-9a67-fc976cf8fb42)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![276810702-cbb69a2a-f209-4133-8f35-7da29b171e5d](https://github.com/user-attachments/assets/24b0e0e5-7b0c-4881-a92e-2c787d5dbce3)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![276810948-6aa29466-366e-43b9-8dbb-f9427b3371d6](https://github.com/user-attachments/assets/e8da20fe-e347-40b4-a025-e9d53b3bc0fe)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![276811008-49166e6e-6546-4905-955b-208136ee701a](https://github.com/user-attachments/assets/62a8ee1a-8466-4458-b0a4-dd823696b9c3)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![276811069-d3b9c042-76ac-49e6-8921-20593a2aa984](https://github.com/user-attachments/assets/0de974e1-01b8-4df6-a916-bce6aba7d36c)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![276811117-a96f0eb7-6475-4ea0-952e-2b81a56dc6ba](https://github.com/user-attachments/assets/7e44c971-f094-42b3-9d70-ce39cb540413)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![276811163-9f44ad79-6697-4c16-bc7b-f10141b80747](https://github.com/user-attachments/assets/aeb16faf-4aa8-4988-b7a2-b1f1d9b933fa)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![276811232-00e6a379-3469-48a8-adde-f2abb5498be6](https://github.com/user-attachments/assets/939fd86f-50a7-45a7-9cf9-025c58c7e86c)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![276811408-c04c158b-9559-4007-b1f1-37c47f2f97aa](https://github.com/user-attachments/assets/11c02ecd-9aca-498c-be46-76229dd8d2d2)



### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”



## Result:
Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
