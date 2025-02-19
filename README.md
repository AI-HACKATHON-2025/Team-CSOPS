# Team-CSOPS
AI-Powered Adaptive Learning Mentor

Overview

This project is a web-based AI-powered learning mentor that:
✅ Generates 10 MCQs based on a given topic.
✅ Analyzes student performance and detects weak areas.
✅ Suggests YouTube video lectures for improvement.
✅ Built with FastAPI (backend) and React (frontend).
---
🚀 Features
MCQ Generation: Automatically generates 10 multiple-choice questions based on the input topic.
Performance Analysis: Detects weak areas based on incorrect answers.
YouTube Recommendations: Suggests video lectures based on weak areas.
Fast & Free: Uses open-source models (no OpenAI required).
---
🛠 Tech Stack
---
📁 Project Structure

AI-Learning-Mentor/
│── backend/                 # FastAPI Backend
│   ├── main.py              # API for MCQs, performance analysis & video recommendations
│   ├── requirements.txt     # Backend dependencies
│── frontend/                # React Frontend
│   ├── src/
│   │   ├── App.js           # Main React component
│   │   ├── index.js         # Entry point
│   ├── package.json         # React dependencies
│── README.md                # Documentation


---

⚡ Installation & Setup
1️⃣ Backend Setup (FastAPI)
📌 Install dependencies
pip install fastapi uvicorn transformers youtube-search-python
📌 Run the FastAPI Server
uvicorn main:app --reload
📌 Test API at http://127.0.0.1:5501
---
2️⃣ Frontend Setup (React)
📌 Install React & Dependencies

npx create-react-app ai-learning-mentor
cd ai-learning-mentor
npm install axios
📌 Run React Frontend
npm start

---

💡 How It Works
1. User enters a topic in the frontend.
2. FastAPI generates 10 MCQs and displays them.
3. User selects answers, and the backend analyzes performance.
4. If weaknesses are found, the app suggests YouTube lectures.
--
🎯 Future Improvements
✔ Add User Authentication (save progress).
✔ Improve MCQ Accuracy using better AI models.
✔ Enhance UI/UX with animations.
---
📝 License
This project is open-source and free to use. 🚀
