# 3D Portfolio

Interactive portfolio website built with React, Three.js, and Vite.  
It showcases Dipankar's profile, skills, projects, and contact form with a 3D-first user experience.

## Project Information

- **Name:** `3d-portfolio`
- **Version:** `0.0.0`
- **App Type:** React SPA
- **Build Tool:** Vite
- **Package Manager:** npm
- **Deployment Target:** Vercel

## Tech Stack

- **Core:** React, React Router DOM, Vite
- **3D:** Three.js, React Three Fiber, React Three Drei
- **Animation:** React Spring (`@react-spring/three`)
- **Styling:** Tailwind CSS, PostCSS, Autoprefixer
- **Contact:** EmailJS (`@emailjs/browser`)
- **Other UI:** React Vertical Timeline Component
- **Code Quality:** ESLint

## Features

- Interactive 3D home scene (island, sky, bird, plane)
- Responsive scaling for 3D objects on smaller screens
- Multi-page navigation (`/`, `/about`, `/projects`, `/contact`)
- Skills and experience sections
- Projects showcase page
- Contact form powered by EmailJS
- Optional background music toggle on the home page

## Project Structure

```text
Dipankar_portfolio/
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── vercel.json
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── components/
│   ├── pages/
│   ├── models/
│   ├── hooks/
│   ├── constants/
│   └── assets/
└── public/
```

## Getting Started

### Prerequisites

- Node.js 16+ (recommended: latest LTS)
- npm

### Installation

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

Default local URL: `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Environment Variables

To enable the contact form, create a `.env` file in the project root:

```env
VITE_APP_EMAILJS_SERVICE_ID=your_service_id
VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
```

## Routing

- `/` -> Home
- `/about` -> About
- `/projects` -> Projects
- `/contact` -> Contact

## Deployment

This project is configured for Vercel deployment via `vercel.json`.

Typical flow:

1. Push your code to GitHub.
2. Import the repository into Vercel.
3. Configure environment variables in Vercel.
4. Deploy.

## Browser Support

- Modern browsers with ES2020+ support
- WebGL support required for 3D rendering

## Maintainer

- **Owner:** Dipankar
- **Role:** Front-End Developer and UI/UX Designer
- **Location:** India

---

**Last Updated:** April 2026  
**Status:** Active development
