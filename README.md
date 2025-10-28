#  GTK-Based File Manager

A simple yet powerful **File Manager** built using **C** and the **GTK+ 3** library.  
It allows users to easily browse, manage, and organize files and folders through a graphical user interface.

---

## Features
- View files and folders with icons  
- Open and navigate directories  
- Create and delete folders  
- Copy, cut, paste, and rename files  
- Display copy progress using a progress bar  
- Detect and display all available drives  
- Search files and folders  

---

## 🧰 Technologies Used
- **Language:** C  
- **GUI Toolkit:** GTK+ 3  
- **Headers:** `<dirent.h>`, `<sys/stat.h>`, `<gio/gio.h>`, `<windows.h>`  

---

## ⚙️ How to Build
### 🪟 On Windows (using MinGW)
1. Make sure GTK+ 3 is installed.  
2. Run the following command in the terminal:

   ```bash
   gcc main.c -o FileManager.exe $(pkg-config --cflags --libs gtk+-3.0)
