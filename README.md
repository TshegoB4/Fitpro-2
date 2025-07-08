# Multi-Purpose Web Application

A comprehensive web application featuring fitness tracking, task management, and developer portfolio showcase. Built with modern web technologies for optimal performance and user experience.

## 🌟 Features

### 🏋️ Fitness & Health Tracking
- **Workout Tracker**: Real-time exercise logging with timers and progress monitoring
- **Nutrition Management**: Comprehensive calorie and macro tracking with water intake monitoring
- **Progress Analytics**: Visual charts and performance insights to track your fitness journey
- **Achievement System**: Goal setting, milestone tracking, and streak monitoring

### ✅ Professional Todo System
- **Task Management**: Hierarchical tasks with dependencies and recurring task support
- **Smart Prioritization**: Eisenhower Matrix integration with custom priority levels
- **Analytics & Reports**: Detailed productivity insights and completion metrics
- **Collaboration Tools**: Team features and shared task management

### 👨‍💻 Developer Portfolio
- **Interactive 3D Elements**: Three.js powered animations and visual effects
- **Project Showcase**: Featured developments and technical achievements
- **Professional Profile**: Skills, education, and contact information display

## 🚀 Live Demo

- **GitHub Repository**: [View Source Code](https://github.com/TshegoB4/Fitpro-2)
- **Live Application**: [https://tshegoB4.github.io/Fitpro-2](https://tshegoB4.github.io/Fitpro-2)

## 🛠️ Technologies Used

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with custom design system
- **UI Components**: shadcn/ui component library
- **3D Graphics**: Three.js with React Three Fiber
- **State Management**: React Query (TanStack Query)
- **Routing**: React Router DOM
- **Charts & Analytics**: Recharts
- **Form Handling**: React Hook Form with Zod validation
- **Icons**: Lucide React
- **Notifications**: Sonner (toast notifications)

## 📦 Installation

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/TshegoB4/Fitpro-2.git
   cd Fitpro-2
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🏗️ Project Structure

```
src/
├── components/           # Reusable UI components
│   ├── ui/              # shadcn/ui components
│   ├── profile/         # User profile components
│   └── [feature]/       # Feature-specific components
├── pages/               # Application pages/routes
│   ├── FitnessLanding.tsx
│   ├── HealthFitnessApp.tsx
│   ├── TodoApp.tsx
│   ├── Portfolio.tsx
│   └── NotFound.tsx
├── hooks/               # Custom React hooks
├── lib/                 # Utility functions
├── types/               # TypeScript type definitions
└── index.css           # Global styles and design tokens
```

## 🎨 Design System

The application uses a custom design system built with Tailwind CSS:
- **Semantic Color Tokens**: HSL-based color system for consistent theming
- **Responsive Design**: Mobile-first approach with breakpoint-specific layouts
- **Component Variants**: Flexible component system using class-variance-authority
- **Dark/Light Mode**: Theme switching support (can be extended)

## 📱 Available Routes

- `/` - Landing page with app overview
- `/app` - Main fitness and health application
- `/todo` - Professional todo management system
- `/portfolio` - Developer portfolio showcase
- `/profile` - User profile management

## 🚀 Deployment

### Deploy with Lovable
1. In the Lovable editor, click the **Publish** button
2. Your app will be available at `https://yourproject.lovable.app`

### Deploy with Netlify/Vercel
1. Build the project: `npm run build`
2. Deploy the `dist` folder to your preferred hosting platform

### Deploy with GitHub Pages
1. Install GitHub Pages deployment package:
   ```bash
   npm install --save-dev gh-pages
   ```
2. Add deployment scripts to `package.json`:
   ```json
   {
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d dist"
     }
   }
   ```
3. Deploy: `npm run deploy`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **GitHub Repository**: [https://github.com/TshegoB4/Fitpro-2](https://github.com/TshegoB4/Fitpro-2)
- **Live Application**: [https://tshegoB4.github.io/Fitpro-2](https://tshegoB4.github.io/Fitpro-2)
- **Issues**: [GitHub Issues](https://github.com/TshegoB4/Fitpro-2/issues)

## 📧 Contact

For questions or support, please reach out via:
- GitHub Issues
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

