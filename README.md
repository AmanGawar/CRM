# CRM
🎯 Overview
CRM Hub is a comprehensive customer relationship management solution that empowers businesses to:

📊 Manage customer data efficiently
🎯 Create targeted customer segments
📧 Run multi-channel marketing campaigns
🤖 Get AI-powered customer insights
📈 Track campaign performance
✨ Features
🔐 Authentication & Authorization
👥 Customer Management
🎯 Segmentation Engine
📢 Campaign Management
🤖 AI-Powered Features
🛠️ Tech Stack
Frontend
{
  "framework": "React 18 + TypeScript",
  "styling": "TailwindCSS",
  "routing": "React Router DOM",
  "state": "React Context",
  "animations": "Framer Motion",
  "forms": "React Hook Form",
  "icons": "Lucide React"
}
Backend
{
  "runtime": "Node.js",
  "framework": "Express.js",
  "database": "MongoDB + Mongoose",
  "authentication": "JWT + Google Auth",
  "validation": "Joi",
  "logging": "Morgan"
}
AI Integration
{
  "provider": "Google Gemini API",
  "features": [
    "Performance Analysis",
    "Content Optimization",
    "Smart Scheduling",
    "Audience Insights"
  ]
}
📂 Project Structure
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
Clone the repository

git clone https://github.com/deeptimaan-k/CMS.git
cd CMS
Install dependencies

# Install root dependencies
npm install

# Install client dependencies
cd client && npm install

# Install server dependencies
cd ../server && npm install
Configure environment

# Copy example env files
cp .env.example .env
cd client && cp .env.example .env
cd ../server && cp .env.example .env
Start development servers

# From root directory
npm run dev
🔑 Environment Variables
Client
VITE_API_URL=http://localhost:5001/api
VITE_GOOGLE_CLIENT_ID=your_google_client_id
Server
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5001
NODE_ENV=development
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GEMINI_API_KEY=your_gemini_api_key
📡 API Reference
Authentication
Method	Endpoint	Description
POST	/api/auth/login	User login
POST	/api/auth/register	User registration
POST	/api/auth/google	Google OAuth
GET	/api/auth/profile	Get profile
PUT	/api/auth/profile	Update profile
Customers
Method	Endpoint	Description
GET	/api/customers	List customers
POST	/api/customers	Create customer
GET	/api/customers/:id	Get customer
PUT	/api/customers/:id	Update customer
DELETE	/api/customers/:id	Delete customer
Campaigns
Method	Endpoint	Description
GET	/api/campaigns	List campaigns
POST	/api/campaigns	Create campaign
GET	/api/campaigns/:id	Get campaign
POST	/api/campaigns/:id/send	Send campaign
Segments
Method	Endpoint	Description
GET	/api/segments	List segments
POST	/api/segments	Create segment
GET	/api/segments/:id	Get segment
PUT	/api/segments/:id	Update segment
DELETE	/api/segments/:id	Delete segment
POST	/api/segments/preview	Preview audience
🤔 Technical Decisions
Why MongoDB?
Flexible schema for varying customer data
Faster development iteration
Better handling of nested data structures
Excellent Node.js integration
Why Client-Side Rendering?
Rich interactive features
Smooth user experience
Reduced server load
Better state management
Authentication Strategy
Real Google OAuth implementation
JWT for secure sessions
Role-based access control
Scalable user management
