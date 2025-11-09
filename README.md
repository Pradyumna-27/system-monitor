# ✅ Linux System Monitor — Capstone Project

This project is a **Linux-based System Monitor** implemented using **C++** and the **/proc** filesystem.  
It displays real-time system information including:

✅ CPU Usage  
✅ Memory Usage  
✅ Running Processes  
✅ Kill Process Function  
✅ Sorting by Memory  
✅ Clean CLI-based UI  

This project is part of the **Capstone Project Assignment** for the Linux System Programming module.

---

## ✅ Features

### 📌 **CPU Usage Monitoring**
- Reads `/proc/stat`
- Calculates CPU utilization percentage
- Updates on each refresh

### 📌 **Memory Usage Monitoring**
- Reads `/proc/meminfo`
- Shows:
  - Total Memory
  - Used Memory
  - Available Memory

### 📌 **Process Management**
- Lists all running processes from `/proc`
- Shows:
  - PID  
  - Memory usage (KB)  
  - Process Name  

### 📌 **Sorting**
- Sort processes by memory usage  
- Default sorting: None

### 📌 **Kill Processes**
Users can kill any process using:

