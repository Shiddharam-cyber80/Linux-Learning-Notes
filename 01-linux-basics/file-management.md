# 1. mkdir --(Make Directory)
The mkdir command is used to create new directories in Linux.

*Example*
```bash
mkdir folder1
ls
cd folder1
pwd
```
*Output*
```bash
/home/kali/folder
```
*What I learned:*

The mkdir command helps me create new directories to organize files and other directories in Linux. 

---------------------------------------------------------------------------------------------------

# 2. touch --(Create Files)
The touch command is commonly used to create empty files in Linux. 
If a file already exits, it updates the file's access and modification timestamps without changing its contents.

*Example*
```bash
touch notes1.txt
```
*Output*
```bash
note1.txt
```
Other files and directories may also appear in output.

*What I learned*

The touch command helps to create empty files in Linux and update timestamps of existing files.

----------------------------------------------------------------------------------------------------

# 3. cp --(Copy Files and Directories)
The cp command is used to copy files in Linux. To copy directories and their contents, the -r (recursive)
option is generally required.

*Example --copy a file*
```bash
cp file.txt file1.txt
```
This create a copy file.txt named file1.txt, assuming the source file exists.

*Example --copy a directory*
```bash
cp -r folder1 folder2
```
This copies the folder1 directory and its contents into a new directory named folder2, provided the destination
does not already exist.

*What I learned:*

The cp command helps me copy files in Linux . I also learned that I generally need the -r option to copy
directories and their contents.

----------------------------------------------------------------------------------------------------

# 4. mv --(Move and Rename Files and Directories)

The mv command is used to move files and directories from one location to another. It can also be used to rename files and directories.

*Example 1 --Rename a file:*
```bash
mv file.txt file01.txt
```
This rename file.txt to file01.txt , assuming the source file exists and the destination name is available.

*Example 2 --Move a file:* 
```bash
mv /home/kali/file01.txt folder1/
```
This moves file01.txt into the folder1 directory , assuming the source file and destination directory exit.

*What I learned:*
The mv command helps me rename files and directories and move them from one location to another in Linux.

----------------------------------------------------------------------------------------------------

# 5. rm --(Remove Files and Directories)

The rm command is used to remove files in Linux. To remove directories and their contents, we can use the -r (recursive) option.

*Example 1 --Remove a File*
```bash
rm file01.txt
```
This remove the file named file01.txt.

*Example 2 --Remove a directory*
```bash
rm -r folder1
```
This removes the folder1 directory and its contents.

*What I learned:*

The rm command helps me remove the files and directories in Linux. I also learned that recursive deletion can be dangerous because it may remove multiple files and directories.
