# Healthspot

Healthspot is a healthcare provider discovery platform that helps users find, review, and receive updates about healthcare providers.

## Project Structure

This project is organized as a monorepo with two main components:

- [Frontend](/frontend) - Next.js application with Tailwind CSS and shadcn/ui components
- [Backend](/backend) - Node.js REST API with SQLite/Sequelize

## Getting Started

### Prerequisites
- Node.js 16+
- npm or pnpm

### Development Setup

1. Start the backend:
   ```bash
   cd backend
   npm install
   npm run dev
   ```

2. Start the frontend:
   ```bash
   cd frontend
   pnpm install
   pnpm dev
   ```

3. Visit http://localhost:3000 to see the application

## Features
- Provider search with filtering
- Review analysis with sentiment detection
- SMS notifications for provider updates
- Save favorite providers