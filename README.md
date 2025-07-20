# 🚀 Job Portal - Modern Job Search Platform

A full-stack job portal application built with React, Node.js, and MongoDB. Features real-time job applications, advanced search, recruiter dashboard, and modern authentication.

![Job Portal Demo](https://img.shields.io/badge/Status-Live-green)
![React](https://img.shields.io/badge/React-18.3.1-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green)

## ✨ Features

### 🔍 **Advanced Job Search**
- Real-time job filtering by title, location, and company
- Category-based job browsing (Programming, Data Science, Design, etc.)
- Salary range filtering
- Remote/On-site job filtering

### 👤 **User Authentication & Profiles**
- Secure authentication with Clerk
- Google OAuth integration
- User profile management
- Application tracking dashboard

### 💼 **Job Application System**
- One-click job applications
- Resume upload and management
- Application status tracking
- Email notifications for applications

### 🏢 **Recruiter Dashboard**
- Post and manage job listings
- View and manage applications
- Company profile management
- Analytics and insights

### 📱 **Modern UI/UX**
- Responsive design for all devices
- Dark/Light mode support
- Real-time notifications
- Intuitive navigation

## 🛠️ Tech Stack

### **Frontend**
- **React 18** - Modern UI framework
- **Vite** - Fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Clerk** - Authentication service
- **Axios** - HTTP client

### **Backend**
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB ODM
- **Multer** - File upload handling
- **Cloudinary** - Cloud storage

### **Deployment**
- **Vercel** - Frontend hosting
- **Railway/Heroku** - Backend hosting
- **MongoDB Atlas** - Cloud database

## 🚀 Getting Started

### **Prerequisites**
- Node.js (v16 or higher)
- MongoDB (local or Atlas)
- Clerk account for authentication
- Cloudinary account for file uploads

### **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smitb-job-portal.git
   cd smitb-job-portal
   ```

2. **Install dependencies**
   ```bash
   # Install backend dependencies
   cd server && npm install
   
   # Install frontend dependencies
   cd ../client && npm install
   ```

3. **Environment Setup**
   
   Create `.env` file in `server/` directory:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   CLERK_SECRET_KEY=your_clerk_secret_key
   CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   ```

4. **Run the application**
   ```bash
   # Start backend server
   cd server && npm run server
   
   # Start frontend (in new terminal)
   cd client && npm run dev
   ```

5. **Access the application**
   - Frontend: `http://localhost:5173`
   - Backend API: `http://localhost:5000`

## 📱 Screenshots

### Homepage
![Homepage](https://via.placeholder.com/800x400/4F46E5/FFFFFF?text=Job+Portal+Homepage)

### Job Search
![Job Search](https://via.placeholder.com/800x400/10B981/FFFFFF?text=Advanced+Job+Search)

### Recruiter Dashboard
![Dashboard](https://via.placeholder.com/800x400/F59E0B/FFFFFF?text=Recruiter+Dashboard)

## 🔧 API Endpoints

### Jobs
- `GET /api/jobs` - Get all jobs
- `POST /api/jobs` - Create new job
- `GET /api/jobs/:id` - Get job by ID
- `PUT /api/jobs/:id` - Update job
- `DELETE /api/jobs/:id` - Delete job

### Applications
- `POST /api/applications` - Submit application
- `GET /api/applications` - Get applications
- `PUT /api/applications/:id` - Update application status

### Users
- `GET /api/users/profile` - Get user profile
- `PUT /api/users/profile` - Update user profile

## 🎯 Key Features

### **Real-time Job Search**
Advanced filtering system with multiple criteria including job title, location, salary range, and job type. Users can search across thousands of job listings with instant results.

### **Secure Authentication**
Integrated Clerk authentication system providing secure user registration, login, and profile management with Google OAuth support.

### **File Upload System**
Cloudinary integration for secure resume and document uploads with automatic file optimization and cloud storage.

### **Responsive Design**
Mobile-first approach ensuring optimal user experience across all devices and screen sizes.

### **Real-time Notifications**
Instant updates for job applications, interview schedules, and important notifications.

## 🚀 Deployment

### **Frontend (Vercel)**
1. Connect GitHub repository to Vercel
2. Set environment variables
3. Deploy automatically on push

### **Backend (Railway/Heroku)**
1. Connect repository to Railway/Heroku
2. Set environment variables
3. Deploy with automatic scaling

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## 🙏 Acknowledgments

- [Clerk](https://clerk.com) for authentication
- [Cloudinary](https://cloudinary.com) for file storage
- [Tailwind CSS](https://tailwindcss.com) for styling
- [MongoDB Atlas](https://mongodb.com/atlas) for database

---

⭐ **Star this repository if you found it helpful!**
