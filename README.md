# 🛒 Reliance Digital Clone

A full-stack e-commerce web application replicating Reliance Digital's online store, built with modern web technologies.



## 🛠️ Tech Stack

### Frontend
- **React.js** - Component-based UI
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Client-side logic
- **HTML5** - Semantic markup

### Backend
- **Node.js** - Server runtime
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM

### APIs & Authentication
- **RESTful APIs** - Backend communication
- **JWT** - User authentication
- **Payment Integration** - Razorpay/Stripe

## ✨ Features

### 🛍️ E-commerce Features
- Product catalog with categories
- Advanced search and filtering
- Shopping cart management
- User authentication system
- Order tracking system
- Product reviews and ratings

### 🎨 User Experience
- Responsive design for all devices
- Intuitive navigation
- Fast loading optimized components
- Modern and clean UI/UX

### 🔒 Security & Performance
- Secure user authentication
- Input validation
- Error handling
- Optimized images and assets

## 📁 Project Structure
Reliance-Digital-Clone/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/ # UI components
│ │ ├── pages/ # Route components
│ │ ├── context/ # State management
│ │ ├── utils/ # Helper functions
│ │ └── styles/ # CSS files
├── server/ # Node.js backend
│ ├── models/ # Database models
│ ├── routes/ # API routes
│ ├── controllers/ # Business logic
│ └── middleware/ # Custom middleware
└── README.md

text

## 🏗️ Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/P-Muneeswari/Reliance.git
   cd Reliance
Backend Setup

bash
cd server
npm install

# Create .env file
echo "MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
PORT=5000" > .env

npm run dev
Frontend Setup

bash
cd client
npm install
npm start
Access Application

Frontend: http://localhost:3000

Backend API: http://localhost:5000

🔧 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	User registration
POST	/api/auth/login	User login
GET	/api/products	Get all products
GET	/api/products/:id	Get single product
POST	/api/cart	Add to cart
GET	/api/cart/:userId	Get user cart
POST	/api/orders	Create order
🎯 Key Functionality
Product Management
Category-wise product listing

Product search with filters

Detailed product pages

Image gallery for products

User Management
Secure registration and login

Profile management

Order history

Address management

Shopping Experience
Add/remove from cart

Quantity updates

Wishlist functionality

Secure checkout process

🚀 Deployment
Frontend (Netlify)
bash
cd client
npm run build
# Deploy build folder to Netlify
Backend (Railway/Heroku)
Set environment variables

Connect MongoDB Atlas

Deploy server directory

👩‍💻 Developer
P Muneeswari

GitHub: https://github.com/P-Muneeswari

LinkedIn: https://www.linkedin.com/in/muneeswari-p-14896532b



🤝 Contributing
Fork the project

Create feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open Pull Request

📄 License
This project is licensed under the MIT License.

⭐ If you like this project, please give it a star!
