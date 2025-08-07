# MetaLytics - Metallurgical Process Optimization System

## Project Overview
MetaLytics is a comprehensive web application for steel production quality optimization using artificial intelligence and machine learning. The system provides real-time process parameter analysis, simulation capabilities, and automated optimization for metallurgical processes.

## Architecture
- **Frontend**: React with TypeScript, Tailwind CSS, Wouter for routing
- **Backend**: Express.js with TypeScript
- **Build System**: Vite with HMR (Hot Module Replacement)
- **UI Components**: Radix UI primitives with shadcn/ui styling
- **Charts**: Chart.js with react-chartjs-2
- **Icons**: Lucide React icons
- **State Management**: React hooks with localStorage persistence

## Key Features
1. **Dashboard**: Real-time parameter input and quality prediction
2. **Simulation**: ML-based process simulation with multiple scenarios
3. **Optimization**: Automated parameter optimization using algorithms
4. **Comparison**: Side-by-side scenario comparison
5. **Results**: Comprehensive reporting and data export
6. **Multilingual**: Portuguese/Spanish language support
7. **Dark/Light Theme**: Responsive theme switching

## Recent Changes
- **2025-01-06**: Successfully migrated from Bolt to Replit environment
- **2025-01-06**: Maximum logo size improvements for ultimate brand visibility and impact:
  - Navbar icon: h-6 → h-20, text: xl → 5xl  
  - Component headers: h-6 → h-32 (Glossary, Help, Results, Simulation)
  - Optimization component: h-6 → h-36
  - Dashboard logo: h-12 → h-40
  - Presentation top logo: Factory icon → MetaLytics logo (h-45, removed circle background)
- **2025-01-06**: Fine-tuned presentation logo through iterations (h-55 → h-50 → h-45) based on user feedback
- **2025-01-07**: Fixed logo loading issue for deployed website:
  - Used Vite asset import system for proper deployment compatibility
  - Added logo to `/src/assets/metalyics-logo.svg` and imported as ES module
  - Updated Presentation component to use imported asset instead of static path
  - This ensures logo loads correctly in both development and production builds
- **2025-01-06**: Fixed TypeScript errors in Glossary component (Set iteration)
- **2025-01-06**: Installed missing dependencies: chart.js, react-chartjs-2

## User Preferences
- Request: Maximum logo visibility - company brand should be prominent and impactful
- Emphasis on professional metallurgical industry standards
- Portuguese language as primary interface language
- Brand logos should be significantly larger than typical for strong visual presence

## Technical Details
- Server runs on port 5000
- Uses in-memory storage (MemStorage) for data persistence
- Professional ML model with realistic metallurgical parameters
- Responsive design with mobile support
- Progressive Web App capabilities

## Development Status
✅ Migration from Bolt to Replit completed
✅ Dependencies installed and verified
✅ Logo visibility improvements implemented
✅ Application running successfully