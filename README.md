# 📚 QuesGen & Library Management System

A **C++-based integrated application** combining a **Question Paper Generator** and a **Library Management System**.  
Built with **Object-Oriented Programming (OOP)** principles, the project uses **file handling** for data storage, interactive **graphics-based menus** (BGI), and supports persistent records for books, users, and question banks.

---

## 🚀 Features

### **1. Question Paper Generator**
- Generates **objective** and **subjective** question papers.
- Supports **class-based** and **marks-based** filtering.
- Stores questions in **binary files** (`mastero.dat`, `masters.dat`).
- Ensures **no duplication** of questions in a paper.
- Displays generated paper with **time allowed** and **maximum marks**.

### **2. Library Management System**
- Categorized books:
  - Biographies
  - Autobiographies
  - Fiction
  - Academics
  - Children’s Books
- Issue, explore, and review books.
- Built-in **book review database** for quick summaries.
- Secure **username/password-based login**.

---

## 🛠️ Implementation Details

- **Language:** C++
- **Paradigm:** Object-Oriented Programming
- **Libraries Used:**
  - `<fstream.h>` for file handling
  - `<graphics.h>` for graphical interface (BGI)
  - `<conio.h>` for console handling
- **Key Classes & Structures:**
  - `question` – handles question storage, input, validation.
  - Multiple `struct` types for book categories and reviews.
  - Library menu & review functions (`choice1`, `choice2`, `choice3`).

---

## 📂 File Structure
QuesGen
|-- Codes
|     |-- main.cpp # Question Paper Generator
|     |-- lib_management.h # Libraray Management System header
|     |-- run.cpp # Integrated application runner
|
|-- Question_Bank
      |-- O.cpp
      |--S.cpp
      |--obj.txt
      |--subj.txt

---

## ⚙️ How to Run

1. Install a C++ compiler supporting old Turbo C++ style code (BGI graphics).
2. Ensure BGI graphics files are available (e.g., `bgi` folder).
3. Compile and run `run.cpp` to access the **integrated menu**.
4. Or compile `main.cpp` to run the question paper generator separately.

---

## 🔮 Future Improvements
- Replace BGI graphics with modern GUI (e.g., SFML, Qt).
- Replace `.dat` binary files with a database (MySQL / SQLite).
- Add export to **PDF** for generated question papers.
- Modernize code for standard C++ compilers.

---

## 📜 License
This project is open-source. You may fork, modify, and distribute it.

