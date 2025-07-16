# 🎓 Student Grade Management System 🚀

## Overview

This Python-based application provides a robust and user-friendly system for managing student grades. Designed for educational institutions, it offers various functionalities for different user roles including teachers, homeroom teachers, and the principal. The system allows for viewing, adding, editing, and deleting student data and their respective subject scores, as well as generating class rankings.

## Key Features ✨

  * **Secure Login System:** Differentiated access based on user roles (Teacher, Homeroom Teacher, Principal) with unique NIPs (Employee ID Numbers) and passwords.
  * **Comprehensive Student Data:** Stores student names, classes, and scores across five core subjects: Mathematics, Science (IPA), Social Studies (IPS), Indonesian Language, and English Language.
  * **Complete Grade Management:**
      * View all student data.
      * View students by specific class.
      * Add new student records with their initial grades.
      * Edit existing student's grades for any subject.
      * Delete student records from the system.
  * **Quick Class Ranking:** Generate and display the top 3 students in a specific class based on their average scores across all subjects.
  * **Intuitive Interface:** A simple, menu-driven command-line interface for ease of navigation.

## Getting Started 🚀

### Prerequisites

  * Python 3.x installed on your system.

### Installation

1.  **Download the file:** Save the provided `FINALCAPSTONE.py` file to your local machine.

### Running the Application

1.  Open your terminal or command prompt.
2.  Navigate to the directory where you saved `FINALCAPSTONE.py`.
3.  Run the application using the Python interpreter:
    ```bash
    python FINALCAPSTONE.py
    ```
4.  Follow the on-screen prompts for login and menu navigation.

## User Roles and Credentials 🔑

The application supports various user roles, each with specific NIPs (Nomor Induk Pegawai/Employee ID Number) and passwords:

| NIP  | Role            | Name         | Subject/Class     | Password         |
| :--- | :-------------- | :----------- | :---------------- | :--------------- |
| G001 | Teacher         | Bu Ana       | Matematika        | `matematika123`  |
| G002 | Teacher         | Bu Suratni   | IPS               | `ips123`         |
| G003 | Teacher         | Pak Budi     | IPA               | `ipa123`         |
| G004 | Teacher         | Pak Sastra   | Bahasa Indonesia  | `Bindo123`       |
| G005 | Teacher         | Miss Jolie   | Bahasa Inggris    | `Bing123`        |
| W010 | Homeroom Teacher| Pak Fajar    | Class 10          | `wali10`         |
| W011 | Homeroom Teacher| Bu Mar       | Class 11          | `wali11`         |
| W012 | Homeroom Teacher| Pak Shubuh   | Class 12          | `wali12`         |
| K001 | Principal       | Dr. Indra    | N/A               | `kepsek123`      |

## How to Use 👩‍🏫👨‍🎓

1.  **Login:** Enter your NIP and password. If successful, you will be directed to the main menu.
2.  **Main Menu:**
      * `1. Tampilkan Semua Siswa` 📚: View all students and their grades.
      * `2. Tampilkan per Kelas` 🏫: View students and grades filtered by class (10, 11, or 12).
      * `3. Tambah Data Siswa` ➕: Add a new student record by providing their name, class, and scores for all five subjects.
      * `4. Edit Data Siswa` ✏️: Update a student's grades. You can leave a field blank if you don't wish to change that specific grade.
      * `5. Hapus Data Siswa` 🗑️: Remove a student record from the system.
      * `6. Ranking Kelas` 🏆: See the top 3 students in a specified class based on their average scores.
      * `0. Keluar` 🚪: Exit the application.

## Code Structure 🏗️

  * `users`: A dictionary storing user credentials and roles.
  * `students`: A list of dictionaries, where each dictionary represents a student with their name, class, and subject scores.
  * `determine_status(nilai)`: A helper function to determine "Lulus" (Pass) or "Tidak Lulus" (Fail) based on a score. (Note: This function is defined but not explicitly used in the main menu flow for displaying status, but could be integrated).
  * `login()`: Handles user authentication.
  * `main_menu()`: Displays the main application menu and handles user choices.
  * `show_all_students()`: Prints a formatted table of all student data.
  * `show_by_class()`: Filters and prints student data for a specified class.
  * `add_student()`: Prompts for new student details and adds them to the `students` list.
  * `edit_student()`: Allows updating grades for an existing student.
  * `delete_student()`: Removes a student record.
  * `show_ranking()`: Calculates and displays the top 3 students by average score for a given class.

-----
