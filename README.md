# Library Management System

## 📌 Introduction
This is a simple **Library Management System** built in Python. It allows users to:
- **Add books** to the library
- **Remove books** from the library
- **View available books**
- **Save the library data** in a `library.txt` file using **JSON format**
- **Load previously saved data** when the program starts

## 🛠️ Technologies Used
- **Python 3**
- **JSON for data storage**

## 🚀 Features
- **Persistent Storage:** Saves book records in `library.txt` so that data is not lost when the program restarts.
- **User-Friendly Interface:** Uses simple text-based input.
- **Error Handling:** Prevents crashes due to missing files or incorrect JSON formatting.

## 📂 Project Structure
```
📦 Library Management System
 ┣ 📜 library.txt  # Stores book data in JSON format
 ┣ 📜 main.py      # Main program file
 ┗ 📜 README.md    # Project documentation
```

## 📌 How It Works
### **1️⃣ Loading the Library Data**
- The function `load_library()` reads the `library.txt` file.
- If the file exists and contains valid JSON, it loads the data into the `library` list.
- If the file does not exist or is empty, an empty list is used.

### **2️⃣ Saving the Library Data**
- The function `save_library()` writes the `library` list to `library.txt` in JSON format.
- It ensures that the data remains available for future sessions.

### **3️⃣ Adding a Book**
- Users can enter book details (title, author, etc.), which are stored in the `library` list.
- The list is then saved using `save_library()`.

### **4️⃣ Removing a Book**
- Users can remove a book by specifying its name.
- The book is deleted from the `library` list, and changes are saved.

### **5️⃣ Viewing Available Books**
- The function `view_books()` displays all stored books from `library.txt`.

## ▶️ How to Run the Program
1. Install **Python 3** (if not already installed).
2. Clone this repository:
   ```sh
   git clone https://github.com/your-username/library-management.git
   ```
3. Navigate to the project folder:
   ```sh
   cd library-management
   ```
4. Run the program:
   ```sh
   python main.py
   ```

---
🔥 **Developed by [Mueza Ejaz]** 🔥


