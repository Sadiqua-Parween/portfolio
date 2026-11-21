# Sadiqua Parween - Portfolio

> A modern, responsive personal portfolio with a monolithic architecture: frontend UI, micro-backend engine, in-browser REST API dispatcher, and LocalStorage database are completely self-contained in a single page.

## 🚀 Features

- **Self-Contained Architecture**: Frontend and mock micro-backend in a single file (`index.html`).
- **Interactive Terminal (CLI)**: Type commands directly (`help`, `skills`, `projects`, `status`, `api /api/stats`, `hire`).
- **In-Browser Backend & DevTools**:
  - Simulated REST API routes (`GET /api/stats`, `GET /api/skills`, `GET /api/projects`, `GET /api/guestbook`, `POST /api/contact`, etc.)
  - Real-time traffic logger with simulated latency and status codes
  - LocalStorage database inspector and JSON export
- **Interactive Guestbook**: Visitors can post notes that persist in the browser's database.
- **Contact Pipeline**: Form validation, simulated dispatch, and inbox management.
- **Modern UI**: Tailwind CSS, Lucide icons, glassmorphism design, celebratory confetti, and Dark/Light theme toggle.

## 💻 Quick Start

Simply open `index.html` in any modern web browser:

```bash
# On macOS
open index.html

# Or serve locally with Python
python3 -m http.server 8000
```
