# Let me Ask 🚀

A modern React-based room management application that allows users to create and join interactive rooms. Built with cutting-edge technologies and best practices.

## ✨ Features

- **Room Management**: Create and join rooms with unique identifiers
- **Real-time Updates**: Built with React Query for efficient data fetching and caching
- **Modern UI**: Beautiful interface built with Tailwind CSS and Radix UI components
- **Type Safety**: Full TypeScript support for better development experience
- **Responsive Design**: Works seamlessly across all devices
- **Dark Mode**: Built-in dark theme support

## 🛠️ Tech Stack

- **Frontend Framework**: React 19 with TypeScript
- **Build Tool**: Vite for fast development and optimized builds
- **Styling**: Tailwind CSS v4 with custom design system
- **UI Components**: Radix UI primitives with class-variance-authority
- **State Management**: TanStack Query for server state management
- **Routing**: React Router DOM v7
- **Code Quality**: Biome for linting and formatting
- **Icons**: Lucide React for beautiful, consistent icons

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/let-me-ask.git
   cd let-me-ask
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the application running.

### Backend Setup

This application requires a backend API running on `http://localhost:3333`. Make sure your backend server is running and provides the following endpoints:

- `GET /rooms` - Returns a list of available rooms

## 📁 Project Structure

```
src/
├── components/
│   └── ui/           # Reusable UI components
│       └── button.tsx
├── lib/
│   └── utils.ts      # Utility functions
├── pages/
│   ├── create-room.tsx  # Room creation and listing page
│   └── room.tsx         # Individual room view
├── app.tsx           # Main application component
├── main.tsx          # Application entry point
└── index.css         # Global styles
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🎨 UI Components

The project uses a custom design system built with:
- **Tailwind CSS v4** for utility-first styling
- **Radix UI** for accessible component primitives
- **class-variance-authority** for component variants
- **clsx** and **tailwind-merge** for conditional styling

## 🔧 Configuration

### Vite Configuration
The project is configured with Vite for optimal development experience:
- React plugin for JSX support
- Tailwind CSS plugin for styling
- Path aliases for cleaner imports (`@/` points to `src/`)

### Code Quality
- **Biome** for linting and formatting
- **Ultracite** configuration for consistent code style
- TypeScript for type safety

## 🌐 API Integration

The application integrates with a backend API to manage rooms:

```typescript
// Example API response structure
type Room = {
  id: string
  name: string
}
```

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service like:
- Vercel
- Netlify
- GitHub Pages
- AWS S3

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Rocketseat](https://rocketseat.com.br/) for the amazing learning platform
- All the open-source contributors who made this tech stack possible

---

Made with ❤️ by Filipe 