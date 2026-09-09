# Week 2: File Permissions
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand the concept of file permissions in Linux.
- Differentiate between read, write, and execute permissions.
- Apply permissions to users, groups, and others.
- Use `chmod`, `chown`, and `chgrp` commands effectively.
- Perform practical exercises in permission management.

---

## 📘 Introduction to Permissions
Permissions determine what actions a user can perform on a file or directory.  

### Types of Permissions
- **Read (r)** → view contents of a file or list directory.  
- **Write (w)** → modify or delete a file, create new files in a directory.  
- **Execute (x)** → run a file as a program or script, or access a directory.  

### Categories of Users
- **Owner (u)** → the user who created the file.  
- **Group (g)** → members of the file’s group.  
- **Others (o)** → all other users on the system.  

---

## 📑 Permission Notation
- **Symbolic Notation**:  
  - `rwx` → read, write, execute.  
  - `rw-` → read, write only.  
  - `r--` → read only.  
- **Numeric Notation**:  
  - r = 4, w = 2, x = 1.  
  - Add values to set permissions:  
    - `7 = rwx`  
    - `6 = rw-`  
    - `5 = r-x`  
    - `4 = r--`  

---

## 📑 Permission Commands
- **chmod** → change file permissions.  
- **chown** → change file ownership.  
- **chgrp** → change group ownership.  

### Examples
chmod 754 file.txt        
# Owner=rwx, Group=rx, Others=r
chmod u=rw,g=r,o=r file.txt
chown student1 file.txt   
# Change owner to student1
chgrp trainees file.txt  
# Change group to trainees

---

## 🔒 Viewing Permissions
- Use `ls -l` to display file permissions.  
- Example output:  
-rwxr-xr-- 1 user group 0 Sep 9 13:40 file.txt

- `-` → regular file.  
- `rwx` → owner permissions.  
- `r-x` → group permissions.  
- `r--` → others permissions.  

---

## 🧪 Practical Exercise
Students should:
1. Create a file named `practice.txt`.  
2. Change its permissions to:  
 - Owner = rwx  
 - Group = rx  
 - Others = r  
 Using both numeric (`chmod 754`) and symbolic (`chmod u=rwx,g=rx,o=r`) methods.  
3. Verify changes with `ls -l`.  
4. Change ownership of the file to another user.  
5. Change group ownership to `trainees`.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Permission changes using both numeric and symbolic notation.  
- Ownership changes with `chown`.  
- Group changes with `chgrp`.  
- Verification using `ls -l`.  

Save in:  
Week2_Linux_Networking/Assignments/File_Permissions_Practice.md
