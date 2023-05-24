# Quiz App

The Quiz App is a web application built with Laravel and Bootstrap that allows users to play quizzes by answering multiple-choice questions. The app provides an admin panel where the administrator can add questions and options for the quizzes.

## Features

-   User registration and authentication
-   Admin panel for managing quizzes
-   Multiple-choice questions with 4 options each
-   Bootstrap-based UI for a visually appealing design
-   Score tracking

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/rahuldahal/quiz-app.git
    ```

2. Navigate into the project directory:

    ```bash
    cd quiz-app
    ```

3. Install the project dependencies using Composer:

    ```bash
    composer install
    ```

4. Create a copy of the `.env.example` file and rename it to `.env`. Update the necessary environment variables such as database configuration.

5. Generate a unique application key:

    ```bash
    php artisan key:generate
    ```

6. Run the database migrations:

    ```bash
    php artisan migrate
    ```

7. Optionally, seed the database with some initial data:

    ```bash
    php artisan db:seed
    ```

8. Install the Node.js dependencies and compile the assets:

    ```bash
    npm install && npm run dev
    ```

9. Start the development server:

    ```bash
    php artisan serve
    ```

10. Access the app in your web browser by visiting `http://localhost:8000`.

## Usage

1. Register a new user account or log in with an existing account.
2. As an admin, log in and access the admin panel.
3. In the admin panel, you can add new questions and their corresponding options for the quizzes.
4. Once the questions are added, users can play the quizzes by selecting the correct option for each question.
5. After completing the quiz, the user's score is calculated and displayed.
6. Admin can view scores of all the users.

## Technologies Used

-   Laravel - PHP web framework
-   Bootstrap - CSS framework for responsive design
-   MySQL - Database management system
-   Composer - Dependency manager for PHP
-   Node.js - JavaScript runtime for asset compilation
-   NPM - Package manager for Node.js

## Contributing

Contributions to the Quiz App are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.

## License

The Quiz App is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
