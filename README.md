# Examination System (Mini Project)

This is a C# console-based Examination System implemented as a mini project.  
It demonstrates OOP principles such as inheritance, polymorphism, events & delegates, file logging, and LINQ.  

## Features
- Question base class with multiple types:
  - True/False
  - Choose One
  - Choose All
- QuestionList class with logging (each exam logs its questions to a file).
- Answer and AnswerList classes for handling student answers.
- Exam base class with:
  - Duration
  - Number of Questions
  - Question-Answer dictionary
  - Exam Modes (Starting, Queued, Finished)
- Events & Delegates:
  - Students get notified when an exam starts.
- Two Exam Types:
  - Practice Exam (shows correct answers after each question)
  - Final Exam (only shows questions).
- Implements ICloneable, IComparable, ToString, Equals, GetHashCode.
- Uses LINQ for filtering/searching.

## Project Structure
ExaminationSystem/
│── Program.cs
│── Enums/
│ └── ExamEnums.cs
│── Models/
│ ├── Question.cs
│ ├── TrueOrFalseQuestion.cs
│ ├── ChooseOneQuestion.cs
│ ├── ChooseAllQuestion.cs
│ ├── Answer.cs
│ ├── AnswerList.cs
│ ├── QuestionList.cs
│ ├── Subject.cs
│ └── Student.cs
│── Events/
│ └── ExamStatusChangedEventArgs.cs
│── Exams/
│ ├── Exam.cs
│ ├── PracticeExam.cs
│ └── FinalExam.cs

bash
نسخ الكود

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ExaminationSystem.git
Open the project in Visual Studio (or Rider).

Build and Run:

bash
نسخ الكود
dotnet run
Follow the console menu to:

Take a Practice Exam

Take a Final Exam

Change Exam Status (see notifications)

Sample Output
markdown
نسخ الكود
🎓 Welcome to the Examination System
=====================================

📋 Available Exams:
1. Practice Exam - Advanced Mathematics
2. Final Exam - Computer Science
3. Change Exam Status (Demonstration)
4. Exit
Requirements
.NET 5 SDK

C# 9.0 or later

Author
Ahmed Ashraf Mosad
Faculty of Computers and Informatics, Zagazig University# ExaminationSystemCSharp
