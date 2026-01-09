🌍 WonderLust – Travel Listing Web Application

WonderLust is a full-stack travel listing web application inspired by platforms like Airbnb.
It allows users to discover, create, and manage travel listings, upload images, and share reviews, all with secure authentication and authorization.

The project is built using Node.js, Express.js, MongoDB, and EJS, following a clean MVC architecture.

🚀 Features

🔐 User authentication (Sign up, Login, Logout)

🏡 Create, edit, and delete travel listings

🖼️ Upload listing images using cloud storage

⭐ Review and rating system for listings

🛡️ Role-based authorization (only owners can edit/delete)

⚠️ Centralized error handling

✅ Data validation for secure inputs

📱 Responsive UI using Bootstrap

🛠️ Tech Stack
Backend

Node.js

Express.js

Database

MongoDB

Mongoose

Frontend

EJS (Embedded JavaScript Templates)

Bootstrap

Authentication & Security

Passport.js

Express Sessions

Joi Validation

Image Upload

Multer

Cloudinary

Architecture

MVC (Model–View–Controller)

📁 Project Structure
WonderLust/
│
├── app.js
├── package.json
├── cloudConfig.js
├── middleware.js
├── schema.js
│
├── controllers/
├── models/
├── routes/
├── views/
├── utils/
├── init/

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/WonderLust.git
cd WonderLust

2️⃣ Install dependencies
npm install

3️⃣ Setup environment variables

Create a .env file and add:

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
MONGO_URL=your_mongodb_connection_string
SECRET=your_session_secret

4️⃣ Run the application
npm start

5️⃣ Open in browser
http://localhost:3000

🧪 Database Initialization (Optional)

To load sample listings into the database:

node init/index.js

🧠 Learning Outcomes

Built a real-world full-stack web application

Implemented secure authentication and authorization

Learned cloud-based image storage

Designed RESTful routes and middleware

Applied error handling and validation best practices

Followed MVC architecture

📌 Future Improvements

Convert frontend to React

Add booking & payment system

Add search and filter functionality

Deploy on cloud (Render / Railway / AWS)

Add REST API version

👨‍💻 Author

Shantanu Achyut Mohod
Final Year CSE (Data Science) Student
Interested in Full-Stack Development & Backend Engineering

📄 License

This project is for learning and educational purposes.