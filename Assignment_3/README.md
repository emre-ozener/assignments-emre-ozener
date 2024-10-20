# Assignment 3

---
## Python Version == 3.10.15

---
## Question 1. Create a **Course** class, where each course has a name, a description and a list of enrolled students. You'll need to implement the next methods:
    - Add a student to the course.
    - Remove a student from the course.
    - Show all students in the course.

In this question, the course class is created.

The object gets two arguments which are name and course type.

These methods, 
- "add student" , 
- "remove student" 
- and "show_students"
are also added.

Empty list named "self.students" stores the students enrolled to these courses. 

All the methods checks the self.students in order to adjust the output of the code: 
- if the user tries to add a student to a course where the student is already added, the code informs the user.
- if the user tries to remove a student that doesn't exist in the course, the code informs the user.
- if the course doesn't have any student inside, the code informs the user.
---
## Question 2. Create a **Student** class, where each student has a name, ID number, address and a list of enrolled courses with the following methods:
    - Enroll in a course.
    - Drop a course.
    - Show all registered student courses.

In this question, the student class is created. 

The object gets three arguments: name, student_id, address. The address is optional. 

There are three methods available: 
- enroll 
- drop
- show_courses

Empty list named "self.courses" stores the courses that the students are enrolled to. 

With these methods, a student could be created, enroll to a course, drop the course, and list all the courses that the student
is enrolled to. 

- When the user tries to enroll to a course that the student already enrolled the code informs when the enroll method is called.
- When the user tries to drop a class the student doesn't exist, the code informs when the drop method is called
- When the student doesn't have a course, the code informs when the show_courses method is called
---
## Question 3. Create a central class that manages courses and students, **Registration** class, where you have a list of students and a list of courses, and methods:
    - Enroll in a course.
    - Drop a course.
    - Show all the enrolled courses.
    - Show all the students.

Class "Registration" is created.

Two empty lists named self.students and self.courses is created. 

- enroll_student_in_course checks if the student or the course is exist in the both lists. If not, the code adds the student and/or
the course to these lists. This method also calls corresponding methods in the Course and Student Class in order to enroll the 
student and add the student to the course. 
- drop_student_from_course calls the corresponding methods in Student and Course classes in order to drop the course and remove the 
student from the course.

---
## Question 4. Let's add grades to each student's course and create method that yields the GPA given a student name or ID.

The classes are copy pasted. 

Additional dictionary to the Registration class is added where the key is student id and course, and the value is the grade

student_grade method allows to enter a grade to the student for a specific course. 

In order to satisfy the condition of the question which is entering student's either name or id to calculate the gpa, 
this student_id_name_matcher helps to identify the student based on the id or name.

gpa_calculator check if the student exists. If yes, it goes to that student's courses and create key for the dictionary 
with the student_id and the course name and look for the grades. And then takes the average of the grades to calculate the gpa. 


