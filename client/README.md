# Openbox Client

The React frontend for [Openbox](../README.md), an open-source cloud storage platform. Built with React and Vite.

## 🛠️ Tech Stack

- [React](https://react.dev/)
- [Vite](https://vite.dev/) for dev server and build tooling
- [Oxlint](https://oxc.rs/docs/guide/usage/linter) for linting

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- The Openbox backend running (see the [server setup](../README.md#-getting-started))

### Setup

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Set up environment variables**

   Copy `.env.example` to `.env` and fill in the values:

   ```bash
   cp .env.example .env
   ```

   ```env
   VITE_API_URL=http://localhost:5000
   ```

   `VITE_API_URL` must point to your running backend.

3. **Start the dev server**

   ```bash
   npm run dev
   ```

4. Open `http://localhost:5173` in your browser.

## 📜 Scripts

| Command           | Description                          |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the development server (HMR)   |
| `npm run build`   | Create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |

Check `package.json` for the full list of scripts, including linting.

## 📂 Folder Structure

```
client/
├── public/          # Static files
├── src/
│   ├── assets/      # Images and static assets
│   ├── components/  # Reusable UI components
│   ├── hooks/       # Custom React hooks
│   ├── pages/       # Page-level components
│   ├── App.jsx      # Root component
│   ├── index.css    # Global styles
│   └── main.jsx     # App entry point
├── .env.example     # Example environment variables
├── index.html
└── vite.config.js
```

## 🤝 Contributing

See the [main README](../README.md#-contributing) for contribution guidelines.