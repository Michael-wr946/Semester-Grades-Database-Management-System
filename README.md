The aim for the project was mainly focused on the semester results published by my university, where they released the grades and the Semester wise GPA only based on roll numbers. Names were not displayed on the results, making it tough to find the relative performance. I had a pdf containing the names, roll numbers, email, and date of birth of the students, so by using C++, I thought to combine the two pdfs and make a database of students with all their details including their semester GPAs. I couldn't find a C++ library to work with PDFs so I copy-pasted the entire PDFs to two separate ".txt" files. "Names.txt" for the names, roll nos., email, and DOB and "Grades.txt" for the SGPAs and roll no. of the students.
The #include<fstream> header file was used to input data from the two ".txt" files. I created a class called "student" which stored data of each student. A vector of datatype "students", called "Database" was used to store data of all the students. The roll number was used as an index for the vector as it was unique for each student. Eg. for Roll No = "B180001ME", "0001" was taken as the index, which made accessing each student faster and easier.
 #Rest of the readme yet to be added
