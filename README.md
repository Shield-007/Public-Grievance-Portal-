🏙️ Bengaluru Sahaya Portal
Empowering Citizens. Verifying Action. Resolving Bengaluru.

🚀 View Live Site ⚙️ Backend API

Bengaluru Sahaya is a modern, AI-powered civic grievance portal designed to streamline the reporting and resolution of urban issues like garbage accumulation, potholes, water leaks, and electricity faults. By leveraging computer vision and a brutalist design aesthetic, we ensure that every community report is verified, tracked, and resolved with transparency.

🚀 Key Features
🧠 AI Photo Verification: Integrates YOLOv8 via FastAPI to automatically verify the authenticity and category of reported grievances from uploaded photos.
⚡ Brutalist UI/UX: A bold, high-contrast interface built with Next.js and Tailwind CSS, designed for speed and clarity.
🤖 Maya AI Chatbot: A friendly AI assistant to help citizens navigate the portal and file reports via natural language.
📱 Multilingual Support: Fully localized in English and Kannada to reach every citizen of Bengaluru.
📋 Admin Dashboard: A comprehensive command center for city officials to review AI-verified reports, dispatch teams, and track resolution timelines.
🚨 Civic Directory: Quick access to essential contact numbers for BBMP, BWSSB, BESCOM, and Emergency services.
🛠️ Tech Stack
Frontend
Framework: Next.js (App Router)
Styling: Tailwind CSS
Animations: Framer Motion
Icons: Heroicons
Backend
Framework: FastAPI (Python)
Database: MongoDB Atlas (Motor Async Driver)
AI/ML: YOLOv8 (Ultralytics)
Communication: Twilio (SMS OTP Verification)
Environment: Uvicorn
📦 Installation & Setup
Prerequisites
Python 3.9+
Node.js 18+
MongoDB Atlas Account
Backend Setup
Navigate to the backend directory:
cd backend
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # Windows: .\venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Create a .env file in the root (see .env.example).
Run the server:
uvicorn main:app --reload
Frontend Setup
Navigate to the frontend directory:
cd frontend
Install dependencies:
npm install
Run the development server:
npm run dev
🌐 Deployment
For detailed deployment instructions on Vercel (Frontend), Render (Backend), and MongoDB Atlas, please refer to our Deployment Guide.

🤝 Contribution
Bengaluru Sahaya is a community-driven project. We welcome contributions that help make our city cleaner and safer.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git origin feature/AmazingFeature)
Open a Pull Request
📜 License
Distributed under the MIT License. See LICENSE for more information.

Developed with ❤️ for Namma Bengaluru.
