# Employee-leave-managment
Employee Leave Management System is a web application built using the MERN stack to manage employee leave requests efficiently.

Features
Employee Dashboard: Employees can log in to view their leave balance, submit leave requests, and view the status of their requests.
Admin Dashboard: Admins can manage employee leave requests, approve or reject requests, view leave balances, and generate reports.
Authentication: Secure authentication system using JWT (JSON Web Tokens).
Role-based Access Control: Admins have access to additional features compared to regular employees.
Leave Types: Supports multiple types of leave such as sick leave, vacation, etc.
Email Notifications: Automated email notifications for leave request status updates.
Technologies Used
Frontend: React.js, Redux (for state management), React Router (for routing)
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)
Styling: CSS3, Bootstrap (optional)
Others: Axios (for HTTP requests), Moment.js (for date formatting)
Getting Started
Clone the repository:
git clone https://github.com/yourusername/employee-leave-management.git
Install dependencies:
# Go to the project directory
cd employee-leave-management

# Install server dependencies
npm install

# Go to the client directory
cd client

# Install client dependencies
npm install
Set up environment variables:
Create a .env file in the root directory and add the following variables:

MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Run the application:
# Run the server
npm start

# Run the client
cd client
npm start
Access the application:
Open your web browser and go to http://localhost:3000 to access the application.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
