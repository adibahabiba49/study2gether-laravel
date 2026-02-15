# Study2Gether – Intelligent Class Test & Analytics Platform

Study2Gether is a cloud-based Class Test Management and Student Performance Analytics system designed to streamline assessment workflows and enable data-driven academic insights.

Originally developed using Core PHP and MongoDB, the system has been refactored to Laravel 12 with MongoDB Atlas integration for scalable cloud deployment.

---

# 🚀 Tech Stack

### Backend
- Laravel 12 (Refactored Architecture)
- Core PHP (Initial Version)
- RESTful Structure
- Role-Based Authentication

### Database
- MongoDB Atlas (Cloud-hosted NoSQL Database)
- MongoDB Laravel Eloquent Driver
- Secure TLS-based connection

### Frontend
- HTML
- CSS
- Blade Templates (Laravel Version)

### Dev Tools
- Composer
- Git & GitHub
- MongoDB Compass
- PHP 8.5 (NTS x64)

---

# ✨ Core Features

## 👤 Admin Panel
- Secure login
- Manage students and teachers
- Create subjects / courses
- Define chapters and topics
- Schedule Class Tests
- Dashboard overview

## 👨‍🏫 Teacher Panel
- Create MCQ and Written Class Tests
- Add questions with chapter/topic tagging
- Automatic MCQ evaluation
- Manual evaluation for written tests
- View topic-wise & chapter-wise weakness
- Student performance tracking

## 👩‍🎓 Student Panel
- View CT schedule
- Attend timed CTs (auto-submit supported)
- Review answers & results
- Topic-wise performance analysis
- CT-to-CT progress tracking

---

# 🧠 Analytics Architecture

The system is structured to support:

- Accuracy per topic
- Speed vs accuracy analysis
- Repeated mistake detection
- Chapter-wise weakness identification
- Study habit tracking (future enhancement)

The MongoDB schema is designed for analytics scalability and AI-driven recommendation expansion.

---

# 🏗 Architecture Evolution

## Phase 1 – Core PHP + Local MongoDB
- Multi-role system
- MCQ + Written evaluation
- Manual analytics

## Phase 2 – Laravel 12 Refactor
- MVC architecture
- Environment-based configuration
- Clean routing & middleware
- Composer-managed dependencies

## Phase 3 – Cloud Migration
- MongoDB Atlas integration
- Secure IP-based access control
- TLS connection
- Cloud-ready configuration

---

# 📂 Project Structure (Laravel Version)


## Project Structure
study2gether-laravel/
├── app/
│ ├── Models/
│ ├── Http/
│ └── Providers/
├── config/
├── routes/
├── resources/
├── composer.json
├── .env
└── README.md
```

---

# 🗃 MongoDB Collections

- users (admin, teacher, student roles unified)
- courses
- questions
- class_tests
- submissions
- student_analytics
- student_behavior

---

# 🔐 Security

- Password hashing (bcrypt)
- Role-based middleware protection
- Session management
- Environment-based secret management (.env)

---

# ⚙ Installation (Laravel Version)

1. Clone repository
2. Run:

---

# 🔮 Future Enhancements

- AI-based personalized practice generation
- Adaptive difficulty adjustment
- Mood-based study suggestions
- ML-driven performance prediction
- Visual analytics dashboards
- Mobile application integration

---

# 🎯 Project Goal

To build a scalable, analytics-driven academic evaluation platform that bridges assessment management with intelligent learning insights.

---

# 📌 Status

Core architecture successfully migrated to Laravel 12 with MongoDB Atlas.
System ready for feature expansion and AI integration.

---

# 👩‍💻 Author

Developed and architected by Adiba Habiba.
