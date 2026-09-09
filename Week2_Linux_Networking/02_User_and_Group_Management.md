# Week 2: User and Group Management
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand the concept of users and groups in Linux.
- Differentiate between root, system, and regular users.
- Create, modify, and delete users and groups.
- Manage group memberships.
- Apply practical exercises in user and group administration.

---

## 👥 Types of Users
- **Root User**: Superuser with unlimited privileges (`username = root`).  
- **System Users**: Created by the system for services (e.g., `http`, `ftp`, `mysql`).  
- **Regular Users**: Accounts for individuals with limited privileges.  
- **Group Users**: Members of a group sharing common permissions.  

### User Characteristics
- **Username**: Unique identifier.  
- **UID (User ID)**: Numeric identifier.  
- **GID (Group ID)**: Numeric identifier for primary group.  
- **Home Directory**: Default workspace.  
- **Password**: Secures account.  
- **Shell**: Interactive terminal (e.g., `/bin/bash`).  

---

## 📑 User Commands
- **useradd [username]** → create new user.  
- **usermod [options] [username]** → modify existing user.  
- **userdel [username]** → delete user.  

### Examples
- **sudo adduser student1**
- **sudo usermod -aG sudo student1**
- **sudo userdel student1**

---

## 👥 Groups
A group is a collection of users who share common permissions and resources.  

### Types of Groups
- **Primary Group**: Default group assigned at user creation.  
- **Secondary Group**: Additional groups providing extra permissions.  

### Benefits
- Simplified user management.  
- Efficient permission control.  
- Improved access management.  

---

## 📑 Group Commands
- **groupadd [groupname]** → create new group.  
- **groupmod [options] [groupname]** → modify group.  
- **groupdel [groupname]** → delete group.  

### Examples
- **sudo groupadd developers**
- **sudo usermod -aG developers student1**
- **sudo groupdel developers**


---

## 🔒 Checking Users and Groups
- **id [username]** → display UID, GID, and group memberships.  
- **getent passwd** → list all users.  
- **groups [username]** → show groups a user belongs to.  

---

## 🧪 Practical Exercise
Students should:
1. Create two new users (`user1`, `user2`).  
2. Assign them passwords.  
3. Create a group called `trainees`.  
4. Add both users to the `trainees` group.  
5. Verify group membership using `id` and `groups`.  
6. Delete one user and confirm removal.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- User creation and deletion.  
- Group creation and membership assignment.  
- Verification of users and groups.  

Save in:  
Week2_Linux_Networking/Assignments/User_Group_Practice.md

