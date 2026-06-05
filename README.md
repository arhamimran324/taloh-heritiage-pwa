# Taloh Heritage PWA

A modern Progressive Web Application (PWA) for hair order management and heritage documentation, built with React, TypeScript, and Vite.

## 🚀 Features

- **Progressive Web App** - Installable on desktop and mobile with offline support
- **Real-time Data Sync** - Powered by Supabase for seamless data synchronization
- **Modern UI** - Beautiful, responsive interface with Tailwind CSS and Radix UI components
- **Type-Safe Development** - Full TypeScript support for improved code quality
- **Fast Performance** - Optimized with Vite and React Compiler
- **Data Visualization** - Interactive charts and analytics with Recharts
- **Form Management** - Robust form handling with React Hook Form
- **State Management** - Efficient data fetching and caching with TanStack React Query

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern UI library
- **TypeScript** - Type-safe JavaScript
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Unstyled, accessible component primitives
- **Framer Motion** - Smooth animations

### Backend & Services
- **Supabase** - PostgreSQL database and authentication
- **TanStack React Query** - Data fetching and caching

### Developer Tools
- **ESLint** - Code quality linting
- **React Compiler** - Automatic rendering optimization
- **Vite PWA Plugin** - Progressive Web App support

## 📦 Dependencies Overview

| Category | Package | Version |
|----------|---------|---------|
| **UI Components** | `@headlessui/react`, `radix-ui` | ^2.2.9, ^1.4.3 |
| **Styling** | `tailwindcss`, `class-variance-authority` | ^4.2.1, ^0.7.1 |
| **Forms** | `react-hook-form` | ^7.71.2 |
| **Data Fetching** | `@tanstack/react-query` | ^5.90.21 |
| **Backend** | `@supabase/supabase-js` | ^2.98.0 |
| **Routing** | `react-router-dom` | ^7.13.1 |
| **Charts** | `recharts` | ^3.7.0 |
| **Animations** | `framer-motion` | ^12.34.5 |

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/arhamimran324/taloh-heritiage-pwa.git

# Navigate to project directory
cd taloh-heritiage-pwa

# Install dependencies
npm install
```

### Development

```bash
# Start development server with HMR
npm run dev
```

The application will be available at `http://localhost:5173`

### Building

```bash
# Create optimized production build
npm run build

# Preview production build locally
npm run preview
```

### Code Quality

```bash
# Run ESLint to check code quality
npm run lint
```

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Route pages
├── hooks/              # Custom React hooks
├── services/           # API and external service integrations
├── lib/                # Utility functions and helpers
├── store/              # State management (if applicable)
└── styles/             # Global styles and Tailwind config
```

## 🔐 Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 📱 PWA Capabilities

This application is a full PWA with:
- **Offline Support** - Works without internet connection
- **Installable** - Can be installed on desktop and mobile devices
- **App-like Experience** - Full-screen mode and native feel
- **Fast Loading** - Service worker caching for instant loads

To install:
1. Visit the application in your browser
2. Click the install button (varies by browser)
3. Or navigate to the app menu and select "Install"

## 🎨 Customization

### Tailwind CSS
Customize colors, spacing, and typography in `tailwind.config.js`

### Component Library
Pre-built components from Radix UI and Headless UI can be extended in the `components/` directory

### ESLint Configuration
Extend ESLint rules in `eslint.config.js` for stricter type-checking:

```js
import tseslint from 'typescript-eslint'

export default defineConfig([
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      tseslint.configs.strictTypeChecked,
    ],
  },
])
```

## 🚀 Performance Optimization

- **React Compiler** - Automatically memoizes components and values
- **Code Splitting** - Vite automatically splits code for optimal loading
- **Tree Shaking** - Unused code is automatically removed from builds
- **Image Optimization** - Integrate `vite-plugin-legacy` for older browser support

## 🤝 Contributing

1. Create a new branch for your feature: `git checkout -b feature/amazing-feature`
2. Commit your changes: `git commit -m 'Add amazing feature'`
3. Push to the branch: `git push origin feature/amazing-feature`
4. Open a Pull Request

## 📝 License

This project is private. All rights reserved.

## 🆘 Support

For issues, questions, or suggestions, please open an [issue](https://github.com/arhamimran324/taloh-heritiage-pwa/issues) on GitHub.

## 📚 Resources

- [React Documentation](https://react.dev)
- [Vite Documentation](https://vitejs.dev)
- [Supabase Documentation](https://supabase.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)

---

**Made with ❤️ for Taloh Heritage**
