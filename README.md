# Portfolio — Yuda Muhamad

Personal portfolio website built with HTML and Tailwind CSS.

## Prerequisites

- Node.js (v16+)
- npm

## Install

```bash
npm install
```

## Run Locally

**1. Build CSS (watch mode):**
```bash
npx tailwindcss -i ./src/input.css -o ./dist/css/main.css --watch
```

**2. Open in browser:**

Open `index.html` directly, or serve it with:
```bash
npx serve .
```

Then visit `http://localhost:3000`.

## Build for Production

```bash
npx tailwindcss -i ./src/input.css -o ./dist/css/main.css --minify
```
