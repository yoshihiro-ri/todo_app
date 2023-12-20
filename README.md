# Todo Application with React and Flask

This is a Todo application built with React for the frontend and Flask for the backend. The application includes user authentication features and basic database operations.

## Installation

To install and run the application, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/yoshihiro-ri/todo_app.git
   ```

   ```bash
   cd todo_app
   ```

2. Clone other repository (backend&frontend):

   ```bash
   git clone https://github.com/yoshihiro-ri/todo_app_back.git
   ```

   ```bash
   git clone https://github.com/yoshihiro-ri/todo_app_front.git
   ```

3. Build the Docker images:

   ```bash
   docker-compose build
   ```

4. Start the application:

   ```bash
   docker-compose up
   ```

5. Access the application in your web browser at [http://localhost:3000/SignUp](http://localhost:3000/SignUp).

## Usage

1. Create your account by visiting [http://localhost:3000/SignUp](http://localhost:3000/SignUp).
2. Log in using your credentials at [http://localhost:3000/Login](http://localhost:3000/Login).
3. Start using the Todo application.
