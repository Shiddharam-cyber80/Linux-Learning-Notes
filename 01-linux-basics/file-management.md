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
