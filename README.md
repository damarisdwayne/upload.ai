# Application Documentation

## Overview

The application is an innovative platform that seamlessly merges a cutting-edge React frontend with a robust Node.js backend, delivering an exceptional data upload and analysis experience. We've harnessed the power of advanced technologies and a myriad of libraries to craft this state-of-the-art solution, boasting a tech stack that includes Shadcn, Tailwind, Radix, Prisma, fs, Dotenv, Fastify, Fastify CORS, OpenAI, Zod, Vite, TypeScript, Lucide React, and clsx.

But here's where it gets really cool - our platform leverages the limitless potential of artificial intelligence. It's not just another tool; it's your creative companion. With our AI capabilities, we empower users to effortlessly generate captivating titles and captivating video descriptions. Gone are the days of wracking your brain for the perfect wording – our AI does it for you, making your content shine.

Welcome to the future of content creation, where technology meets creativity, and your ideas come to life with the click of a button. Say goodbye to writer's block and hello to a world of limitless possibilities. This is more than a platform; it's your creative partner in the digital realm.

### Frontend

#### Directory Structure

- `src/`: Contains the frontend application source code files.
- `public/`: Contains public files, such as icons and images.
- `package.json`: Node.js project configuration file.
- `tsconfig.json`: TypeScript configuration file.
- `vite.config.js`: Vite configuration, the bundler used for development.

#### Dependencies

The main dependencies of the frontend include:

- `react` and `react-dom`: React libraries for building user interfaces.
- `tailwindcss`: A CSS framework for styling.
- `clsx`: A library for working with CSS classes conditionally.
- `lucide-react`: An SVG icon library.
- `@radix-ui/react-*`: A set of UI components for creating rich interfaces.
- `@vitejs/plugin-react`: A Vite plugin for React support.

#### Scripts

- `dev`: Starts the Vite development server.
- `build`: Compiles the project for production.
- `lint`: Runs ESLint linter to check for code style and quality issues.
- `preview`: Starts a preview server for production files.

### Backend

#### Directory Structure

- `src/`: Contains the backend source code files.
- `package.json`: Node.js project configuration file.
- `tsconfig.json`: TypeScript configuration file.

#### Dependencies

The main dependencies of the backend include:

- `@fastify/cors`: A Fastify plugin for handling CORS (Cross-Origin Resource Sharing).
- `@fastify/multipart`: A Fastify plugin for processing multipart/form-data.
- `@prisma/client`: The Prisma client for database access.
- `fastify`: A lightweight web framework for Node.js.
- `openai`: A library for integrating with the OpenAI platform.
- `zod`: A library for data validation in TypeScript.
- `prisma`: An ORM library for interacting with the database.

#### Scripts

- `dev`: Starts the development server using `tsc watch` to automatically compile TypeScript code during development.

## Configuration

To set up the application, follow these steps:

1. Clone the application's repository to your local machine.

2. In the project's root directory, install the frontend and backend dependencies by running the `npm install` or `yarn install` command.

3. Configure the necessary environment variables. For the backend, check the `.env` file to set environment variables such as API keys and database settings.

## Usage

To start the application, follow these steps:

1. In the project's root directory, run `npm run dev` to start the frontend development server.

2. Next, navigate to the `backend` directory and run `npm run dev` to start the backend development server.

3. Access the application in your browser via the local address specified by the frontend development server.
