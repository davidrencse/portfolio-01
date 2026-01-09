# David Ren - Portfolio Website (React)

A modern, responsive portfolio website built with React.js showcasing projects, skills, and experience in computer engineering.

## Features

- 🎨 Modern, sleek design with smooth animations
- 📱 Fully responsive across all devices
- ⚡ Fast performance with Vite build tool
- 🎭 Interactive animations using Anime.js
- 📊 Skills visualization with ECharts
- 🎯 Project filtering and detailed modals
- 📝 Contact form with real-time validation
- 🌊 Particle background effects

## Tech Stack

- **React 18** - UI framework
- **React Router** - Client-side routing
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Anime.js** - Animation library
- **ECharts** - Data visualization
- **Splide.js** - Carousel component

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

The production build will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
├── src/
│   ├── components/      # Reusable components
│   │   ├── Navigation.jsx
│   │   ├── Footer.jsx
│   │   └── ParticleBackground.jsx
│   ├── pages/           # Page components
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   └── Contact.jsx
│   ├── hooks/           # Custom React hooks
│   │   └── useScrollAnimation.js
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── public/              # Static assets
│   └── resources/       # Images and media
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
└── tailwind.config.js   # Tailwind configuration
```

## Pages

- **Home** (`/`) - Hero section, featured projects, skills overview
- **About** (`/about`) - Personal story, education, experience timeline
- **Projects** (`/projects`) - Interactive project showcase with filtering
- **Contact** (`/contact`) - Contact form and information

## Customization

### Colors

Edit `tailwind.config.js` to customize the color scheme:

```javascript
colors: {
  'primary': '#0066ff',
  'secondary': '#6b7280',
  'success': '#10b981',
}
```

### Content

Update the content in each page component:
- `src/pages/Home.jsx` - Homepage content
- `src/pages/About.jsx` - About page content
- `src/pages/Projects.jsx` - Projects data
- `src/pages/Contact.jsx` - Contact information

## License

© 2025 David Ren. All rights reserved.





