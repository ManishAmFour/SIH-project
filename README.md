# 🚀 EduGuide - Digital Guidance Platform

A **comprehensive career and education advisory platform** that provides **personalized guidance to students**.

---

## ✨ Features

### 🎯 Personalized AI Recommendations

* AI-powered career path suggestions based on student profiles
* Academic performance analysis and course recommendations
* Interest and aptitude-based guidance system

### 📝 Interactive Assessments

* Comprehensive aptitude and interest-based quizzes
* Multi-category evaluation (Logical, Verbal, Numerical, Spatial)
* Detailed results with career stream recommendations

### 📊 Career Mapping Dashboard

* Visual career pathway exploration with interactive charts
* Industry demand analysis and salary trends
* Skills requirement mapping for different careers
* Entrance exam information and preparation guidance

### 🏫 College Directory

* Comprehensive database of nearby colleges and institutions
* Advanced search and filtering capabilities
* Detailed college information (fees, cutoffs, facilities)
* Integrated map functionality for location-based discovery

### ⏰ Timeline Tracker

* Admission, scholarship, and exam deadline management
* Important deadline & event tracking
* Smart notifications and reminders
* Visual timeline with status indicators

### 📚 Resource Hub

* Curated educational materials and e-books
* Scholarship information and application guides
* Skill development courses and video content
* Resume-building and career planning tools

### 👤 User Profile Management

* Comprehensive student profile system
* Academic history and interest tracking
* Preference management and notification settings
* Data privacy and security controls

---

## 🛠️ Tech Stack

### 🎨 Frontend

* **React 18 + TypeScript** for type safety
* **Tailwind CSS** for responsive, modern styling
* **React Router** for seamless navigation
* **Chart.js** for data visualization
* **Lucide React** for consistent iconography

### ⚙️ Backend & Database

* **Supabase** for backend services, authentication & real-time database
* **PostgreSQL** with **Row Level Security (RLS)** for data protection
* **Express.js** API server for custom business logic
* **JWT Authentication** through Supabase Auth

### 🔑 Key Features

* **Responsive Design** – Optimized for mobile, tablet, and desktop
* **Real-time Updates** – Live data synchronization
* **Secure Authentication** – Email/password with profile management
* **Data Visualization** – Interactive charts & progress tracking
* **Role-based Access** – Student & Admin user types

---

## ⚡ Getting Started

### ✅ Prerequisites

* Node.js 16+ and npm
* Supabase account and project

### ⚙️ Setup Instructions

1. **Install Dependencies**

   ```bash
   npm install
   ```

2. **Supabase Setup**

   * Create a project at [Supabase](https://supabase.com)
   * Copy your project URL & anon key
   * Add them to `.env.local`:

     ```env
     VITE_SUPABASE_URL=https://your-project.supabase.co  
     VITE_SUPABASE_ANON_KEY=your-anon-key-here  
     ```

3. **Database Setup**

   * Run provided SQL migrations in Supabase SQL editor
   * Creates necessary tables & security policies

4. **Start Development Server**

   ```bash
   npm run dev
   ```

5. **Start API Server (Optional)**

   ```bash
   npm run server:dev
   ```

---

## 📂 Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/            # Main application pages
├── context/          # React Context providers
├── lib/              # Configurations & utilities
├── services/         # API & data services
└── types/            # TypeScript types

server/               # Express.js backend
└── routes/           # API route handlers

supabase/
└── migrations/       # Database schema migrations
```

---

## 🔌 API Endpoints

* `POST /api/recommendations` → Get AI-powered career recommendations
* `POST /api/quiz/analyze` → Analyze quiz results
* `GET /api/colleges` → Fetch college directory
* `GET /api/timeline` → Get timeline events
* `GET /api/resources` → Fetch educational resources

---

## 🔒 Security Features

* **Row Level Security (RLS)** – Users access only their data
* **JWT Authentication** – Secure session management
* **Input Validation** – Sanitized user inputs
* **CORS Protection** – Cross-origin security

---

## 🚀 Deployment

* **Frontend** → Vercel, Netlify, or similar
* **Backend** → Supabase (primary) + Express (optional on Railway/Render)
* **Database** → Supabase with automatic backups

---

## 🤝 Contributing

1. Fork the repository
2. Create a branch → `git checkout -b feature/amazing-feature`
3. Commit changes → `git commit -m 'Add amazing feature'`
4. Push branch → `git push origin feature/amazing-feature`
5. Open a Pull Request





---

## 💬 Support

For support and questions, please reach out via the platform’s contact system.


