Student Grade Management System
Overview
This project is a Python-based application designed to help manage and track student grades efficiently. The system allows users to input grades for different subjects or assignments, automatically calculate the average grade, and display the overall GPA and corresponding letter grade. It’s a simple yet effective tool for educators, students, or developers looking to manage academic performance data.

Key Technologies
Python: The entire application is built using Python, leveraging its simplicity and versatility for handling data and performing calculations.
Object-Oriented Programming (OOP): The project is structured around a Student class, demonstrating OOP principles such as encapsulation and modularity.
Features
Add Grades: Easily add grades for different subjects or assignments.
Calculate Average: Automatically calculate the average grade across all subjects.
GPA Calculation: Convert the average grade into a GPA and corresponding letter grade based on a standard scale.
Display Grades: View all entered grades along with the calculated average, GPA, and letter grade.
Description
The Student Grade Management System is a simple, user-friendly application designed to manage student grades. It allows users to input grades for various subjects and assignments, and then automatically calculates the average grade, GPA, and letter grade based on a predefined scale.

How It Works:
Initialization: A Student object is created with a name.
Adding Grades: Grades are added to specific subjects using the add_grade method.
Calculations:
The calculate_average method computes the average grade across all subjects.
The calculate_gpa method converts the average grade into a GPA and letter grade.
Display: The display_grades method presents all the grades, the average, GPA, and the corresponding letter grade.
Example Usage:
python
Copy code
# Create a Student object
student = Student("ABHISHEK CHATTERJEE")

# Add grades
student.add_grade("Math", 85)
student.add_grade("English", 92)
student.add_grade("Science", 78)

# Display the student's grades and GPA
student.display_grades()
Output:
yaml
Copy code
Grades for ABHISHEK CHATTERJEE:
Math: [85]
English: [92]
Science: [78]
Average Grade: 85.00
GPA: 3.00 (B)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/student-grade-management.git
Navigate to the directory:
bash
Copy code
cd student-grade-management
Run the script:
bash
Copy code
python student_grade_management.py
Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the functionality, add new features, or enhance the documentation.
