# 360° Booth Website

A futuristic website for 360° and selfie booth business targeting weddings and corporate events. Features a dark glowing aesthetic with neon accents, smooth animations, and immersive user experience.

## Features

- 🎥 Full-screen video background showcasing booth experiences
- 📱 Responsive design optimized for all devices
- ✨ Futuristic UI with neon glow effects and glass morphism
- 🎨 Interactive camera lens logo navigation
- 📋 Comprehensive booking form for event planning
- 🖼️ Gallery showcase of previous events
- 🎯 Service packages for different event types

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS v4 with custom design system
- **Animations**: Motion (Framer Motion successor)
- **Build Tool**: Vite
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js 16+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/360-booth-website.git
cd 360-booth-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

## Deployment

### Build for Production

```bash
npm run build
```

### Deploy to Vercel

1. Push your code to GitHub
2. Connect your GitHub repository to [Vercel](https://vercel.com)
3. Vercel will automatically build and deploy your site

### Deploy to Netlify

1. Build your project: `npm run build`
2. Drag and drop the `dist` folder to [Netlify](https://netlify.com)
3. Or connect your GitHub repository for continuous deployment

## Project Structure

```
├── components/           # React components
│   ├── ui/              # Reusable UI components
│   └── figma/           # Figma-specific components
├── styles/              # Global styles and CSS
├── public/              # Static assets
└── guidelines/          # Development guidelines
```

## Design System

The website uses a custom futuristic design system with:

- **Colors**: Dark theme with cyan (#00d4ff) primary accent
- **Typography**: 14px base size with consistent 1.5 line height
- **Effects**: Neon glow, glass morphism, and smooth animations
- **Components**: Custom UI components with consistent styling

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
