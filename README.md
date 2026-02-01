# 🧠 QuizNest – Quiz App

## 🚀 Features

### 🔐 Authentication

* Google OAuth & JWT-based secure login
* Role-based access (User, Premium, Admin)

### 🧠 AI-Powered Quiz Generation

* Automatically generate MCQs & written questions
* AI assigns duration, marks, and evaluates written answers using NLP
* Adaptive difficulty: beginners get easier questions, advanced users get harder ones

### 🎮 Smart Quiz Experience ✅

* **Intelligent Fullscreen Mode**: Auto-submit protection when interrupted (Escape key, route changes, browser close)
* **Performance-Optimized UI**: Lightning-fast rendering with smooth animations
* **Mobile-First Design**: Perfect responsive experience across all devices
* **Enhanced Timer**: Centered, non-intrusive timing system
* **Smart State Management**: Efficient data handling with React best practices

### 🤖 AI Study Buddy *(NEW - Premium Feature)* ✅

* **Google Gemini 2.5 Pro Integration**: Advanced AI tutoring with personalized responses
* **Persistent Study Sessions**: Context-aware conversations that remember your learning history
* **Dynamic Quiz Generation**: Create custom quizzes directly from AI conversations
* **Smart Explanations**: Get detailed concept explanations adapted to your learning style
* **Personalized Study Plans**: AI-generated learning schedules and improvement goals
* **Weak Area Analysis**: Targeted suggestions for skill improvement
* **Quick Actions**: Pre-defined study actions for common learning tasks
* **Seamless Navigation**: Direct integration with existing quiz system

### ⚔️ Real-Time Quiz Battles *(NEW - Live Multiplayer)* ✅

* **Live 1v1 Quiz Duels**: Challenge other users in real-time quiz competitions
* **Speed Scoring System**: First to answer correctly gets maximum points with time bonuses
* **Real-Time Leaderboards**: Dynamic rankings that update instantly during gameplay
* **Room Management**: Create, join, and manage multiplayer quiz rooms
* **Live Chat System**: Real-time messaging during quiz battles
* **Synchronized Timers**: Perfect countdown synchronization across all players
* **Instant Results**: Immediate feedback after each question with live scoring
* **Host Controls**: Room creators can customize settings and manage gameplay
* **Multiplayer Statistics**: Dedicated stats tracking for competitive gameplay

### 📱 Progressive Web App (PWA) *(NEW)* ✅

* **Native App Experience**: Install QuizNest as a native app on any device
* **Offline Functionality**: Continue learning even without internet connection
* **Push Notifications**: Study reminders and achievement notifications
* **Background Sync**: Automatic data synchronization when connection restored
* **Service Worker Caching**: Lightning-fast loading with smart caching strategies
* **Cross-Platform**: Works seamlessly on mobile, tablet, and desktop

### 🤖 Intelligence Dashboard *(Premium Feature)* ✅

* **Smart Quiz Recommendations**: AI-powered quiz suggestions based on performance, favorite categories, and learning patterns
* **Adaptive Difficulty System**: Dynamic difficulty adjustment based on recent performance with confidence scoring
* **Learning Analytics**: Comprehensive performance insights with trends, predictions, and personalized study recommendations
* **Performance Trends**: Visual weekly performance tracking with interactive charts
* **Next Quiz Predictions**: AI predicts expected performance on upcoming quizzes
* **Personalized Study Tips**: Custom recommendations for optimal study times and improvement areas

### 📊 Advanced Analytics & Reports ✅

* **Beautiful User Reports**: Modern card layouts replacing clunky tables on mobile
* **Real-Time Performance Tracking**: Live progress updates and achievements
* **Comprehensive Analytics**: Category-wise performance breakdown
* **Visual Progress Indicators**: Interactive charts for better understanding
* **Quiz History**: Detailed performance reports with visual feedback
* **Score Analytics**: Real-time feedback and comprehensive score tracking

### 🏆 Gamification

* **Achievements System** ✅

  * Earn badges like “Quiz Master,” “Speed Genius,” and “Perfect Score”
  * View badges and stats in user profile
* **Leaderboards**

  * Weekly and monthly top scorers
  * Promotes user engagement and competition

### ⚔️ Live Quiz Battles *(Fully Implemented)* ✅

* Real-time multiplayer quiz competitions with Socket.IO
* Live scoring with speed bonuses and instant feedback
* Chat system for communication during battles
* Room management with customizable settings

### 🎨 Next-Generation UI/UX ✅

* **Advanced Theme Selector** with 15+ themes including Light/Dark/Material/Dracula/Nord modes
* **Mobile-First Design** with responsive navigation bar for phones and tablets
* **Enhanced Dashboard** with modern card-based layout and data visualization
* **Interactive Quiz Modal** with progress tracking and mobile optimization
* **Gamification Hub** with daily challenges and tournament management interface
* **PWA Installation Prompts** with native app-like experience
* **Consistent Design System** with polished animations and micro-interactions
* **Performance Optimized UI** with 60fps animations and reduced computational overhead
* **Hardware Accelerated Transitions** using CSS transforms and optimized backdrop-filters
* **Smooth Animation Framework** with simplified framer-motion implementations for better performance

### 💳 Subscription Plans

* **Free Plan**: Limited quizzes, core features, basic multiplayer access
* **Premium Plan**: Unlimited access, AI Study Buddy, Intelligence Dashboard, advanced achievements, PWA features, and premium multiplayer battles

### 📚 Comprehensive Help System ✅

* **Interactive Help Guide**: Step-by-step tutorials for every feature
* **User Type Explanations**: Clear differences between Simple, Premium, and Admin users
* **Quiz Creation Tutorials**: Complete guide for premium users
* **Troubleshooting Section**: Solutions for common issues
* **Feature Walkthroughs**: Detailed explanations of all platform capabilities
* **Mobile-Optimized Help**: Responsive help system for all devices

### 🛡️ Admin Panel

A powerful admin dashboard providing full control of platform operations:

* 🔍 Monitor user activity and quiz submissions
* 🧩 Add/Edit/Delete quizzes and questions
* 👥 Manage users: roles, status, analytics
* 📈 Real-time insights and platform stats

---

## 🛠️ Tech Stack

* **Frontend**: React, CSS, Vite, PWA Service Workers
* **Backend**: Node.js, Express.js, MongoDB, Socket.IO
* **AI Integration**: Google Gemini 2.5 Pro, Together AI
* **Real-Time**: Socket.IO for multiplayer functionality
* **Authentication**: JWT, Google OAuth
* **PWA**: Service Worker, Web App Manifest, Push Notifications
* **Performance**: Optimized CSS animations, hardware acceleration, reduced backdrop-filter usage
* **Animation Framework**: Simplified framer-motion with performance-first approach
* **Caching Strategy**: Intelligent service worker caching with network-first and cache-first strategies
* **Redis Caching**: Production-ready Redis Cloud integration for session management and data caching
* **Logging System**: Environment-aware logging with file storage (dev) and console output (production)
* **Deployment**: Render with optimized caching strategies

---
