````md
# David Ren — Portfolio Website (React)

A responsive portfolio website built with React and Vite to present projects, technical skills, and experience in computer engineering.

## Key Capabilities

- Responsive layout optimized for desktop and mobile
- Client-side routing with React Router
- Production builds via Vite for fast local development and optimized output
- UI motion/interaction using Anime.js
- Skills and metrics visualization using Apache ECharts
- Project browsing with filtering and project detail modals
- Contact form with client-side validation
- Particle/visual background effects

## Technology Stack

- React 18
- React Router
- Vite
- Tailwind CSS
- Anime.js
- Apache ECharts
- Splide.js

## Requirements

- Node.js v16+ (recommended: latest LTS)
- npm or yarn

## Setup

Install dependencies:

```bash
npm install
````

Run the development server:

```bash
npm run dev
```

Open the URL printed in your terminal (commonly `http://localhost:5173` for Vite).

## Production Build

Build:

```bash
npm run build
```

Output is generated in the `dist/` directory.

Preview the production build locally:

```bash
npm run preview
```

## Project Layout

```text
├── src/
│   ├── components/              Reusable UI components
│   │   ├── Navigation.jsx
│   │   ├── Footer.jsx
│   │   └── ParticleBackground.jsx
│   ├── pages/                   Route-level pages
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   └── Contact.jsx
│   ├── hooks/                   Custom React hooks
│   │   └── useScrollAnimation.js
│   ├── App.jsx                  Application root / route setup
│   ├── main.jsx                 Entry point
│   └── index.css                Global styles
├── public/                      Static assets served as-is
│   └── resources/               Images and media
├── index.html                   HTML template
├── package.json                 Scripts and dependencies
├── vite.config.js               Vite configuration
└── tailwind.config.js           Tailwind configuration
```

## Routes

* `/` — Home: hero, featured projects, skills overview
* `/about` — About: background, education, experience timeline
* `/projects` — Projects: project showcase with filtering and modals
* `/contact` — Contact: contact form and contact details

## Configuration and Content Updates

### Tailwind theme

Adjust the color palette in `tailwind.config.js`:

```js
colors: {
  primary: "#0066ff",
  secondary: "#6b7280",
  success: "#10b981",
}
```

### Page content

Update content in the page components:

* `src/pages/Home.jsx`
* `src/pages/About.jsx`
* `src/pages/Projects.jsx`
* `src/pages/Contact.jsx`

## License

© 2025 David Ren. All rights reserved.

```
::contentReference[oaicite:0]{index=0}
```
