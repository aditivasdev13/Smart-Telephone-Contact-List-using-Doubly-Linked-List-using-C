# 📱 Smart Telephone Contact Manager (C Language)

## 📌 Project Overview

The **Smart Telephone Contact Manager** is a console-based application developed in the C programming language. This project allows users to efficiently manage their contact list using a dynamic data structure. It supports operations such as adding, deleting, updating, searching, and displaying contacts.

Unlike traditional implementations that use arrays, this project uses a **Doubly Linked List**, enabling efficient traversal in both forward and backward directions. This makes the application more flexible and memory-efficient.

---

## 🎯 Objectives

* To implement a real-world contact management system using C.
* To understand and apply the concept of **Doubly Linked Lists**.
* To perform dynamic memory allocation using `malloc`.
* To provide efficient data manipulation operations such as insertion, deletion, and search.

---

## ⚙️ Features

* ➕ Add new contacts (Name & Phone Number)
* 📄 Display contacts (Forward Traversal)
* 🔄 Display contacts (Backward Traversal)
* 🔍 Search contacts using **partial name matching**
* ✏️ Update existing contact details
* ❌ Delete contacts
* 🧠 Efficient memory management using dynamic allocation

---

## 🧩 Data Structures Used

* **Doubly Linked List**

  * Each node contains:

    * Name
    * Phone number
    * Pointer to next node
    * Pointer to previous node

---

## 🚀 How It Works

1. The program starts with an empty contact list.
2. Users interact through a menu-driven interface.
3. Contacts are dynamically added to the list.
4. Users can navigate forward and backward through contacts.
5. Search functionality allows partial matching of names.
6. Contacts can be updated or deleted as required.

---

## 🛠️ Technologies Used

* Programming Language: **C**
* Concepts:

  * Structures (`struct`)
  * Pointers
  * Dynamic Memory Allocation (`malloc`, `free`)
  * String handling (`strcmp`, `strstr`)

---

## ▶️ How to Run

1. Copy the code into a file named `contact_manager.c`
2. Compile using:

   ```bash
   gcc contact_manager.c -o contact
   ```
3. Run the program:

   ```bash
   ./contact
   ```

---

## 📚 Learning Outcomes

* Practical understanding of linked data structures
* Memory management in C
* Implementation of CRUD operations
* Building menu-driven console applications

---

## 🔮 Future Enhancements

* File handling for permanent data storage
* User authentication (password protection)
* Sorting contacts alphabetically
* GUI-based version of the application

---

## 👨‍💻 Author

Developed as part of a Data Structures / C Programming project.

---

## ⭐ Note

This project is uniquely implemented using a **Doubly Linked List**, making it different from standard array-based solutions.
