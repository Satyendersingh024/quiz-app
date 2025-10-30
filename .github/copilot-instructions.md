# Quiz App AI Agent Instructions

## Project Overview
This is a React-based Quiz application built with Vite. The project uses modern React (v19) and follows a component-based architecture.

## Tech Stack
- React 19.0.0
- Vite 4.4.5
- ESLint for code quality
- React Strict Mode enabled

## Project Structure
```
Quiz App/
├── public/
│   └── quiz-logo.png
├── src/
│   ├── assets/
│   ├── App.jsx         # Main application component
│   ├── main.jsx        # Application entry point
│   └── index.css       # Global styles
├── index.html          # Entry HTML file
├── package.json        # Dependencies and scripts
└── vite.config.js      # Vite configuration
```

## Development Workflow
1. Start development server:
```bash
npm run dev
```

2. Build for production:
```bash
npm run build
```

3. Preview production build:
```bash
npm run preview
```

4. Lint code:
```bash
npm run lint
```

## Key Conventions
- React Strict Mode is enforced for better development experience
- ESLint is configured with React-specific rules and hooks validation
- Project uses ES modules (type: "module" in package.json)

## Important Integration Points
- Application mounts to `#root` element in index.html
- Assets are served from the public directory
- CSS imports are supported in JavaScript files

## Note
This appears to be a new or starter project. As the codebase grows, update these instructions with:
- Component patterns and best practices
- State management approaches
- Testing conventions
- New scripts and workflows
- Additional tooling and configurations