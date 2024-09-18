# Next.js and NestJS Monorepo

This project demonstrates a monorepo setup combining Next.js for the frontend and NestJS for the backend. It's designed to provide insights on how to structure and manage a full-stack TypeScript application using these two powerful frameworks.

## Project Structure

- `apps/frontend`: Next.js application
- `apps/backend`: NestJS application
- Root level configuration for the monorepo

## Description

This monorepo showcases:

- A Next.js frontend with Tailwind CSS for styling
- A NestJS backend API
- Concurrent development of both frontend and backend
- Shared configuration and dependencies management

## Getting Started

### Prerequisites

- Node.js (version 14 or later recommended)
- npm or yarn

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/shaqdeff/another-juan.git
   cd another-juan
   ```

2. Install dependencies:
   ```shell
   npm install
   ```

### Running the Development Environment

To start both frontend and backend concurrently:

```shell
npm run dev
```

- This command utilizes the script defined in the root `package.json` file to run the `dev` script in both `apps/frontend` and `apps/backend` directories.

### Accessing the Applications

- Frontend: http://localhost:3000
- Backend: http://localhost:3001

## Frontend (Next.js)

The frontend is a Next.js application with Tailwind CSS for styling. It includes:

- Custom font configuration (Geist Sans and Geist Mono)
- Responsive design
- Dark mode support

Key files:

- `apps/frontend/src/app/page.tsx`: Main page component
- `apps/frontend/src/app/layout.tsx`: Root layout with font and metadata configuration
- `apps/frontend/tailwind.config.ts`: Tailwind CSS configuration

## Backend (NestJS)

The backend is a NestJS application providing a simple API. Key files:

- `apps/backend/src/main.ts`: Entry point
- `apps/backend/src/app.module.ts`: Root module
- `apps/backend/src/app.controller.ts`: Main controller
- `apps/backend/src/app.service.ts`: Service with business logic

## Deployment

Refer to the respective documentation for deploying Next.js and NestJS applications:

- [Next.js Deployment Documentation](https://nextjs.org/docs/deployment)
- [NestJS Deployment Documentation](https://docs.nestjs.com/fundamentals/lifecycle-events#application-shutdown)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
