# 🔓 AIUNLOCKED

AIUNLOCKED is a blazing-fast, Vite-powered web application designed to deliver next-gen AI tools and user experiences. This project is built with modern JavaScript tooling, fully integrated with Firebase Hosting, and CI/CD-automated via CircleCI.

---

## 🚀 Tech Stack

- ⚡ [Vite](https://vitejs.dev/) — lightning-fast frontend tooling
- 🔥 [Firebase Hosting](https://firebase.google.com/docs/hosting) — secure & scalable deployment
- 🧪 Jest / Vitest — unit and integration testing
- 🔁 CircleCI — continuous integration and delivery
- 💡 TailwindCSS (optional) — utility-first styling

---

## 📁 Project Structure

```bash
.
├── public/             # Static assets
├── src/                # Application source code
│   ├── assets/         # Images and fonts
│   ├── components/     # Reusable UI components
│   ├── views/          # Route-level views
│   └── main.ts         # App entry point
├── .circleci/          # CircleCI config
│   └── config.yml
├── .gitignore
├── firebase.json
├── vite.config.ts
├── tsconfig.json
├── package.json
└── README.md

✅ Setup Instructions

1. Clone the Repository
git clone https://github.com/Boomchainlab/aiunlocked.git
cd aiunlocked


2. Install Dependencies
npm install


3. Start Development Server
npm run dev

4. Build for Production
npm run build

🚦 Continuous Integration & Deployment

This repo is powered by CircleCI.

🔄 CI Pipeline (.circleci/config.yml)

The following jobs run on every push:
	•	✅ Install dependencies
	•	🧹 Lint the codebase
	•	🧪 Run unit tests
	•	🏗️ Build the project
	•	🚀 Deploy to Firebase (on main branch)

To configure deployment:
	1.	Generate a Firebase CI token:
firebase login:ci

2.	Add it to CircleCI → Project Settings > Environment Variables:
FIREBASE_TOKEN=your_generated_token

📡 Deploy to Firebase (Manual)
npm install -g firebase-tools
firebase deploy


Configure your firebase.json and projectId accordingly.

⸻

📬 Feedback & Support

For issues, suggestions, or feature requests, open an issue or contact:

📧 support@boomchainlab.com
🔗 https://boomchainlab.com

⸻

© License

This project is licensed under the MIT License.
