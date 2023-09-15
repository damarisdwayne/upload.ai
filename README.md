# Application Documentation

## Overview

Welcome to the future of content creation! Our innovative platform combines a powerful React front-end with a robust Node.js back-end to provide an exceptional upload and data analysis experience to help users be more creative in creating names and descriptions for their videos. With AI capabilities at its core, it's more than just a tool; is your creative companion. Say goodbye to writer's block and hello to limitless possibilities.

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
- `ai`: A library that provides a wide range of artificial intelligence capabilities, including natural language processing, machine learning, and more. It empowers our application to automatically generate titles and video descriptions, making content creation more efficient and creative.

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
- `ai`: The same AI library used on the frontend, enabling powerful AI features on the backend as well.

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
