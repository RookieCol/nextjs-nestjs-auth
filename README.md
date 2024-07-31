# NestJS + Next.js Authentication with Prisma

This repository demonstrates a monorepo setup using Turborepo, featuring NestJS for the backend, Next.js for the frontend, and Prisma as the ORM for database management. It provides a full-stack authentication system, including user registration and login.

## Features

- **Monorepo Structure**: Managed with Turborepo for efficient development and builds.
- **User Authentication**: Includes registration, login, and secure session management.
- **NestJS Backend**: API server handling authentication logic.
- **Next.js Frontend**: Client-side application for user interaction.
- **Prisma ORM**: Database schema and migrations management.
- **TypeScript**: Full-stack TypeScript for type safety.

## Monorepo Structure
``` basg
├── apps
│ ├── backend # NestJS backend
│ └── frontend # Next.js frontend
├── packages
│ ├── tsconfig # Shared TypeScript configurations
│ └── eslint-config-custom # Shared ESLint configurations
├── turbo.json # Turborepo configuration
└── package.json # Root package.json
```