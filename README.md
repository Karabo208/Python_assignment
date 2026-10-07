Section A
Goal for section A is to take the input for one student and validate their grades.
It works by taking the students name ans marks for Maths, English and Science then uses a while loop to make sure that the grades stay between 0 and 100, then calculates the total score and average for that student.

Section B
The goal for section B is to handle multiple students at once and calculates class statistics.
It works but taking the total number of students and uses a loop to collect all their marks, after that it then stores the data as a list of tuples.
Instructions 
When asked to "enter number students" type a number and press enter.
For each each student:
-tpye the student's name
-Enter their grade for math, english and science and it should be between 0-100
-View the generated highest and lowest grade table and the summary table 

Output:
-The highest and lowest grade achieved in each subject across the whole class.
-A summary table showing each student's grades and overall average score.

Section C
The goal is to build a menu so users can manage grades.
It works by converting the list from section B into a nested dictionary so the records can be looked up and modifided easily.
Main menu:
1. Add:Adds a news student ad their grades.
2. Update:Changes existing grades for a student.
3. Remove:Deletes a student from the gardebook.
4. View syubjects:Displays all students grades for one chosen subjects.
5. Search: Finds a students then prints thier full garde reports, and calculates their average.
6. Exit:Stops the menu loop and exits the program.

Instruction
1. Add:Type 1 to add a new student then their name and their marks for all 3 subjects.
2. Update:Type 2 to changes marks for exixting student then ebter the student's name then input new marks.
3. Remove:Type 3 to delete a student, enter their name to removes them from the system.
4. View syubjects:Type 4 to view everyone's score for on subjects,type maths,english,science.
5. Search: Type 5 to view a specific students report card, enter their name to see all their grades and average mark.
6. Exit:Stops the program.
