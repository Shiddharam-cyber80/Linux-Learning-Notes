1.**pwd --(Print Working Directory)**

The pwd command displays the path of the current working directory.
In simple words, it works like a GPS for the terminal, helping you identify your current location in the directory structure.

*Example:* 

pwd

*Output:*

/home/kali

What I learned:
The pwd command helps me identify my current working directory in Kali Linux.

----------------------------------------------------------------------------------------------------

2.**ls --(List Directory Contents)** 

The ls command is used to list the content of a directory, such a files, folders, images, and compressed files.
By default id displays the content of the current working directory. you can also specify a directory path to list the contents.

*Example:*

ls

*Output:*

Documents  Downloads  image.jpg  archive.gz

What I learned:
The ls commands helps me view the files and directories in my current location or in a specified directory.

------------------------------------------------------------------------------------------------

3.**cd --(Change Directory)**

The cd command is used to navigate between directories in Linux. It allows users to move to a specific directory.

*Example:*

cd Documents 
pwd

*Output*

/home/kali/Documents

What I learned:
The cd command helps me navigate between directories in Linux and access different locations in file system.

------------------------------------------------------------------------------------------------

4.**cd .. --(Navigate to the Parent Directory)**

The cd .. command is used to move from the current directory to its parent directory.

*Example:*

If I am inside a Documents directory and want to return to its parent directory , I can use the cd .. command

cd Documents 
pwd
cd ..
pwd

*Output*

/home/kali/Documents
/home/kali

What I learned:
the cd .. command helps me navigate one level up in the Linux directory structure.

------------------------------------------------------------------------------------------------

4.**cd ~  --(Navigate to the Home Directory)**

The cd ~ command is used to navigate to the current user's home directory.
The tilde(~) symbol represents the home directory of the current user.

*Example*

cd ~ 
pwd

*Output* 

/home/kali

What I learned:
The cd ~ command helps me return to my home directory from any location in the Linux file system.

------------------------------------------------------------------------------------------------

5.**ls -l --(List Detailed file information)

The ls -l command displays detailed information about the files and directories in specified directory.
This information typically includes file permissions , the number of hard links, the owner, the group, the file size, the modification date and time, and the file name.

*Example:*

ls -l /home/kali/Documents 

*Output*

-rw-r--r-- 1 kali kali 56 oct 16 14:30 file1.txt

What I learned:
The ls -l command helps me view detailed information about files and directories, including their permissions, ownership, and file sizes.

----------------------------------------------------------------------------------------------------

**ls -a --(List Hidden Files and Directories)**
The ls -a command is used to list all entries, including hidden files and directories, in the specified directoy.
In Linux, hidden files and directories usually start with a doe (.) . These often include configuration files, such as .bashrc and .zshrc .

*Example*

ls -a ./

*Output*

. .. .bashrs .zshrc Documents Downloads 

What I learned:
The ls -a command helps me view hidden files and directories in the current directory.

----------------------------------------------------------------------------------------------------

**ls -la --(List All Entries in Long Format)**

The ls -la command is used to display all entries, including hidden files and directories, in long format.
It shows detailed information such as file permissions , the number of hard links, ownerships , file size, and modification data and time.

*Example*

ls -la

*Output*

drwxr-xr-x 5 kali kali 4096 oct 19 10:00 .
drwxr-xr-x 20 kali kali 4096 oct 19 9:00 ..
-rw-r--r-- 1 kali kali 220 oct 19 09:30 .bashrc
-rw-r--r-- 1 kali kali 100 oct 19 09:45 .zshrc

What I learned:
The ls -la command helps me view detailed information about all files and directories, including hidden entries.



