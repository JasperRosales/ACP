# Expense Wise

------Description----------
Expense Wise is a financial management application designed specifically for students to track and manage their expenses effectively. The app allows users to categorize their spending, set personalized budgets, and visualize financial data through an intuitive and user-friendly dashboard. With its tailored features, Expense Wise empowers students to maintain financial discipline, stay within their budget, and make informed decisions about their spending habits.

The application is particularly beneficial for student organizations like the Student Supreme Council (SSC). SC members can oversee transactions, allocate budgets, and ensure transparency and accountability in financial operations. This makes the app not just a personal finance tracker, but also a valuable tool for organizational budget management.


Users can register using their email  and securely log in to their accounts. The project can displays graphs and tables with real-time transaction updates. Allows users to add, edit, and delete transactions.


----Download requirements-------
pip install -r requirements.txt


----Use of Libraries-------
The Flask framework is the backbone of the Expense Wise application, serving as a lightweight web framework to manage backend operations such as handling user routes (e.g., /signup, /login, /register), processing HTTP requests, and rendering dynamic HTML templates. It is chosen for its simplicity, scalability, and suitability for student-level projects while remaining flexible for future enhancements.

The application uses Flask-MySQLdb to establish a seamless connection between Flask and the MySQL database. This library allows the application to execute SQL queries for storing, retrieving, and updating data, such as user credentials, expense records, and budget information, ensuring a reliable database integration.

To create dynamic and interactive web pages, the application leverages Jinja2, a powerful templating engine built into Flask. Jinja2 allows the embedding of Python variables and logic into HTML templates, enabling features like displaying success or error messages and rendering user-specific data on the dashboard.
 
----Steps to follow------

To use the Expense Wise app, start by setting up and installing the necessary components. Clone the project repository from GitHub or download the source code as a ZIP file. Ensure Python (version 3.8 or above) is installed on your system, and install the required dependencies by running the command pip install -r requirements.txt. Set up a MySQL database named exp, and create the necessary tables using the provided SQL schema file (schema.sql). Update the file to match your MySQL credentials.

Once the setup is complete, navigate to the project directory in your terminal and run the Flask application using the flask run command. Open your browser and visit http://127.0.0.1:5000 to access the application.

To sign up, go to the Sign-Up page by clicking the "Sign-Up" button on the homepage or visiting /signup. Fill out the form with your username, school email (in the format 20-12345@g.batstate-u.edu.ph), and password, then click "Create Account." If you already have an account, navigate to the Login page at /login, enter your credentials, and log in.

Once logged in, you can use the dashboard to track, categorize, and manage your expenses. You can also set budgets for different categories and receive alerts when nearing your limits. The app allows you to view visual spending trends through charts and graphs to analyze your financial habits.



