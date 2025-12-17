🧠 AI Resume Builder
An ATS‑friendly, AI‑powered resume builder built with TypeScript, Vite, and Google Gemini.

📌 Overview
AI Resume Builder helps users generate clean, professional, and ATS‑optimized resumes using the Gemini API. The app provides a simple UI, modular architecture, and fast development workflow.

This project is based on the official AI Studio template and can be run locally or deployed anywhere.


✨ Features
🤖 AI‑generated resume content using Gemini

✅ ATS‑friendly templates

⚡ Fast Vite development environment

🧩 Component‑based architecture

🎨 Clean, minimal UI

🔑 Environment‑based API key configuration

🛠️ Tech Stack

Technology	Purpose
TypeScript	Core logic & type safety
Vite	Build tool & dev server
React	UI components
Gemini API	AI text generation
HTML / CSS	Layout & styling
📁 Project Structure
~~
AI-Resume-builder/
│
├── components/          # UI components
├── hooks/               # Custom React hooks
├── services/            # Gemini API service logic
├── templates/           # Resume templates
├── App.tsx              # Main application component
├── index.tsx            # App entry point
├── index.html           # Root HTML file
├── constants.ts         # Static values & config
├── metadata.json        # App metadata
├── types.ts             # TypeScript types
├── package.json         # Dependencies & scripts
├── tsconfig.json        # TypeScript config
└── vite.config.ts       # Vite configuration
~
▶️ Getting Started
1. Clone the repository
bash
git clone https://github.com/BuhlaluseNgcobo/AI-Resume-builder
cd AI-Resume-builder
2. Install dependencies
bash
npm install
3. Add your Gemini API key
Create a .env.local file in the project root:

Code
GEMINI_API_KEY=your_key_here
4. Run the development server
bash
npm run dev
Your app will be available at a local development URL (usually http://localhost:5173).

🚀 Deployment
This project can be deployed to any static hosting provider (Vercel, Netlify, GitHub Pages, etc.).

Build the production bundle:

bash
npm run build
Then deploy the dist/ folder.

📌 Future Enhancements
Add multiple resume templates

Add export to PDF

Add user profile storage

Add drag‑and‑drop resume sections

Add dark mode

Add AI‑powered job‑matching suggestions

🤝 Contributing
Contributions are welcome. Feel free to fork the repo and submit pull requests.
