# Deck Task: Simple Task Management App
This task management app is a full-stack application built using the MERN stack (MongoDB, Express.js, React, and Node.js) and Vite as the front-end build tool.
It allows users to create, read, update, and delete tasks efficiently. This application aims to help individuals and teams organize their with ease.

## Features
- User Authentication (Sign up, Sign in, Sign out)
- Create tasks with titles, descriptions, priorities, and deadlines
- View all tasks in an organized dashboard
- Update task details
- Delete tasks
- Responsive design for desktop and mobile devices

## Prerequisites
Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- MongoDB (local setup or MongoDB Atlas)
- Yarn or npm installed

## Installation
```
git clone https://github.com/yourusername/task-management-app.git
cd decktask
```

## Setting up the Backend
Navigate to the backend directory and install dependencies:

```
cd backend
npm install

```

Create a .env file in the backend directory and add the following:
- PORT = 4000
- MONGO_URL = your_mongodb_uri
- ATS=your_accesstoken_secret
- ATE=1h(you can modify):your_accesstoken_expiration_date
- RTS=your_refresh_token_secret
- RTE=7d(you can modify):your_refreshtoken_expiration_date

Set up a cloudinary account and add the following
- CLOUDINARY_API_KEY = =you_cloudinary_api_key
- CLOUDINARY_API_SECRET = your_cloudinary_api_secret
- CLOUDINARY_NAME = dbtjysxp1 = your_cloudinary_name

Start the backend server:
```
npm run dev
```

## Setting up the Frontend
Open a new terminal window, navigate to the frontend directory, and install dependencies:

```
cd frontend
npm install

```

Start the Vite development server:

```
npm run dev

```
The application should now be running and accessible at http://localhost:5173.
Ensure it is running at this port to avoid cors issues. You can always check index.js in the backend to modify origins.

## Usage
After logging in or signing up, you can start by creating a new task using the "Add Task" button. 
Each task requires a title and a deadline is attached to any task.
Use the dashboard to view, edit, or delete your tasks.

## Contributing
Contributions to the Task Management App are welcome. To contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature/AmazingFeature).
- Make your changes and commit them (git commit -m 'Add some AmazingFeature').
- Push to the branch (git push origin feature/AmazingFeature).
- Open a pull request.

## Credits
   - [pesto](https://www.pesto.tech)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
Your Name - @isaacprogi

Project Link: https://github.com/Isaacprogi/decktask.git
