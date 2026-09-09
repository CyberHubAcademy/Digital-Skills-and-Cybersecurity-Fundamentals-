# Week 2: File System and Navigation
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand the Linux file system hierarchy.
- Navigate directories using relative and absolute paths.
- Use basic commands (`ls`, `cd`, `pwd`, `mkdir`, `rmdir`, `touch`, `rm`, `cp`, `mv`).
- Apply options to customize command outputs.
- Perform practical exercises in directory and file management.

---

## 📘 Linux File System Basics
- **Root directory (`/`)**: The top of the file system tree.  
- **Home directory (`/home/username`)**: Default workspace for each user.  
- **System directories**: `/etc` (configuration), `/bin` (binaries), `/var` (logs), `/usr` (user programs).  
- **Path types**:  
  - **Absolute path**: Starts from `/` (e.g., `/home/kali/Desktop`).  
  - **Relative path**: Based on current directory (e.g., `../Documents`).  

---

## 📑 Directory Listing (`ls`)
- **Basic usage**: `ls` → lists files in current directory.  
- **Options**:  
  - `ls -l` → long format (permissions, owner, size, date).  
  - `ls -a` → show hidden files.  
  - `ls -r` → reverse order.  
  - `ls -R` → recursive listing.  
  - `ls -S` → sort by size.  
  - `ls -t` → sort by modification time.  
- **Example**:  
# ls -la


---

## 📂 Change Directory (`cd`)
- **Basic usage**: `cd [path]` → change current directory.  
- **Examples**:  
- `cd ~` → home directory.  
- `cd ..` → parent directory.  
- `cd /` → root directory.  
- `cd -` → previous directory.  
- `cd ~/Documents` → Documents folder in home.  

---

## 📍 Print Working Directory (`pwd`)
- **Usage**: `pwd` → shows current directory path.  
- **Example**:  
# /home/kali/Documents


---

## 🗂️ Create Directory (`mkdir`)
- **Basic usage**: `mkdir newdir` → create directory.  
- **Options**:  
- `mkdir -p /path/dir/dir` → create parent directories if needed.  
- `mkdir -m 755 newdir` → set permissions.  
- `mkdir -v newdir` → verbose output.  

---

## 🗑️ Remove Directory (`rmdir`)
- **Basic usage**: `rmdir directory` → remove empty directory.  
- **Options**:  
- `rmdir -v directory` → verbose output.  
- `rmdir --ignore-fail-on-non-empty directory` → ignore errors if not empty.  

---

## 📄 Create File (`touch`)
- **Basic usage**: `touch file.txt` → create empty file.  
- **Options**:  
- `touch -a file.txt` → update access time.  
- `touch -m file.txt` → update modification time.  
- `touch -t 202609200000 file.txt` → set custom timestamp.  

---

## 🗑️ Remove File (`rm`)
- **Basic usage**: `rm file.txt` → delete file.  
- **Options**:  
- `rm -i file.txt` → prompt before removal.  
- `rm -f file.txt` → force removal.  
- `rm -v file.txt` → verbose output.  
- `rm -d directory` → remove empty directory.  

---

## 📋 Copy Files (`cp`)
- **Basic usage**: `cp file1 file2` → copy file1 to file2.  
- **Options**:  
- `cp -i file1 file2` → prompt before overwrite.  
- `cp -v file1 file2` → verbose output.  
- `cp -r dir1 dir2` → copy directories recursively.  

---

## 📦 Move/Rename Files (`mv`)
- **Basic usage**: `mv file1 file2` → move or rename file.  
- **Options**:  
- `mv -i file1 file2` → prompt before overwrite.  
- `mv -v file1 file2` → verbose output.  

---

## 🧪 Practical Exercise
Students should:
1. Create a directory named `Week2_Practice`.  
2. Navigate into it using `cd`.  
3. Create three files: `file1.txt`, `file2.txt`, `file3.txt`.  
4. Copy `file1.txt` to `backup.txt`.  
5. Rename `file2.txt` to `report.txt`.  
6. Remove `file3.txt`.  
7. Print the current working directory.  
8. List all files with `ls -l`.  

---

## 📜 Assignment
Prepare a step‑by‑step demonstration (screenshots or terminal logs) showing:
- Directory creation and navigation.  
- File creation, copying, renaming, and deletion.  
- Use of absolute and relative paths.  
- Submission in `Assignments/File_System_Practice/`.  

