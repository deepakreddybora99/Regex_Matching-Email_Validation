# Regex_Matching-Email_Validation web development 


**Objective:** The task is to replicate the core functionality of the website regex101.com. This entails creating a web application that allows users to input a test string and a regular expression (regex) and displays all the matches found.

Steps:

1. Create a new directory for the project and navigate into it.

2. Set up your virtual development environment:

3. Install Flask, a Python web framework, using pip if not already installed: pip install Flask.

   
## Initialize a new Flask application:

4. Create a new Python file named app.py.
    Import Flask and create a new Flask app instance.
    Define a route for the home page ("/") where users can input the test string and regex.
    Render an HTML template containing a form with fields for the test string and regex, and a submit button.
5. Create the HTML template:
      Create a new directory named templates within your project directory.
      Inside the templates directory, create a new HTML file named home.html.
      Design the HTML form with input fields for the test string and regex, and a submit button.
   
6.  Define a route to handle form submission:
      The home route ("/") in the app.py file will also handle form submission.
      It extracts the test string and regex submitted by the user from the form data.
      Use Python's re module to perform regex matching on the test string.
      Store the matched strings in a list.
6.  Render the results:
     Pass the list of matched strings to the HTML template.
     Modify the HTML template to display the matched strings below the input form.

    
8.  Test the application:

     Run the Flask application (python app.py).
     Open a web browser and navigate to http://localhost:5000 to access the application.
     Input various test strings and regex patterns to ensure the application displays the correct matches.

    
   (BONUS) Implement a new route where a user can validate if a given email id is valid or not.

(IMPORTANT) Deploy the application on AWS Cloud. LINK :http://35.173.183.234:5000
