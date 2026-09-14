# Bibliotheca — Lebanon Online Bookstore

A Vite + React website for a physical-book online bookstore. UI supports English, Arabic (RTL), and French. Prices are in USD and orders open WhatsApp.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## GitHub + Vercel

1. Create a GitHub repository named `bibliotheca`.
2. Upload all files in this folder to the repository root.
3. Import the repository into Vercel.
4. Vercel detects Vite automatically. Build command: `npm run build`. Output directory: `dist`.

## Editing books

Open your deployed site and choose **Edit books** in the top-right. You can change title, author, category, price, description, best-seller status, and upload a cover photo.

Important: the current editor saves changes in the browser's localStorage. That means edits are local to the device/browser and are not a shared online database. For a real multi-device admin system, connect a database/CMS later.

## WhatsApp

The current order number is `+961 70 112 659`.
