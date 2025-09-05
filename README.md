# 🚀 Intern Project – Full Stack Application

## 👤 Author
**Arsh Gupta**

---

## 🔗 Working URLs
- **Frontend Repository:** [https://github.com/Arsh0080/Int_Pro_Frontend](https://github.com/Arsh0080/Int_Pro_Frontend)  
- **Backend Repository:** [https://github.com/Arsh0080/Int_Pro_Backend](https://github.com/Arsh0080/Int_Pro_Backend)  

- **Frontend Deployment (Vercel):** [https://int-pro-frontend.vercel.app/](https://int-pro-frontend.vercel.app/)  
- **Backend Deployment (Render):** [https://int-pro-backend.onrender.com/](https://int-pro-backend.onrender.com/)  

- **Resume Link:** [Click here](https://drive.google.com/file/d/1xYsWq2l5SGOE1Fqc02nqq8QxRRRrr6Eb/view?usp=drive_link)

---

## 🏗️ Project Architecture

The project is divided into two parts:

1. **Backend (Node.js + Express + MongoDB)**
   - Handles API requests
   - Stores data in MongoDB
   - Hosted on **Render**

2. **Frontend (React)**
   - Minimal UI to:
     - Search by skill
     - List projects
     - View profile
   - Calls hosted backend API (CORS enabled)
   - Hosted on **Vercel**

---

## ⚙️ Setup Instructions

### 🔹 Backend (Local Setup)
```bash
# Clone repo
git clone https://github.com/Arsh0080/Int_Pro_Backend.git
cd Int_Pro_Backend

# Install dependencies
npm install

# Create .env file
MONGO_URI=your_mongodb_connection_string
PORT=5000

# Run locally
npm run dev

Frontend
public/        # Static assets
src/
 ├── App.js    # Main component
 ├── index.js  # React entry point
 ├── App.css   # Styling
 ├── ...
.env           # Environment variables

Backend
index.js       # Entry point for server
models.js      # Database models
.env           # Environment variables
package.json   # Dependencies and scripts

# Clone repo
git clone https://github.com/Arsh0080/Int_Pro_Frontend.git
cd Int_Pro_Frontend

# Install dependencies
npm install

# Create .env file
REACT_APP_BACKEND_URL=http://localhost:5000

# Run locally
npm start

