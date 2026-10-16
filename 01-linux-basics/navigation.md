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

2.**ls --List Directory Contents** 

The ls command is used to list the content of a directory, such a files, folders, images, and compressed files.
By default id displays the content of the current working directory. you can also specify a directory path to list the contents.

*Example:*

ls

*Output:*

Documents  Downloads  image.jpg  archive.gz

What I learned:
The ls commands helps me view the files and directories in my current location or in a specified directory.

------------------------------------------------------------------------------------------------

3.**cd --Change Directory**

The cd command is used to navigate between directories in Linux. It allows users to move to a specific directory.

*Example:*

cd Documents 
pwd

*Output*

/home/kali/Documents

What I learned:
The cd command helps me navigate between directories in Linux and access different locations in file system.

------------------------------------------------------------------------------------------------

4.**cd .. --Navigate to the Parent Directory**

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

4.**cd ~  --Navigate to the Home Directory**

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

5.**ls -l --List Detailed file information

The ls -l command displays detailed information about the files and directories in specified directory.
This information typically includes file permissions , the number of hard links, the owner, the group, the file size, the modification date and time, and the file name.

*Example:*

ls -l /home/kali/Documents 

*Output*
