
# Linux Basic Commands

These are basic Ubuntu commands I have practised while learning Linux.

## 1. pwd — Print Working Directory

Displays the path of the current directory.

```bash
pwd
```
Output:
        /home/aneesa
        
## 2. ls — List Directory Contents

Lists files and directories.

```bash
ls
ls -l
ls -a
```
Output:     (All files or folders you have will be listed)
      Downloads Documents Pictures Practice-file 
      
- `ls`: lists directory contents.
- `ls -l`: displays detailed information.
- `ls -a`: includes hidden entries.

## 3. cd — Change Directory

Moves to another directory.
Directory in Linux as Folder in Windows.

```bash
cd Documents (Enter directory/folder name)
cd .. 
cd ~          
```

- `cd Documents`: enters Documents.
- `cd ..`: moves to the parent directory.
- `cd ~`: returns to the home directory.

## 4. mkdir — Make Directory

Creates a directory.

```bash
mkdir practice
```
Output:    A directory (folder) named as practice will be created.

## 5. touch — Create an Empty File

Creates an empty file if it does not exist.

```bash
touch notes.txt
```
Output:
        Creates Empty file but if the same file already exists it will update its Timestamp.
        Timestamp --> Last time you visited or updated your file.
       
## 6. cp — Copy Files

Copies a file to another location. (The same file will exist in two places.)

```bash
cp notes.txt notes-backup.txt
```

## 7. mv — Move or Rename Files

Renames a file or moves it to another location.

Rename file or directory:
```bash
mv notes.txt linux-notes.txt
```
Move file or directory:
```bash
mv notes.txt linux-notes/
```
* / --> it shows move to the directory.
  
## 8. rm — Remove Files

Removes a file.

```bash
rm linux-notes.txt
```

**Caution:** `rm` can permanently delete files. Check the filename before executing it.

## Key Learning

Linux commands allow users to navigate directories, manage files, and perform system tasks through the terminal.

I will continue adding commands and practical examples as I learn.
