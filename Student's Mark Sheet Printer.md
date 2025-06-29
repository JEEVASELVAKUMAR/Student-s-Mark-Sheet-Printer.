📄 Student Mark Sheet Printer using Java OOP
This Java program generates a neat End Semester Mark Sheet for students using Object-Oriented Programming (OOP) principles. It allows users to input student details, their subject marks, and calculates the overall grade based on the average score.

🧠 Concepts Used
Java Classes & Objects

Inheritance

Constructors

Arrays

Conditional Statements (if-else)

Loops (for)

User Input with Scanner

🎯 Objective
To design a simple and interactive Java application that collects student details and subject marks, calculates grades, and prints a professional-looking result sheet similar to what universities generate.

📌 Features
✅ Accepts multiple students’ details
✅ Accepts variable number of subject marks
✅ Calculates average marks
✅ Assigns grade based on standard university grading
✅ Prints personalized result sheets in a formatted structure

📂 Project Structure
bash
Copy
Edit
Student_Mark_Sheet_Printer/
├── Students_Mark_Sheet_Printer_Using_JAVA_OOP.java
└── README.md
🧾 Code Breakdown
🔹 1. Class PERSON
Attributes: First Name, Last Name, ID Number

Constructor: Initializes the attributes

Method: printPERSON() prints the formatted college header and student info

🔹 2. Class STUDENT (inherits from PERSON)
Attributes: An array of test scores

Constructor: Accepts and stores test scores

Method: calculate() computes average marks and returns the grade using conditions

🔹 3. Main Class: Students_Mark_Sheet_Printer_Using_JAVA_OOP
Uses a Scanner to accept user input

Supports multiple student entries

Stores subject marks in an array

Creates a STUDENT object and prints result details

🧮 Grade Criteria
Grade	Meaning
O	Excellent
A	Very Good (Keep Rocking)
B	Good (Keep Trying)
C	Enough (Need More Practice)
D	Poor (Worst Performance)
E	Very Poor (Worst Performance)
F	Fail (Must Study Everyday)

🖥️ Sample Output
text
Copy
Edit
How many mark statements do you want to print : 1
Enter your FIRST NAME : Jeeva
Enter your LAST NAME : S
Enter your ID NUMBER : 101
Enter the NUMBER OF SUBJECTS : 3
Enter your mark that you scored in Subject 1 : 80
Enter your mark that you scored in Subject 2 : 90
Enter your mark that you scored in Subject 3 : 85

=====================================================================================
                              V.S.B. ENGINEERING COLLEGE                              
        (Approved by AICTE, New Delhi and Affiliated to Anna University Chennai)  
            NBA Accredited Courses, NAAC Accredited & ISO Certified Institution       
                          KARUDAYAMPALAYAM PO.KARUR-639 111                           
                      Phone : 99944 96212, 82200 80832, 82705 96212                   
------------------------(PLACE FOR PLACEMENT)-------------------------
                                                                                  
                                 END SEMESTER RESULTS                                 
=====================================================================================
     NAME : S.Jeeva
     IDNUMBER : 101
     GRADE : A
-------------------------------Subject--Wise--Marks----------------------------------
     SUBJECT 1 = 80
     SUBJECT 2 = 90
     SUBJECT 3 = 85
=====================================================================================
     NOTE :    
     O = Excelent.
     A = Very Good(Keep Rocking).
     B = Good(keep trying).
     C = Enough(Need more practice).
     D = Poor(Worst Performance).
     E = Very Poor(Worst Performance). 
     F = Fail(Must Study Everyday).
                    THANKYOU                  
                                                           *********      
                                                    SIGNATURE OF PRINCIPAL
=====================================================================================




🙌 Author
Jeeva S

Java Enthusiast

Learning through project-based development

This project is built for self-practice and understanding of real-world OOP concepts


