## Summary: Linux Monitoring v1.0

This project involves basic Bash scripting and system research on Linux. The task is divided into multiple chapters, each building upon the previous one to develop a comprehensive system monitoring tool.

### **Chapter I: Introduction**  
A new system administrator struggles with collecting system data manually. The user steps in to help by developing Bash scripts.

### **Chapter II: Bash & Shell Basics**  
Explains Bash and Shell scripting fundamentals, including their role as command interpreters and scripting languages.

### **Chapter III: Task Breakdown**  
- **Part 1: First Effort**  
  - A simple script that prints a given parameter unless it is a number.  

- **Part 2: System Research**  
  - A script that outputs system details such as hostname, timezone, user, OS, uptime, IP, RAM, disk space, and more.  
  - Option to save the output to a timestamped file.  

- **Part 3: Visual Output Design**  
  - Enhances the system research script with customizable colors for text and background.  
  - Ensures that text and background colors do not match.  

- **Part 4: Configurable Output Design**  
  - Uses a configuration file to define default colors instead of requiring parameters.  
  - Displays the selected color scheme in the output.  

- **Part 5: File System Research**  
  - A script that analyzes a given directory and outputs:  
    - Total folders and files.  
    - Largest folders and files.  
    - File types (config, logs, executables, archives, etc.).  
    - Top executable files with their MD5 hash.  
    - Script execution time.  

Each script is designed to run on **Ubuntu Server 20.04 LTS** and follows structured coding guidelines.