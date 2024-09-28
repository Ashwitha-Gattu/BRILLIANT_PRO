# BRILLIANT_PRO
CSV Processing Script:
  
  Read CSV File: Load student records from a CSV file containing name, age, and grade.
  Calculate Average Grade: Compute the average grade of all students.
  Identify Highest Grade: Print the name and grade of the student with the highest grade.

Flask Web Application:
    
    Home Page: A welcome page that greets users.
    Registration Page: Users can create an account.
    Login Page: Users can log in to access the application.
    Form Page: Users submit their name, age, and bio.
    Display Page: Shows submitted user data from the database.
    API Endpoint: Returns a JSON response with all user data.
    Error Handling: Manages invalid form inputs.

HTML Templates:
     
     home.html: Displays welcome message and links to login/register.
     login.html: Form for user login.
     register.html: Form for user registration.
     display.html: Lists submitted student records.

Database Integration:
  
   Database Setup
      Use SQLite for simplicity.
      Define models in models.py to represent users and student data.
      Use Flask-SQLAlchemy to manage database interactions.
  
  User Authentication
      
      Implement registration and login routes to manage user accounts.
      Use password hashing for security.

This project showcases how to handle CSV data processing alongside creating a web application using Flask. The application allows for user registration and authentication, storing and retrieving student records from a database, and serves as a foundational platform for further development. You can enhance it with additional features such as editing records, user roles, and more complex API endpoints.

Run the application:
 
  python app.py
