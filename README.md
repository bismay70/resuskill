<div align="center">
  <div>
    <img alt="Static Badge" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
        <img src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
        <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
    <img alt="Static Badge" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">
  </div>

  <h3 align="center">Resuskill - AI Resume Analyzer</h3>

   <div align="center">
     Intelligent Resume Analysis Platform with AI-Powered Job Matching
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. � [How to Use](#getting-started)

## <a name="introduction">✨ Introduction</a>

**Resuskill** is an intelligent, AI-powered Resume Analyzer platform built with modern web technologies. It enables job seekers to upload their resumes, analyze them against job descriptions, receive actionable feedback, and get ATS (Applicant Tracking System) scores. The platform leverages cutting-edge AI to provide personalized recommendations for resume optimization, helping candidates stand out in competitive job markets.

Built with React, React Router, and Puter.js, Resuskill provides a seamless, privacy-first experience where authentication and data storage happen entirely in the browser. No backend setup required—just upload, analyze, and improve!

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[React](https://react.dev/)** is a popular open‑source JavaScript library for building user interfaces using reusable components and a virtual DOM, enabling efficient, dynamic single-page and native apps.

- **[React Router v7](https://reactrouter.com/)** is the go‑to routing library for React apps, offering nested routes, data loaders/actions, error boundaries, code splitting, and SSR support—all with a smooth upgrade path from v6.

- **[Puter.com](https://puter.com/)** is an advanced, open-source internet operating system designed to be feature-rich, exceptionally fast, and highly extensible. Puter can be used as: A privacy-first personal cloud to keep all your files, apps, and games in one secure place, accessible from anywhere at any time.

- **[Puter.js](https://puter.com/library)** is a tiny client‑side SDK that adds serverless auth, storage, database, and AI (GPT, Claude, DALL·E, OCR…) straight into your browser app—no backend needed and costs borne by users.

- **[Tailwind CSS](https://tailwindcss.com/)** is a utility-first CSS framework that allows developers to design custom user interfaces by applying low-level utility classes directly in HTML, streamlining the design process.

- **[TypeScript](https://www.typescriptlang.org/)** is a superset of JavaScript that adds static typing, providing better tooling, code quality, and error detection for developers, making it ideal for building large-scale applications.

- **[Vite](https://vite.dev/)** is a fast build tool and dev server using native ES modules for instant startup, hot‑module replacement, and Rollup‑powered production builds—perfect for modern web development.

- **[Zustand](https://github.com/pmndrs/zustand)** is a minimal, hook-based state management library for React. It lets you manage global state with zero boilerplate, no context providers, and excellent performance through selective state subscriptions.

## <a name="features">🔋 Features</a>

👉 **Easy & Convenient Authentication**: Secure, browser-based authentication using Puter.js—no backend required, no email configurations needed.

👉 **Resume Upload & Cloud Storage**: Upload, organize, and store multiple resumes securely in the cloud with instant access from any device.

👉 **AI-Powered Resume Analysis**: Analyze your resume against specific job descriptions to identify missing keywords and skill gaps.

👉 **ATS Score Calculation**: Get real-time ATS (Applicant Tracking System) scores that show how well your resume matches job requirements.

👉 **Smart AI Feedback**: Receive personalized, actionable recommendations to optimize your resume for specific job listings.

👉 **PDF Resume Support**: Seamlessly upload and process PDF resumes with automatic text extraction and analysis.

👉 **Job Matching Engine**: Compare your resume against job descriptions with intelligent keyword matching and relevance scoring.

👉 **Resume Preview & Details**: View detailed resume information with a clean, organized interface showing all extracted content.

👉 **Modern, Responsive UI**: Built with Tailwind CSS for a sleek, professional design that works perfectly on all devices—desktop, tablet, and mobile.

👉 **Reusable Component Architecture**: Leverage modular, well-structured components for easy maintenance and future feature additions.

👉 **Privacy-First Design**: Your data stays with you. All processing happens in the browser with no personal data sent to external servers.

👉 **One-Click Resume Wipe**: Easily clear all stored resumes and start fresh whenever you want.

👉 **Dark Mode Support**: Comfortable viewing experience with beautiful dark and light theme options.

And many more features including code architecture, performance optimization, and extensibility for future enhancements.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/bismay70/resuskill.git
cd resuskill
```
**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

**Project Structure Overview**

- `app/` - Main application components and routes
  - `components/` - Reusable React components (Resume Card, Score Badge, ATS, etc.)
  - `routes/` - Route handlers for authentication, home, resume, upload, and wipe functionality
  - `lib/` - Utility functions for PDF processing and Puter integration
- `types/` - TypeScript type definitions
- `constants/` - Application constants
- `public/` - Static assets including PDF worker and icons

## <a name="getting-started">📚 How to Use Resuskill</a>

1. **Sign In**: Create an account or sign in using browser-based authentication
2. **Upload Resume**: Click the upload button and select your PDF resume
3. **Add Job Description**: Paste or upload a job description you want to target
4. **Get Analysis**: Instantly receive:
   - ATS score showing compatibility percentage
   - Missing keywords and skills
   - Personalized recommendations for optimization
   - Detailed feedback on how to improve your resume
5. **Download & Apply**: Use the insights to improve your resume and apply with confidence


