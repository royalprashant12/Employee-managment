Employee Management System
An intuitive Employee Management System designed to streamline the tracking of employee details, tasks, and performance. This application allows admins and associates to manage tasks, track working hours, and generate insightful reports.

🌟 Features
Admin Portal: Manage employee data, assign tasks, and generate reports.
Employee Portal: View tasks, update status, and track working hours.
Task Management: Create, update, and delete tasks.
Charts & Reports: Visualize work hours and task distribution using charts.
File Uploads: Securely upload documents (using Cloudinary).
🚀 Getting Started
1. Clone the Repository
Start by cloning this repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/employee-management.git
cd employee-management
2. Install Dependencies
Use the following command to install all the necessary dependencies:

bash
Copy code
npm install
📦 Prerequisites
Before running the project, ensure you have the following tools installed:

Node.js: Download and install from Node.js.
MongoDB: Make sure MongoDB is set up and running on your local machine or a cloud service.
Cloudinary Account: Set up a Cloudinary account for file uploads.
⚙️ Setup Environment Variables
Create a .env file at the root of the project and add the following:

bash
Copy code
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

MONGO_URI=your_mongo_db_connection_string
PORT=5000
🛠️ Install Required Tools
1. Multer (For file uploads)
Multer is a middleware for handling multipart/form-data, primarily used for uploading files.

bash
Copy code
npm install multer
2. Cloudinary (For image storage)
Cloudinary is used to store and manage media files in the cloud.

bash
Copy code
npm install cloudinary
npm install multer-storage-cloudinary
3. Express.js (Backend framework)
Ensure Express.js is installed for building the backend API.

bash
Copy code
npm install express
4. Additional Packages
Other required packages include:

mongoose: For MongoDB database interactions.
dotenv: For environment variables.
cors: To enable Cross-Origin Resource Sharing.
To install these packages, run:

bash
Copy code
npm install mongoose dotenv cors
📂 Project Structure
bash
Copy code
├── backend
│   ├── config
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── uploads
│   ├── server.js
├── frontend
│   ├── public
│   ├── src
│   │   ├── Components
│   │   ├── App.js
│   │   ├── index.js
├── .env
├── package.json
└── README.md
🚀 Running the Application
1. Backend (API Server)
To start the server:

bash
Copy code
cd backend
npm start
The server will run on http://localhost:8080.

2. Frontend (React App)
To start the frontend React app:

bash
Copy code
cd frontend
npm start
The React app will run on http://localhost:3000.

📤 File Uploads with Cloudinary
The system allows uploading images/documents using multer and Cloudinary. Ensure your .env file contains the correct Cloudinary API credentials.

🎥 Demo Video
Check out the full walkthrough of the project setup and functionality in the video below:

Demo Video

🤝 Contributing
Feel free to fork this repository and submit pull requests. Any contributions to improve this system are welcome!

📧 Contact
If you have any questions or need further assistance, please reach out:

Prashant Kumar
Email: prashantroyal17@gmail.com
