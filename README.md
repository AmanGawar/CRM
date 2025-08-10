# CRM
📌 CRM Hub






CRM Hub is a powerful Customer Relationship Management solution that helps businesses manage customer data, run targeted marketing campaigns, and leverage AI insights — all in one platform.

🎯 Overview
CRM Hub enables you to:

📊 Manage customer data efficiently

🎯 Segment customers for targeted campaigns

📧 Run multi-channel marketing campaigns

🤖 Gain AI-powered customer insights

📈 Track campaign performance in real-time

✨ Features
🔐 Authentication & Authorization

👥 Customer Management

🎯 Segmentation Engine

📢 Campaign Management

🤖 AI-Powered Insights

🛠 Tech Stack
Frontend: React 18 + TypeScript, TailwindCSS, React Router DOM, React Context, Framer Motion, React Hook Form, Lucide React
Backend: Node.js, Express.js, MongoDB + Mongoose, JWT + Google Auth, Joi Validation, Morgan Logging
AI: Google Gemini API for Performance Analysis, Content Optimization, Smart Scheduling, Audience Insights

📸 Screenshots
(Replace placeholders with real screenshots)

Dashboard

Customer Management

🌐 Live Demo
🚀 View Live App
📹 Watch Demo Video

📂 Project Structure
csharp
Copy
Edit
crm-hub/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/    # UI components
│   │   ├── context/      # State management
│   │   ├── pages/        # Route components
│   │   └── utils/        # Helper functions
│   └── public/           # Static files
│
└── server/               # Node.js backend
    ├── config/          # Configuration
    ├── controllers/     # Route handlers
    ├── middleware/      # Custom middleware
    ├── models/          # Database models
    ├── routes/          # API routes
    └── validation/      # Request schemas
🚀 Installation
bash
Copy
Edit
# Clone the repository
git clone https://github.com/deeptimaan-k/CMS.git
cd CMS

# Install dependencies
npm install
cd client && npm install
cd ../server && npm install
Environment Setup
bash
Copy
Edit
cp .env.example .env
cd client && cp .env.example .env
cd ../server && cp .env.example .env
Run the app
bash
Copy
Edit
npm run dev
📡 API Reference
(See full API docs in the repository)

Method	Endpoint	Description
POST	/api/auth/login	User login
POST	/api/auth/register	User registration
POST	/api/auth/google	Google OAuth
GET	/api/customers	List customers
POST	/api/campaigns	Create campaign
GET	/api/segments	List segments

🤔 Technical Decisions
MongoDB: Flexible schema for customer data

Client-Side Rendering: Smooth, interactive UI

Auth: Google OAuth + JWT with role-based access
