# FreelanceFinder
**FreelanceFinder** is a platform designed to connect freelancers with meaningful job opportunities across various industries. With the tagline "Discovering Opportunities, Unlocking Potential," it aims to empower individuals by helping them find the right projects that match their skills and aspirations. The platform not only facilitates freelance work but also encourages personal and professional growth, enabling freelancers to realize their full potential.

📌 Features

👤 User Functionality Sign up and log in securely Register complaints with details (address, pincode, etc.) View status of submitted complaints Chat with assigned agent

🧑‍💼 Rental Portal View all users (Rental/Owner) Assign complaints to agents View status and history of all complaints Delete user data if necessary

👨‍🔧 Owner Dashboard View assigned complaints Update complaint statuses Engage in conversation via messaging

🛠️ Tech Stack Frontend: React JS Bootstrap 5 React Router DOM Axios Backend: Node.js Express.js MongoDB with Mongoose CORS, Body-Parser Database: MongoDB Atlas (cloud-hosted NoSQL DB)

🗂️ Project Structure ResolveNow/ │ ├── backend/ # Express + MongoDB backend │ ├── config.js # MongoDB connection │ ├── index.js # All API endpoints │ └── Schema.js # Mongoose schemas │ ├── frontend/ # React frontend │ ├── src/ │ │ ├── components/ # UI components (user, admin, agent) │ │ ├── App.js │ │ ├── App.css │ │ └── index.js │ └── public/ │ │ │ ├── index.html │ ├── .env # (Optional) For environment variables └── README.md

yaml Copy Edit

🚀 Getting Started

Clone the Repository
git clone https://github.com/your-username/ResolveNow.git cd ResolveNow

2. Setup Backend bash Copy Edit cd backend npm install node index.js Ensure MongoDB is running locally or use your MongoDB Atlas URI in config.js.

3. Setup Frontend bash Copy Edit cd frontend npm install npm start The frontend will run on http://localhost:3000

🌐 Environment Configuration In backend/config.js, replace:

js Copy Edit mongoose.connect("mongodb://127.0.0.1:27017/Freelance") with your MongoDB Atlas URI if deploying to production.

📦 Future Enhancements ✅ File upload with complaint

✅ Email notifications for status updates

✅ Authentication token with JWT

✅ Improved UI with dark mode

✅ Deployment (Render/Vercel/Netlify)

📄 License This project is licensed under the MIT License - see the LICENSE file for Freelance
