# Django Quiz App

This is a Django-based quiz application that allows users to create and take quizzes. The application provides a user-friendly interface and incorporates various features to enhance the quiz-taking experience.

## Features

- User Registration: Users can create an account to access the quiz functionalities.
- Quiz Creation: Registered users can create quizzes by adding questions and options.
- Quiz Taking: Users can select and take quizzes from the available options.
- Result Tracking: The application keeps track of users' quiz results and displays them upon completion.
- Responsive Design: The user interface is designed to be responsive and compatible with different devices.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/rohittelgote23/django-quiz-app.git
   ```

2. Navigate to the project directory:

   ```shell
   cd django-quiz-app
   ```

3. Create and activate a virtual environment:

   ```shell
   virtualenv env
   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate  # For Windows
   ```

4. Install the project dependencies:

   ```shell
   pip install -r requirements.txt
   ```

5. Perform database migrations:

   ```shell
   python manage.py migrate
   ```

6. Start the development server:

   ```shell
   python manage.py runserver
   ```

7. Access the application locally via `http://localhost:8000` in your web browser.

## Usage

1. Register a new account or log in with your existing credentials.
2. Create a quiz by providing a title, questions, and options.
3. Browse the available quizzes and select one to start the quiz.
4. Answer the questions by selecting the appropriate options.
5. Submit the quiz to view your results.

## Acknowledgements

- The project uses the [Django](https://www.djangoproject.com/) web framework.
- Special thanks to the developers and contributors of the dependencies used in this project.
