# thealfred.dev

A modern portfolio website built with [Astro](https://astro.build) 🚀

## 🌟 Features

- ⚡️ Lightning-fast performance with Astro
- 📱 Fully responsive design
- 🎨 Modern gradient UI with smooth animations
- 🧩 Component-based architecture
- 📦 Zero JavaScript by default
- 🎯 SEO optimized

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Hero.astro
│   │   ├── Projects.astro
│   │   └── Skills.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                       |
| :--------------------- | :------------------------------------------- |
| `npm install`          | Installs dependencies                        |
| `npm run dev`          | Starts local dev server at `localhost:4321`  |
| `npm run build`        | Build your production site to `./dist/`      |
| `npm run preview`      | Preview your build locally, before deploying |

## 📝 License

ISC

## 🚢 Deployment

This Astro site can be deployed to various platforms:

### Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify
```bash
# Build command
npm run build

# Publish directory
dist
```

### GitHub Pages
Add to `astro.config.mjs`:
```js
export default defineConfig({
  site: 'https://thealfred.dev',
  base: '/',
});
```

Then build and deploy the `dist` folder.

## 🎨 Customization

Edit the components in `src/components/` to customize:
- **Hero.astro** - Update name and tagline
- **About.astro** - Modify personal information
- **Skills.astro** - Add/remove skills and proficiency levels
- **Projects.astro** - Showcase your own projects
- **Contact.astro** - Update contact links