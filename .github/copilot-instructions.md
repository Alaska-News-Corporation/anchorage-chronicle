# Copilot Instructions — Alaska News Site

## Project Context
This is an Alaska-themed news/media website built with React + Vite + TypeScript + TailwindCSS.

## Architecture
- **Frontend**: React 18+, Vite, TypeScript, TailwindCSS
- **Components**: shadcn/ui component library
- **Build**: `npm run build` or `bun run build`
- **Deploy**: Static site / GitHub Pages

## Code Style
- TypeScript strict mode
- Functional React components with hooks
- TailwindCSS utility classes
- Import from `@/components/` path alias

## Guidelines
- Prioritize readability and content hierarchy
- Article pages must have proper meta/OG tags for social sharing
- Responsive typography (clamp-based sizing)
- Accessible markup (semantic HTML, ARIA)
- Never commit API keys or secrets
- Fast load times — lazy load images below fold
