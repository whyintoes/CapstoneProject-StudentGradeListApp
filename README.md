
# 🎓 FINAL CAPSTONE PROJECT – Student Grade ListApp

This project is a simple yet functional **Student Grades Management Application**, built with Python and designed for **data input, processing, and summary of student grades**. The application allows users to add, view, and analyze student scores across multiple subjects. It also includes file-saving functionality for future reference.

## 📌 Features

- Input student data interactively via CLI.
- Support for three subjects: **Bahasa Indonesia**, **Mathematics**, and **English**.
- Score validation and conversion to grade categories (A, B, C, D, E).
- Identify subjects the student passed or failed.
- Option to save data into a CSV file.
- Clear, user-friendly prompts and outputs.

## 🧠 How It Works

The app follows this flow:

1. Prompt user for student name.
2. Input and validate scores for three subjects.
3. Automatically convert scores to grades.
4. Determine passed/failed subjects based on grade thresholds.
5. Display student performance summary.
6. Ask if user wants to enter another student.
7. Ask if data should be saved to a `.csv` file.

## 🗂️ File Structure

```text
FINALCAPSTONE.py    # Main Python script containing the CLI-based application logic
```

## 🔧 Requirements

This application is built using standard Python libraries and does not require external dependencies.

- Python 3.x
- Built-in modules: `csv`

## ▶️ How to Run

1. Ensure Python is installed (`python --version`)
2. Open terminal or command prompt.
3. Navigate to the folder containing `FINALCAPSTONE.py`.
4. Run the script:

```bash
python FINALCAPSTONE.py
```

## 📋 Output Example

```
=== STUDENT GRADE SYSTEM ===
Enter student name: John Doe

Enter score for Bahasa Indonesia: 80
Enter score for Mathematics: 70
Enter score for English: 50

Student Name: John Doe
Grades:
- Bahasa Indonesia: B
- Mathematics: B
- English: D

Passed Subjects: Bahasa Indonesia, Mathematics
Failed Subjects: English
```

## 💾 Saving to CSV

After data entry, the app gives the option to **save the student record** to a CSV file (`student_grades.csv`). If the file doesn't exist, it will be created. Otherwise, new data will be appended.

## 🎯 Grading System

| Score Range | Grade | Status     |
|-------------|-------|------------|
| 85 - 100    | A     | Pass       |
| 70 - 84     | B     | Pass       |
| 60 - 69     | C     | Pass       |
| 50 - 59     | D     | Fail       |
| 0 - 49      | E     | Fail       |

## 🛠 Future Improvements

- GUI version (e.g. using Tkinter or PyQt)
- Web version with uploadable CSVs (e.g. Streamlit or Flask)
- Database integration (e.g. SQLite or PostgreSQL)
- Summary statistics for all students

## 👨‍💻 Author

This project was developed as part of a **Final Capstone** in a Python learning journey.

If you'd like help extending this into a full web or GUI application, feel free to reach out!
