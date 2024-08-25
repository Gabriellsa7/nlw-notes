# Notes Website

## Description

This is a simple and intuitive notes website where users can add, edit, and delete notes. It is designed to help users remember important tasks, ideas, or anything they need to keep track of. The website provides a clean and responsive interface for easy note management.

## Features

- **Add Notes:** Users can quickly add new notes to remember tasks, ideas, or important information.
- **Edit Notes:** Users can easily edit existing notes to update information.
- **Delete Notes:** Users can remove notes that are no longer needed.

## Technologies Used

- **ReactJS:** A JavaScript library for building user interfaces.
- **Vite:** A fast build tool and development server for modern web projects.
- **TypeScript:** A typed superset of JavaScript that helps with writing more robust code.
- **Tailwind CSS:** A utility-first CSS framework for creating custom designs easily.

## Setup

### Prerequisites

- Node.js and npm/yarn installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Gabriellsa7/nlw-notes.git

## React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

- If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
