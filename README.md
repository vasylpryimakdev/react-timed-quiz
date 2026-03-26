# ReactQuiz

An interactive quiz application built with React and Vite, featuring timed multiple-choice questions with immediate feedback and comprehensive results analysis.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## ✨ Features

- ⏱️ **Timed Questions**: Each question has a countdown timer with auto-skip functionality
- ✅ **Instant Feedback**: Immediate visual feedback on answer selection
- 🔀 **Randomized Answers**: Answer order is shuffled for each question
- 📊 **Detailed Results**: Comprehensive summary with performance metrics
- 🎯 **Responsive Design**: Optimized for desktop and mobile devices
- 🚀 **Fast Development**: Built with Vite for rapid development and optimized builds

## 🚀 Demo

[Live Demo](https://react-quiz-puce-tau.vercel.app/)

## 📸 Screenshots

### Welcome Screen

![Start Game](./public/screenshots/start-game.png)
_The initial screen where users can start the quiz_

### Question Interface

![Answer State](./public/screenshots/answer-state.png)
_Question display with multiple-choice answers and timer_

### Results Summary

![Game Over](./public/screenshots/game-over.png)
_Final results screen with performance breakdown_

## 🛠️ Tech Stack

- **Frontend Framework**: React 19 with functional components and hooks
- **Build Tool**: Vite for fast development and optimized production builds
- **Programming Language**: JavaScript (ES6+) with JSX
- **Code Quality**: ESLint for linting and code standards
- **Styling**: CSS with modern responsive design principles

## 📋 Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/vasylpryimakdev/react-timed-quiz.git
   cd react-quiz
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:5173` to view the application.

## 📜 Available Scripts

| Command           | Description                          |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the development server         |
| `npm run build`   | Build the project for production     |
| `npm run lint`    | Run ESLint for code quality checks   |
| `npm run preview` | Preview the production build locally |

## 📁 Project Structure

```
react-quiz/
├── public/
│   └── screenshots/          # Application screenshots
├── src/
│   ├── assets/               # Static assets (images, icons)
│   ├── components/           # React components
│   │   ├── Answers.jsx       # Answer options component
│   │   ├── Header.jsx        # Application header
│   │   ├── Question.jsx      # Question display component
│   │   ├── QuestionTimer.jsx # Timer component
│   │   ├── Quiz.jsx          # Main quiz logic
│   │   └── Summary.jsx       # Results summary component
│   ├── questions.js          # Quiz questions data
│   ├── App.jsx               # Main application component
│   ├── main.jsx              # Application entry point
│   └── index.css             # Global styles
├── package.json              # Dependencies and scripts
├── vite.config.js            # Vite configuration
└── README.md                 # Project documentation
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
