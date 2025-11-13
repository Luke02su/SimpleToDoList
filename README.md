# 📝 Simple ToDo List App

[![Kotlin](https://img.shields.io/badge/Linguagem-Kotlin-orange?logo=kotlin)](https://kotlinlang.org/)  
[![Android Studio](https://img.shields.io/badge/IDE-Android_Studio-brightgreen?logo=android-studio)](https://developer.android.com/studio)  
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)  

---

A minimalist **ToDo List** application built with **Kotlin** and **Jetpack Compose**, designed for simplicity, clarity, and persistence.  
It allows users to **add, edit, mark, and remove** tasks — and all data is **saved locally** using `SharedPreferences`, so nothing is lost when the app closes.

## 🚀 Features

- ✅ Add new tasks with **title** and **description**, and **Toast** for signage when fields be empty
- ✏️ Edit task details in a dedicated screen
- ☑️ Mark tasks as completed
- 🗑️ Delete tasks easily
- 💾 Automatic **data persistence** (keeps tasks after closing the app)
- 🧭 Simple navigation between list and detail screens using **Navigation Compose**

--- 


## 📱 Print of Screen

<p align="center">
   <img width="300" height="600" alt="Tela 1" src="https://github.com/user-attachments/assets/9e10e2b2-3732-4b53-8294-7be8cba353bd" />
    <img width="300" height="600" alt="Tela 2" src="https://github.com/user-attachments/assets/5c8595df-6f2a-4252-a798-83876c60e453" />
   <img width="300" height="600" alt="Tela 3" src="https://github.com/user-attachments/assets/78dddeea-fe81-4854-a1d5-b65a5b74c8ed" />
</p>

---

## 🧱 Tech Stack

- **Language:** Kotlin  
- **UI Framework:** Jetpack Compose  
- **State Management:** `remember` + `mutableStateOf`  
- **Local Storage:** SharedPreferences (JSON serialization)  
- **Navigation:** Navigation Compose

---

## 📱 How It Works

1. Type a **title** and an optional **description** for your task.  
2. Tap **+ Add** to include it in the decreasing list.  
3. Tap the edit icon ✏️​ to modify it.
4. Tap the trash icon 🗑️ to remove it.  
5. Check the box to mark a task as completed.  

All your tasks are automatically **saved** and **restored** when you reopen the app.

---

## 💡 Future Improvements

- Add draggable for move tasks in vertical orientation
- Add a progress indicator (e.g., “3 of 10 tasks done”)  
- Add search or filter for completed tasks  
- Switch to **Room Database** for more advanced persistence  
- Add cloud sync (e.g., Firebase integration)

---

## 🧑‍💻 Author

**Lucas Samuel Dias**  
Developed for learning and demonstration purposes with a focus on simplicity and usability.

---

## 🪪 License

This project is open source and available under the **MIT License**.
