# 🎓 AI-Powered Smart Study Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
  <img src="https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-blue" alt="Frontend">
  <img src="https://img.shields.io/badge/Backend-Flask%2BDjango-green" alt="Backend">
  <img src="https://img.shields.io/badge/Database-MySQL-orange" alt="Database">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

<p align="center">
  <b>A comprehensive AI-powered web application designed to help students study smarter, not harder!</b>
</p>

<p align="center">
  <a href="https://friendly-lolly-26a977.netlify.app/">🚀 <b>Live Demo</b></a>
</p>

---

---

## 📖 About

The **AI Study Assistant** is a modern, feature-rich web application that leverages artificial intelligence to enhance the learning experience for students. Whether you need complex concepts explained in simple terms, want to generate quizzes to test your knowledge, or need to create flashcards for quick revision, this application has you covered.

### 🌟 Key Highlights

- **AI-Powered Learning**: Get intelligent explanations, summaries, and study materials
- **Interactive Quizzes**: Test your knowledge with auto-generated multiple-choice questions
- **Smart Flashcards**: Create and study with interactive flashcards
- **Modern UI/UX**: Beautiful glassmorphic design with smooth animations
- **Full-Stack Solution**: Complete frontend and backend implementation
- **Database Integration**: Persistent storage for all your study materials

---

## ✨ Features

### 🎓 For Students
- **Concept Explainer**: Get complex topics explained in simple, beginner-friendly language
- **Notes Summarizer**: Upload notes (PDF/TXT) or paste text to get concise summaries with key points
- **Quiz Generator**: Generate multiple-choice quizzes from any topic to test your knowledge
- **Flashcards**: Create interactive flashcards for quick revision and better retention
- **Progress Tracking**: View your learning history and activity

### 🎨 Design
- Modern glassmorphic UI with blue and pink gradient color scheme
- Responsive design that works on all devices
- Smooth animations and transitions
- Beautiful animated background with floating particles

## 🚀 Live Demo

You can experience the full AI Study Assistant directly in your browser without any setup!

<p align="center">
  <a href="https://friendly-lolly-26a977.netlify.app/">🚀 <b>Launch Live Demo</b></a>
</p>

## 📁 Project Structure

This repository contains the frontend source code for the AI Study Assistant.

```
project/
├── frontend/
│   ├── css/                          # Stylesheets for the glassmorphic design
│   ├── js/                           # Interactive logic and AI features
│   ├── login.html                    # Welcome & Authentication portal
│   ├── dashboard.html                # Main workspace
│   ├── links-manager.html            # Demo launch portal (Redesigned)
│   └── ...                           # Feature pages (Quiz, Summarizer, etc.)
└── ...
```

## 🎯 Features

- **Concept Explainer**: Simplifies complex topics using AI.
- **Notes Summarizer**: Converts long text into concise key points.
- **Quiz Generator**: Auto-generates MCQs for active study.
- **Flashcards**: Interactive study tools for revision.
- **Modern UI**: A premium glassmorphic interface built with vanilla HTML/CSS/JS.

## 👨‍💻 Development

### Adding New Features
1. Frontend: Add HTML page in `frontend/` and corresponding JS file
2. Flask: Add endpoint in `flask_backend/app.py` and logic in `ai_service.py`
3. Django: Add model, serializer, view, and URL route

### Database Changes
After modifying models in `django_backend/users/models.py`:
```bash
python manage.py makemigrations
python manage.py migrate
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
3. **Commit your changes**
4. **Push to the branch**
5. **Open a Pull Request**

### 💡 Ideas for Contributions

- Add real AI integration (OpenAI, Google AI, etc.)
- Implement more study features (Pomodoro timer, spaced repetition)
- Add support for more file formats
- Improve accessibility
- Add internationalization support
- Write tests

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Copyright (c) 2026 Chandana
```

This means you are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Use privately

---

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Flask and Django communities

---

**Made with ❤️ for students who want to study smarter, not harder!**
