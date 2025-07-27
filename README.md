Timetable Generation System
Project Description
The project, Timetable Generation System (TTGS), is a web application developed using the Django Framework and an SQLite database.

The project makes use of a genetic algorithm to satisfy the soft and hard constraints and generate the most optimal timetable. The web application includes a simple authentication-authorization module, and on successfull authentication the user is redirected to the admin dashboard.

On the admin dashboard the user can input the data of the college/university which is required to generate the timetable. The user must add the following details:

Teachers
Classrooms
Timings
Courses
Departments
Sections
Upon successfull entry of the data into sqlite database, the user can navigate to the "Generate Timetable" page to start the process of generating the timetable. Upon successfull generation of the timetable the user can download the timetable as a PDF.

Technologies Used:

HTML5
CSS3
Python 3.8
Django 3.0.*
JavaScript
sqlite3
How to run the Project?
Clone the Repository
Access the project files by using an IDE (PyCharm or Spyder) or via the command line
Enter the directory of the main project via the command line or the terminal on the IDE
Run the command "python manage.py runserver"
Open your browser and access localhost at port http://127.0.0.1:8000/
