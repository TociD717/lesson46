# Lesson 46 project

This is a simple React application built with Vite, TypeScript, and Redux Toolkit. It serves as a test project to learn a basic setup with state management and CSS styling.

## Features

- React with TypeScript for type-safe components.
- Redux Toolkit for state management.
- Vite as a fast build tool and development server.
- Basic CSS styling.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 16 or higher recommended)
- [Yarn](https://yarnpkg.com/) (package manager)

# Project Structure

```
lesson46/
├── dist/ # Production build output
├── src/ # Source code
│ ├── store/ # Redux store configuration
│ ├── App.tsx # Main application component
│ ├── main.tsx # Entry point
│ └── index.css # Global styles
├── types/ # TypeScript type declarations
│ └── css.d.ts # Declaration for CSS files
├── tsconfig.json # Root TypeScript configuration
├── tsconfig.app.json # TypeScript config for the app
├── tsconfig.node.json# TypeScript config for Node.js
├── vite.config.ts # Vite configuration
└── package.json # Project dependencies and scripts
```

## Scripts

yarn dev — Start the development server.
yarn run build — Build the project for production.
yarn preview — Preview the production build.
