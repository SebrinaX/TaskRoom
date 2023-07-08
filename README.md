### Task Room - Personal Kanban Board Project
## Task Room is a web-based application that serves as a personal Kanban board. It provides a visual representation of your tasks, allowing you to organize and track your work effectively.

## Features
- User Registration and Authentication: Users can create an account and log in to access their personalized Kanban boards.
Task Management: Create, update, delete, and track tasks across different stages of your workflow.
- User Roles: Guest users can view the Kanban board, team members can view and comment on tasks, and admins have full control over the board and its settings.
- Real-time Updates: Collaborate with team members in real-time, with live updates and instant notifications.
Integration with OpenAI API: Utilize OpenAI API for additional features or assistance in task management (optional).
## Technologies Used
Frontend: React
Backend: Node.js with Express
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
Deployment: Frontend deployed on AWS S3, Backend deployed on AWS ECS
CI/CD: Jenkins for continuous integration and deployment
Installation
Clone the repository: git clone <repository-url>
Install dependencies for the frontend: cd frontend && npm install
Install dependencies for the backend: cd backend && npm install
Set up environment variables: Rename .env.example files in the frontend and backend directories to .env and provide the necessary configurations.
Start the development server for the frontend: cd frontend && npm start
Start the development server for the backend: cd backend && npm start
Folder Structure
frontend: Contains the frontend React application code.
backend: Contains the backend Node.js application code.
frontend/public: Public assets and HTML templates for the frontend.
backend/src: Backend code, including routes, controllers, models, and middleware.
backend/config: Configuration files for the backend, such as database connection settings and authentication details.
backend/utils: Utility functions or helper modules.
backend/tests: Test files and configurations for testing the backend code.
Contributing
Contributions to Task Room are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

## Developers 







