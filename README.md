# AI Attendance Management System 📚

A terminal-based attendance management system built using Python, JSON, and AI. It processes natural-language commands to manage student attendance without requiring a frontend.

## 🚀 Features
- AI-powered attendance commands
- Check student attendance by date
- Mark or remove attendance
- Automatically calculate attendance percentages
- Calculate class attendance average
- Update student records in JSON

## 🛠️ Tech Stack
- Python
- JSON
- OpenAI API
- Python-dotenv

## 📁 Project Structure
```text
Attendance-AI/
├── main.py
├── attendance.py
├── ai_parser.py
├── students.json
├── requirements.txt
├── .env
└── README.md
```

## ⚙️ Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Attendance-AI.git
   cd Attendance-AI
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your API key to `.env`:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

4. Run the application:
   ```bash
   python main.py
   ```

## 💡 Example Commands
- "Was Rahul present on 10 October 2026?"
- "Mark Rahul absent on 10 October 2026."
- "What is Rahul's attendance percentage?"

## 🎯 Objective
To combine AI and Python for natural-language attendance management, automated calculations, and JSON-based data storage.

## 🔐 Security
Never upload your `.env` file or expose your API key on GitHub.

## 👨‍💻 Author
Yuvraj Singh
