# CodeAlpha_CGPA_Calculator


This is a simple C++ program to calculate the CGPA (Cumulative Grade Point Average) of a student based on course grades and credit hours.

## 📌 Features

- Takes the number of courses as input
- Allows entry of course name, grade, and credit hours for each course
- Calculates GPA and CGPA using standard formula
- Displays a detailed report of all entered data

## 🧮 Formula Used

> CGPA = (Total Grade Points) / (Total Credit Hours)  
> Where, Grade Points = Grade × Credit Hours (for each course)

## 🛠 How to Compile and Run

1. **Compile the code** using a C++ compiler (e.g., `g++`):
   ```bash
   g++ main.cpp -o cgpa_calculator
   Run the executable:

2. **Run the executable:**
./cgpa_calculator   # Linux/Mac
cgpa_calculator.exe # Windows

**📥 Sample Input**

Enter number of courses: 3

Enter name of course 1: Math
Enter grade for Math: 9
Enter credit hours for Math: 4

Enter name of course 2: Physics
Enter grade for Physics: 8
Enter credit hours for Physics: 3

Enter name of course 3: Chemistry
Enter grade for Chemistry: 7.5
Enter credit hours for Chemistry: 3

**📤 Sample Output**

--- Course Report ---
Course              Grade     Credit    
Math                9         4         
Physics             8         3         
Chemistry           7.5       3         

Final CGPA: 8.15
