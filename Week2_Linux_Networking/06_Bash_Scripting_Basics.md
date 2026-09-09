# Week 2: Bash Scripting Basics
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand the fundamentals of bash scripting.
- Create, edit, and execute bash scripts.
- Use variables, conditionals, loops, and functions.
- Automate repetitive tasks with scripts.
- Apply best practices for scripting in Linux.

---

## 📘 Introduction
A **bash script** is a text file containing a series of commands to be executed by the Linux shell.  
Scripts are used to automate tasks, simplify complex processes, and improve productivity.

### Benefits of Scripting
- Automate repetitive tasks.  
- Simplify complex processes.  
- Improve accuracy and consistency.  
- Enhance flexibility and configuration management.  
- Support system administration tasks.  

---

## 📑 Basics of Bash Scripting
### Shebang
- First line of a script specifies the interpreter.
  # !/bin/bash
  
### Creating a Script
1. Open a text editor (`nano`, `vim`, or `gedit`).  
2. Write commands in the file.  
3. Save with `.sh` extension (e.g., `welcome.sh`).  
4. Make executable:  
# chmod +x welcome.sh
5. Run script:  
./welcome.sh


---

## 📑 Variables
- **Definition**: Store data for use in scripts.  
- **Rules**:  
- Can contain letters, numbers, and underscores.  
- Cannot start with a number.  

### Types
- **Scalar**: Single value.  
- **Array**: Multiple values.  
- **Integer**: Whole numbers.  
- **String**: Text values.  
- **Local**: Accessible only within a function.  
- **Global**: Accessible throughout the script.  

### Example
name="Umar"
echo "Hello $name"

---

## 📑 Conditionals
Allow scripts to make decisions.  

### Example
if [ -f file.txt ]; then
echo "File exists"
else
echo "File not found"
fi


---

## 📑 Loops
Used to repeat tasks.  

### For Loop


---

## 📑 Loops
Used to repeat tasks.  

### For Loop
for i in 1 2 3
do
echo "Number $i"
done


### While Loop
count=1
while [ count -le 3 ] do echo "Count $count" count=((count+1))
done


---

## 📑 Functions
Organize reusable code.  

### Example
greet() {
echo "Welcome, $1"
}
greet Umar

---

## 🧪 Practical Exercise
Students should:
1. Create a script `welcome.sh` that prints a welcome message.  
2. Add a variable for student name and display it.  
3. Write a conditional to check if a file exists.  
4. Write a loop to print numbers 1–5.  
5. Create a function that greets the user.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Script creation and execution.  
- Use of variables, conditionals, loops, and functions.  
- Proper use of comments for readability.  

Save in:  
Week2_Linux_Networking/Assignments/Bash_Scripting_Practice.md

