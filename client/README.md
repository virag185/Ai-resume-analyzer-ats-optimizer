# ResumeMatch: AI Resume Analyzer & ATS Optimizer

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6)

ResumeMatch is a full-stack AI-powered web application designed to help job seekers bypass Applicant Tracking Systems (ATS) by optimizing their resumes. Built with a modern tech stack and premium UI, the application intelligently compares resumes against job descriptions, identifies missing keywords, and suggests actionable, quantifiable improvements to bullet points.

## 🌟 Core Features

- **ATS Score Calculator**: Provides a visual Gauge score out of 100 based on keyword matches, formatting, and action verbs.
- **Keyword Gap Analysis**: Instantly highlights missing essential keywords from the provided Job Description.
- **AI Bullet Point Enhancer**: Rewrites weak resume bullet points into data-oriented, powerful achievements.
- **Drag-and-Drop Parsing**: Clean, modern interface supporting instant PDF parsing.

## 🛠️ Tech Stack
- **Frontend & API Routes:** Next.js (App Router), React
- **Styling:** Tailwind CSS, Framer Motion (for micro-animations), Lucide Icons
- **File Parsing:** `pdf-parse`, internal `ArrayBuffer` handling built natively for Next.js.
- **AI Integration:** OpenAI API (`gpt-3.5-turbo`)

## 🚀 Getting Started Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/resume-analyzer.git
   cd resume-analyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env.local` file at the root of your project:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🔗 Deployment

This application is fully optimized to be deployed instantly on [Vercel](https://vercel.com/new).

## 📄 License
This project is licensed under the MIT License.
