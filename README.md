# ⚡ EasyCharge – Electric Car Charging Station Manager

## 📌 Overview
EasyCharge is a C project (Visual Studio solution) that simulates the management of electric car charging stations.  
It provides functionality for handling stations, ports, and cars using various data structures (linked lists, queues, and binary search trees).  

The system allows:
- Managing charging stations and their ports  
- Tracking cars waiting in line  
- Assigning cars to charging stations  
- Viewing and updating system data from text files  

---

## 🗂 Project Structure
```
Project1.sln                → Visual Studio solution file  
Project1/  
│── main.c                  → Main entry point  
│── menu.c                  → Menu system for user interaction  
│── struct.c                → Data structure definitions  
│── List.c                  → Linked list implementation  
│── Queue.c                 → Queue implementation (for cars in line)  
│── BST.c                   → Binary Search Tree (for stations)  
│── Cars.txt                → Data file: list of cars  
│── LineOfCars.txt          → Data file: cars waiting in line  
│── Ports.txt               → Data file: charging ports  
│── Stations.txt            → Data file: charging stations  
```

---

## ⚙️ Installation & Build
1. Open **Visual Studio 2019/2022**.  
2. Load the solution file:  
   ```
   Project1.sln
   ```
3. Build the project (`Ctrl + Shift + B`).  
4. Run the program (`F5`).  

> 🔹 Make sure the text data files (`Cars.txt`, `LineOfCars.txt`, `Ports.txt`, `Stations.txt`) are placed in the **working directory** (usually the `Project1/` folder).  

---

## ▶️ Usage
When running, the program displays a **menu system** that allows you to:  
1. View available charging stations and ports.  
2. Display cars in line waiting for charging.  
3. Assign a car to a station.  
4. Remove a car after charging.  
5. Save and update data to text files.  

---

## 📚 Data Structures Used
- **Linked List** – for dynamic management of ports and cars.  
- **Queue** – for handling cars waiting in line.  
- **Binary Search Tree (BST)** – for efficient management of charging stations.  

---

## 🧪 Example Input Files
- `Cars.txt` – Car details  
- `LineOfCars.txt` – Queue of cars waiting  
- `Ports.txt` – Information about charging ports  
- `Stations.txt` – Information about charging stations  

---

## 🚀 Future Improvements
- GUI interface for easier interaction  
- Database integration instead of flat `.txt` files  
- More advanced simulation of charging times and priorities  

---

## 👨‍💻 Authors
Developed as part of an academic project by Bshar Hussein computer engineering student   
