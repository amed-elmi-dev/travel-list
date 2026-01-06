<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# travel-list — Far Away 💼🏝️

A simple React + Vite app to build and manage a travel packing list. Add items (with quantity), toggle packed status, sort items, delete entries, clear the whole list, and view packing stats.

🚀 Features
Add items with description and quantity
Toggle packed status (strikethrough when packed)
Delete items and clear list (confirmation)
Sort by input order, description, or packed status
Live stats: total items, number packed, and percentage
Lightweight and easy to run locally
🧰 Tech stack
React 19
Vite
Plain CSS (see index.css)
🔧 Getting started
Prerequisites:

Node.js (recommended >= 16)
Commands:
# Install dependencies
npm install

# Start dev server
npm run dev
# Open http://localhost:5173

# Build for production
npm run build

# Preview production build locally
npm run preview

# Run linter
npm run lint

📁 Project structure (important files)
index.html — app entry
main.jsx — React entry
App.jsx — main app logic & state
index.css — styling
components
Logo.jsx — app title
Form.jsx — add-item form (quantity + description)
Item.jsx — single list item (checkbox + delete)
PackingList.jsx — list + sorting + clear action
Stats.jsx — footer with packing stats

ℹ️ Notes & suggestions
Current state is in-memory (no persistence). Consider adding localStorage or backend persistence if you want data to survive page reloads.
No tests included yet. Adding unit tests (Jest/React Testing Library) and a CI workflow would be a good next step.
ESLint is configured (npm run lint) — follow the existing lint rules.
🤝 Contributing
Fork -> branch -> PR
Please run npm run lint and ensure no lint errors before opening a PR.
Add short, focused commits and a descriptive PR message.
📜 License
MIT — replace with your preferred license and add a LICENSE file.
>>>>>>> 8edb061fdedc8ee30805ac9fbb16559cdec90326
