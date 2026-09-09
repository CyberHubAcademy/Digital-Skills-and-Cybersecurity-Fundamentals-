# Week 2: Package Installation & Management
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD 

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand the role of package managers in Linux.
- Install, update, and remove software packages.
- Use APT (Debian/Ubuntu) and recognize other package managers (YUM/DNF).
- Search for packages and manage dependencies.
- Perform practical exercises in package management.

---

## 📘 Introduction
A **package manager** is a utility that automates the installation, update, and removal of software packages. It ensures dependencies are resolved and conflicts are avoided.  

### Benefits
- Centralized software management.  
- Easy installation and removal.  
- Automatic updates and security patches.  
- Dependency resolution.  

---

## 📑 Common Package Managers
- **APT (Advanced Package Tool)** → Debian-based systems (Ubuntu, Kali).  
- **YUM/DNF** → Red Hat-based systems (CentOS, Fedora).  

---

## 📦 APT Commands (Debian/Ubuntu)
### Update Package List
sudo apt update

### Upgrade Packages
sudo apt upgrade
sudo apt full-upgrade

### Install Package
sudo apt install package_name

### Remove Package
sudo apt remove package_name
sudo apt autoremove  
# remove unused dependencies

### Search for Package
sudo apt search keyword

---

## 🌐 Downloading Packages
### Using `wget`
- Download files from the internet.  
wget http://example.com/file.zip

### Using `git clone`
- Download repositories from GitHub.  
git clone https://github.com/notepad-plus-plus/notepad-plus-plus.git (github.com in Bing)


---

## 🧪 Practical Exercise
Students should:
1. Update package lists using `sudo apt update`.  
2. Install a text editor (e.g., `gedit`).  
3. Verify installation with `gedit --version`.  
4. Remove the package using `sudo apt remove gedit`.  
5. Use `sudo apt search browser` to find available web browsers.  
6. Download a file using `wget`.  
7. Clone a GitHub repository using `git clone`.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Updating and upgrading packages.  
- Installing and removing a package.  
- Searching for packages.  
- Using `wget` and `git clone`.  

Save in:  
Week2_Linux_Networking/Assignments/Package_Management_Practice.md
