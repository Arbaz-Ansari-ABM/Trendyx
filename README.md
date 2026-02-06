Markdown
Copy
Code
Preview
# Trendyx - Full Stack E-commerce Platform

A modern MERN stack e-commerce platform with secure payments, admin dashboard, and responsive design.

## 🚀 Features

- 🛍️ Complete shopping experience with cart & checkout
- 👤 Customer & Admin dual roles
- 💳 Stripe payment integration
- 📱 Fully responsive design
- 🔍 Product search & filtering
- ⭐ Product reviews & ratings
- 📦 Order tracking & history
- 👨‍💼 Admin dashboard for management
- 🔒 JWT authentication

## 🛠️ Tech Stack

**Frontend:** React 18, Tailwind CSS, Redux Toolkit, Vite  
**Backend:** Node.js, Express.js, MongoDB  
**Services:** Stripe, Cloudinary, JWT

## ⚡ Quick Start

```bash
# Clone & Install
git clone https://github.com/Arbaz-Ansari-ABM/Trendyx-Full-Stack.git
cd Trendyx

# Backend
cd server && npm install
cp .env.example .env  # Add your credentials
npm run dev

# Frontend (new terminal)
cd client && npm install
npm run dev

🔑 Environment Variables

MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=sk_test_...
STRIPE_PUBLISHABLE_KEY=pk_test_...
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PORT=5000

📁 Project Structure
Copy
Trendyx/
├── client/          # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── store/
│   └── package.json
├── server/          # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
└── README.md

🌐 Deployment

Frontend	Backend	Database
Vercel / Netlify	Render / Railway	MongoDB Atlas

👤 Developer
Arbaz Ahmad Ansari

📧 arbazahmadansari03@gmail.com
🎓 MCA Student, Galgotias University
💻 MERN Stack Developer

Built with ❤️ using React, Node.js & MongoDB
