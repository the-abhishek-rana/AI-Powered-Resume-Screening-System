# 🤖 AI-Powered Resume Screening System

An AI-powered Resume Screening System that automates candidate evaluation by parsing resumes, analyzing skills using Large Language Models (LLMs), and ranking candidates against job descriptions. The platform streamlines recruitment by reducing manual effort and providing AI-driven insights for better hiring decisions.

---

## 🚀 Features

* 📄 Upload and parse PDF resumes
* 🤖 AI-powered resume analysis using Groq LLM
* 🎯 Candidate ranking based on job descriptions
* 📊 Automated resume scoring
* 🔍 Skill and experience extraction
* 👤 Secure user authentication with Firebase
* 📂 Resume management dashboard
* 💬 AI chatbot assistance
* 📱 Responsive and modern user interface

---

## 🛠️ Tech Stack

### Frontend

* React.js
* TypeScript
* Vite
* Tailwind CSS
* React Router
* jsPDF
* pdfjs-dist

### Backend

* Python
* Flask
* Flask-CORS
* REST API

### AI / NLP

* Groq API
* PyPDF2

### Database & Authentication

* Firebase Authentication
* Firebase Firestore

### Development Tools

* Git
* VS Code
* ESLint
* PostCSS

---

## 📂 Project Structure

```text
.
├── backend/
│   ├── app.py
│   ├── utils.py
│   ├── requirements.txt
│   └── .env
│
├── public/
│
├── src/
│   ├── components/
│   ├── contexts/
│   ├── lib/
│   ├── pages/
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── firebase.json
├── firestore.rules
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/ai-powered-resume-screening-system.git
cd ai-powered-resume-screening-system
```

---

### 2. Install Frontend Dependencies

```bash
npm install
```

---

### 3. Install Backend Dependencies

```bash
cd backend
pip install -r requirements.txt
```

---

### 4. Configure Environment Variables

Create a `.env` file in the project root and another inside the `backend` folder.

Example backend `.env`

```env
GROQ_API_KEY=your_groq_api_key
```

Add your Firebase configuration to the frontend environment as required.

---

### 5. Start Backend

```bash
cd backend
python app.py
```

---

### 6. Start Frontend

```bash
npm run dev
```

Open

```
http://localhost:5173
```

---

## 💡 How It Works

1. User uploads one or more resumes.
2. The system extracts text from PDF files.
3. AI analyzes candidate skills, experience, and qualifications.
4. Resume content is compared with the provided job description.
5. Candidates receive AI-generated relevance scores.
6. Recruiters can review ranked candidates through the dashboard.

---

## 📸 Screenshots

Add screenshots here after deployment.

* Login Page
* Dashboard
* Resume Ranking
* Candidate Analysis
* AI Chatbot

---

## 📈 Future Enhancements

* ATS Integration
* Interview Scheduling
* Resume Clustering
* Candidate Feedback Automation
* Skill Gap Analysis
* Analytics Dashboard
* Docker Deployment
* CI/CD Pipeline
* Multi-language Resume Support

---

## 🎯 Skills Demonstrated

* Artificial Intelligence
* Large Language Models (LLMs)
* Natural Language Processing
* Prompt Engineering
* Resume Parsing
* Full Stack Development
* REST API Development
* Firebase Integration
* Authentication
* PDF Processing
* Cloud Database Management


If you found this project helpful, consider giving it a ⭐ on GitHub.
