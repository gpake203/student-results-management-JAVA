# README for Student Results Management coursework

**Summary**

This was a university project for the Advanced Object Oriented Programming Module. The task was to read in a CSV file of student module results, and print out results for each student depending on their subject taken. Object oriented techniques such as inheritance and encapsulation were used here. Functional and unit testing took place to verify that the code worked as expected.

**Business case**

Students take examinations in educational organisations across the country, and it is important that there are efficient and effective systems to manage this. While this project shows some methods that could be used in administrating, a larger, non-command lined based system would have to be implemented, such as GUI on a web-based application. This would be the most user-friendly approach. A database would also be required as large amounts of data would need to be queried, and it is impractical to read in a text file. The database would need to be regularly updated with new student records. This is more efficient than writing one new line of data into a text file and reading the whole thing again.

**Methodology**

1) Read in text file of students, printing the results as the file is read in.
2) Create Student object to create a student with their first name, surname, year, subject, and grades
3) Create methods for calculating results, classficiations etc.
4) Undertake unit testing comparing the result of each test to a predefined value

**Skills**

Object Oriented Programming, Java, Encapsulation, Inheritance, Design Patterns, File Handling, Unit Testing, Automation

**Results**

12/12 functional tests
5/12 unit tests passed, this is because the 5 passed tests were matching the first result in the file, the other 7 weren't and my program had skipped over these

**Further Improvements**

The code could have been a little more complex and include a greater range of Object Oriented examples.
Unit testing could have been done better as detailed above
