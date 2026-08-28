# 🛍️ I-Shopping Site

A modern shopping/e-commerce web application built with **React, TypeScript, Vite, Tailwind CSS, and Google Gemini AI**.

This project was created and developed using **Google AI Studio** and can be opened and continued directly from the Google AI Studio environment.

## ✨ Features

- 🛍️ Modern shopping interface
- 📦 Product browsing
- 🔎 Product/search experience
- 🤖 Google Gemini AI integration
- ⚡ Fast Vite development environment
- 🎨 Responsive UI with Tailwind CSS
- ✨ Smooth animations with Motion
- 🧩 Reusable React components
- 💡 Lucide React icons
- 🔐 Environment-variable based Gemini API configuration
- 📱 Responsive design for desktop and mobile

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | Frontend UI |
| TypeScript | Type-safe development |
| Vite | Development & build tool |
| Tailwind CSS | Styling |
| Google Gemini API | AI functionality |
| `@google/genai` | Gemini SDK |
| Motion | Animations |
| Lucide React | Icons |
| Express | Server-side support |
| dotenv | Environment variables |
| npm | Package management |

## 📁 Project Structure

```text
i-shopping-site/
│
├── src/
│   ├── components/
│   ├── context/
│   ├── data/
│   ├── services/
│   ├── types/
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
│
├── .env.example
├── .gitignore
├── index.html
├── metadata.json
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/flerkenstudio/i-shopping-site.git
cd i-shopping-site
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure Gemini API

Create a `.env.local` file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Replace `your_gemini_api_key` with your Gemini API key.

**Never commit your API key to GitHub.**

### 4. Start the development server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## 🏗️ Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 🔍 Type Checking

```bash
npm run lint
```

## 🤖 Google AI Studio

This project was created with **Google AI Studio** and uses Google's Gemini ecosystem for AI functionality.

### Open the project in Google AI Studio

https://ai.studio/apps/681cfbf7-0901-43bd-9c8c-f8c32fcbf650

### Google AI Studio

https://aistudio.google.com/

## 🔑 Environment Variables

The application uses environment variables for sensitive configuration.

Example:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Keep `.env.local` private and never upload API keys or other secrets to GitHub.

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run preview` | Preview production build |
| `npm run lint` | Run TypeScript checking |
| `npm run clean` | Remove generated build/server files |

## 🌐 Development

### Frontend

```text
React
TypeScript
Vite
Tailwind CSS
```

### AI

```text
Google Gemini
@google/genai
Google AI Studio
```

### UI

```text
Lucide React
Motion
```

### Server / Configuration

```text
Express
dotenv
```

## 🔒 Security

- Never expose your Gemini API key in source code.
- Never commit `.env.local`.
- Use environment variables for secrets.
- Do not share API keys in screenshots, issues, pull requests, or public repositories.

## 📌 Project Status

This is an actively developed shopping-site project. Features and implementation may change as the application evolves.

## 👨‍💻 Author

**flerkenstudio**

GitHub:  
https://github.com/flerkenstudio

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

## 📄 License

Add your preferred open-source license here if you intend to distribute the project publicly.

---

**Built with React + TypeScript + Google Gemini + Google AI Studio.**

Prompt → Build → Test → Improve 🚀
