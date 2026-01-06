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
