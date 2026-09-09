# Week 2: Advanced File Operations & Text Processing
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Perform advanced file operations beyond basic create, copy, and delete.
- Use text processing tools (`grep`, `awk`, `sed`) for searching and editing.
- Apply file search commands like `find`.
- Work with both GUI and CLI text editors.

---

## 📘 Advanced File Operations
- **Creation**: Create new files or directories.  
- **Deletion**: Remove files or directories.  
- **Copy**: Duplicate files or directories.  
- **Move**: Relocate files or directories.  
- **Rename**: Change file or directory names.  

---

## 🔍 File Searching (`find`)
The `find` command searches for files and directories based on criteria. 
find [path] [options] [expression]


### Examples
- `find . -name "file.txt"` → search for `file.txt` in current directory and subdirectories.  
- `find / -type f -size +1M` → find files larger than 1MB in entire system.  
- `find . -mtime -1` → find files modified in last 24 hours.  

---

## 📑 Text Processing Tools
### `grep`
- Searches for patterns in text.  
- Example:  
grep "error" logfile.txt


### `awk`
- Pattern scanning and processing.  
- Example:  
awk '{print $1,$3}' data.txt

### `sed`
- Stream editor for modifying text.  
- Example:  
sed 's/error/warning/g' logfile.txt


---

## 🖊️ Text Editors
### GUI Editors
- **gedit**  
- **mousepad**

### CLI Editors
- **nano** → beginner-friendly.  
- **vim** → powerful, advanced editing.  

---

## 🧪 Practical Exercise
Students should:
1. Create a file named `log.txt` and add sample text.  
2. Use `grep` to search for a keyword in the file.  
3. Use `awk` to print specific columns from a data file.  
4. Use `sed` to replace a word in `log.txt`.  
5. Use `find` to locate `log.txt` in the system.  
6. Edit a file using `nano` or `vim`.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Use of `find` to search files.  
- Use of `grep`, `awk`, and `sed` for text processing.  
- Editing a file with both CLI and GUI editors.  

Save in:  
Week2_Linux_Networking/Assignments/Advanced_File_Operations_Practice.md

### Syntax
