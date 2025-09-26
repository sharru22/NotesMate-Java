
# NotesMate - Java 
File I/O Notes Manager

**NotesMate** is a simple yet powerful **text-based Notes Manager** built using Java.  
It allows users to create and manage notes directly from the terminal, while demonstrating how to use **File I/O** and handle **exceptions** effectively in Java.  
This project was developed as part of a **Java Developer Internship task** to strengthen practical Java skills.

---

## 🚀 Features
- ✍️ Add new notes (saved using `FileWriter` in append mode)  
- 📖 View all saved notes (read using `BufferedReader`)  
- 🗂 Auto-creates the notes file if it does not exist  
- ⚡ Implements `try-with-resources` for safe resource handling  
- 🛡 Handles file-related errors with proper exception management  

## 🛠 Tech Stack
- **Java (Core)**  
- **VS Code / IntelliJ / Terminal**  
- **Git & GitHub** for version control  

## 📂 Project Structure
NotesMate-Java/
│── NotesApp.java # Main Java program
│── notes.txt # File storing all notes (auto-created on runtime)
│── README.md # Project documentation

📌 Key Learning Outcomes
Difference between FileReader and BufferedReader
Using try-with-resources for automatic closing of streams
Handling checked and unchecked exceptions
Understanding append vs overwrite mode in FileWriter
Gaining practical experience in Java File I/O

📷 Demo (Sample Run)
===== NotesMate =====
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Complete Java File I/O Task
✅ Note added successfully!

===== NotesMate =====
1. Add Note
2. View Notes
3. Exit
Enter your choice: 2
📒 Your Notes:
- Complete Java File I/O Task

  ~Thankyou for checking out!
