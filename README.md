# Vite React TypeScript TailwindCSS Boilerplate

This repository is a boilerplate for building a frontend application using Vite, React, TypeScript, and TailwindCSS. It includes ESLint, Prettier, and Husky pre-commit hooks for code quality and consistency.

## Features

- **Vite**: Fast build tool and development server.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **ESLint**: A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
- **Prettier**: An opinionated code formatter.
- **Husky**: Git hooks made easy.

## Prerequisites

- [Node.js](https://nodejs.org/en/) (v18 or above)
- [npm](https://www.npmjs.com/) (v9 or above)

## Getting Started

1. **Clone the repository:**

   ```sh
   git clone https://github.com/codingunda/vite-react-ts-tailwind-boilerplate.git
   cd vite-react-ts-tailwind-boilerplate
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Start the development server:**

   ```sh
   npm run dev
   ```

   The development server will be running at `http://localhost:5173`.

## Available Scripts

- **`npm run dev`**: Starts the development server.
- **`npm run build`**: Builds the app for production.
- **`npm run preview`**: Serves the production build.
- **`npm run lint`**: Runs ESLint to check for linting errors.
- **`npm run prepare`**: Setup husky.
- **`npm run format`**: Formats code using Prettier.

## Project Structure

```
.
├── .husky
│   └── pre-commit
├── .vscode
│   └── settings.json
├── public
│   └── favicon.svg
├── src
│   ├── assets
│   │   ├── styles.css
│   ├── app.tsx
│   └── main.tsx
├── .eslintignore
├── .eslintrc.js
├── .gitignore
├── .lintstagedrc
├── .prettierignore
├── .prettierrc.js
├── index.html
├── LICENSE
├── package.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.js
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Code Quality

This project uses ESLint for linting and Prettier for code formatting. Husky is used to run pre-commit hooks to ensure code quality before committing changes.

- **ESLint**: Configured to work with TypeScript and React.
- **Prettier**: Configured to format code on save and before commits.
- **Husky**: Runs linting and formatting checks before committing code.

## Contributing

If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Husky](https://typicode.github.io/husky/#/)

---

Enjoy building your Vite React TypeScript TailwindCSS application!

---

Happy coding!
