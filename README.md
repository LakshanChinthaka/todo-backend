# To-Do List Application (Backend)

## Description

This is a simple web application built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to create, read, update, and delete (CRUD) tasks. The application includes user authentication using JWT, task management features, and a responsive user interface.

## Features

- **User Authentication**: Register and login functionality with JWT for secure authentication.
- **Task Management**: Add, view, update, and delete tasks.
- **Grouping and Filtering**: Tasks are grouped by due date, and overdue tasks are displayed separately.
- **Responsive UI**: A user-friendly and responsive interface built with React and styled using Tailwind CSS or styled-components.
- **Deployment**: The application can be deployed on platforms such as Heroku or Vercel.

## Technologies Used

- **Frontend**: React, Tailwind CSS (or styled-components)
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Development Tools**: Nodemon, Axios, bcryptjs, dotenv

## Installation

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your machine.
- MongoDB server running locally or a MongoDB Atlas account.

### Setup

1. **Clone the repository**:

    ```sh
    git clone https://github.com/yourusername/todo-backend.git
    ```

2. **Navigate to the project directory**:

    ```sh
    cd todo-backend
    ```

3. **Install dependencies**:

    ```sh
    npm install
    ```

4. **Create a `.env` file in the root directory** and add the following environment variables:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET_KEY=your_jwt_secret_key
    ```

5. **Run the server**:

    For development:

    ```sh
    npm run dev
    ```

    For production:

    ```sh
    npm start
    ```

## API Endpoints

### Authentication

- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Login an existing user.

### Tasks

- **GET /api/tasks**: Retrieve all tasks for the authenticated user.
- **POST /api/tasks**: Add a new task.
- **PUT /api/tasks/:id**: Update an existing task by ID.
- **DELETE /api/tasks/:id**: Delete a task by ID.
- **GET /api/tasks/filter**: filter date by compltete and incomplete.

## Frontend

## To-Do List Application (Frontend)
   <a href="https://github.com/LakshanChinthaka/todo-frontend.git">To-Do List Application (Frontend)</a> 

## Deployment

To deploy the application, you can use platforms like Heroku or Vercel. Follow their respective documentation to set up deployment pipelines for both the backend and frontend.

## Contributing

Feel free to open issues or submit pull requests. Contributions are welcome!


## Acknowledgements

- Inspired by modern web application practices.
- Using MERN stack to demonstrate full-stack development.

---

Feel free to adjust any sections to better fit your project's needs or to include additional details about your setup or features.
