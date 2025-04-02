# Healthspot Frontend

Next.js application for the Healthspot healthcare provider platform.

## Tech Stack
- Next.js
- Tailwind CSS
- shadcn/ui components
- API connection to Healthspot backend

## Setup

### Prerequisites
- Node.js 16+
- pnpm

### Environment Variables
Create a `.env.local` file with:
```
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

### Installation
```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build
```

## Project Structure
- `/app` - Next.js application routes
- `/components` - Reusable React components
- `/hooks` - Custom React hooks including API integration
- `/lib` - Utility functions and API client
- `/public` - Static assets
- `/styles` - Global CSS and theme definitions