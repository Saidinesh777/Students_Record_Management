# Students_record_Management

Libraries Used:

1. **iostream**: This library is used for input/output operations in C++.
2. **cstdlib**: This library provides functions for general purpose utilities, including the exit() function used to terminate the program.

  Code Explanation:

1. The code begins with the inclusion of the necessary libraries.

2. The student struct is defined, representing a student's details. It contains members for the first name, last name, roll number, and CGPA.

3. The students array is declared to store student records, and number_of_students is initialized to 0 to keep track of the number of students in the array.

The code defines several functions:

1. **addStudentDetails()** : Prompts the user to enter details for a new student and adds them to the students array if the roll number is unique.
2. **findStudentByRollNumber()**: Prompts the user to enter a roll number and searches for a student with that roll number in the students array, displaying their details if found.
3. **findStudentByFirstName()**: Prompts the user to enter a first name and searches for students with that first name in the students array, displaying their details if found.
4. **findTotalStudents()**: Displays the total number of students stored in the students array.
5. **deleteStudentByRollNumber()**: Prompts the user to enter a roll number and deletes the corresponding student record from the students array if found.
6. **updateStudentDetails()**: Prompts the user to enter a roll number and offers options to update various details (first name, last name, roll number, or CGPA) of the student with that roll number.
7. In the **main() function**, a while loop is used to repeatedly display a menu of options and perform the selected operation until the user chooses to exit.

8. Inside the loop, the user's choice is obtained, and a switch statement is used to call the appropriate function based on the choice.

9. The program includes proper input validation to handle incorrect user inputs, such as selecting an invalid option or entering non-numeric data where expected.

10. If the user chooses option 7 (Exit), the exit(0) function is called to terminate the program.

Overall, the code allows users to interactively manage a student database by adding, searching, updating, and deleting student records based on roll number and first name.
