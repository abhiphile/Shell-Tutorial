## Basic Commands

### 1. `pwd` (Print Working Directory)
Displays the current directory you're in.
```bash
pwd
```
Example output:
```
/home/user
```

### 2. `ls` (List Directory Contents)
Lists files and directories in the current or specified directory.
```bash
ls
```
Example output:
```
Documents  Downloads  Music  Pictures
```

### 3. `cd` (Change Directory)
Changes the current directory.
```bash
cd /path/to/directory
```
Example:
```bash
cd /home/user/Documents
```

### 4. `echo` (Print Text or Variables)
Prints text or the value of variables to the terminal.
```bash
echo "Hello, World!"
```
Example output:
```
Hello, World!
```

### 5. `cat` (Concatenate and Display File Content)
Displays the contents of a file.
```bash
cat filename.txt
```
Example:
```bash
cat /etc/hosts
```

### 6. `touch` (Create an Empty File)
Creates an empty file or updates the timestamp of an existing file.
```bash
touch newfile.txt
```

### 7. `rm` (Remove Files or Directories)
Deletes files. To remove directories, use `-r` (recursive).
```bash
rm file.txt
```
Example for directories:
```bash
rm -r directory/
```

### 8. `cp` (Copy Files or Directories)
Copies files from one location to another.
```bash
cp source.txt destination.txt
```
For directories, use the `-r` option:
```bash
cp -r source_directory/ destination_directory/
```

### 9. `mv` (Move or Rename Files)
Moves or renames files or directories.
```bash
mv oldname.txt newname.txt
```

### 10. `mkdir` (Make Directory)
Creates a new directory.
```bash
mkdir new_directory
```

### 11. `rmdir` (Remove Empty Directory)
Removes an empty directory.
```bash
rmdir empty_directory
```

### 12. `chmod` (Change File Permissions)
Changes the permissions of a file or directory.
```bash
chmod 755 script.sh
```
This example makes `script.sh` executable by the owner and readable/executable by others.

### 13. `chown` (Change File Ownership)
Changes the owner of a file or directory.
```bash
chown newowner filename
```
Example:
```bash
chown user:group file.txt
```

### 14. `find` (Search for Files)
Searches for files in a directory hierarchy.
```bash
find /path/to/search -name "*.txt"
```

### 15. `grep` (Search Text in Files)
Searches for a specific pattern in a file or output.
```bash
grep "search_term" file.txt
```
Example:
```bash
grep "error" /var/log/syslog
```

These are the most basic yet powerful commands in bash for everyday tasks. Let me know if you need further clarification on any command!