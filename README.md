<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Modern React Starter

A production-ready React + Vite starter template with Tailwind CSS v4, TypeScript, and modern tooling.

View your app in AI Studio: https://ai.studio/apps/drive/1EA4Dif6LC3cRncRIefT08Uf7jRyQDAAI

## Features

- ⚡ **Vite** - Next generation frontend tooling with instant HMR
- ⚛️ **React 19** - Latest React with modern hooks
- 🎨 **Tailwind CSS v4** - Utility-first CSS framework with PostCSS integration
- 📘 **TypeScript** - Full type safety support
- 🔌 **lucide-react** - Beautiful, consistent icon library
- 🚀 **Production-Ready** - Optimized for build and deployment

## Tech Stack

- **Framework**: React 19
- **Build Tool**: Vite 6
- **Styling**: Tailwind CSS v4 (with PostCSS)
- **Language**: TypeScript
- **Icons**: lucide-react
- **Package Manager**: npm

## Project Structure

```
├── src/
│   └── index.css          # Tailwind CSS entry point
├── components/            # React components
│   ├── Button.tsx
│   ├── FeatureGrid.tsx
│   ├── Footer.tsx
│   ├── Header.tsx
│   └── Hero.tsx
├── App.tsx                # Main application component
├── index.tsx              # React entry point
├── index.html             # HTML template
├── tailwind.config.js     # Tailwind configuration
├── postcss.config.js      # PostCSS configuration
├── vite.config.ts         # Vite configuration
└── package.json           # Dependencies and scripts
```

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd startup0
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key (if using AI features)

### Development

Start the development server with hot module replacement:

```bash
npm run dev
```

The app will be available at `http://localhost:3000`

### Build for Production

Create an optimized production build:

```bash
npm run build
```

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
```

## Customization

### Tailwind Configuration

Customize colors and theme in `tailwind.config.js`:

```javascript
theme: {
  extend: {
    colors: {
      primary: '#4f46e5',
      secondary: '#10b981',
      dark: '#0f172a',
    }
  }
}
```

### Environment Variables

Create a `.env.local` file in the root directory:

```
GEMINI_API_KEY=your_api_key_here
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run preview` - Preview production build

## Browser Support

This project is configured to work with modern browsers including Chrome, Firefox, Safari, and Edge.

## Security

The development server includes Content Security Policy (CSP) headers configured for development. For production deployment, ensure to:
- Review and adjust CSP headers appropriately
- Remove `unsafe-eval` and `unsafe-inline` directives where possible
- Implement proper security headers

## Learn More

- [React Documentation](https://react.dev)
- [Vite Documentation](https://vitejs.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [TypeScript Documentation](https://www.typescriptlang.org)

## License

This project is open source and available under the MIT License.
