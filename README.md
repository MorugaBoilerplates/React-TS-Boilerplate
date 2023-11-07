# React TypeScript Boilerplate

This is a boilerplate for building React applications using TypeScript.

## Features

- React 17+
- TypeScript 4+
- ESLint for code linting
- Prettier for code formatting
- Husky for Git hooks
- lint-staged for running scripts on staged files
- GitHub Actions for CI/CD

## Getting Started

First, clone the repository and install the dependencies:

```bash
git clone https://github.com/MorugaBoilerplates/React-TS-Boilerplate>
cd React-TS-Boilerplate
yarn install
```

To start the development server:

```bash
yarn start
```

To build the project for production:

```bash
yarn build
```

## Scripts

- `yarn start`: Run the app in development mode.
- `yarn build`: Build the app for production to the `build` folder.
- `yarn test`: Launch the test runner in the interactive watch mode.
- `yarn eject`: This will remove the single build dependency from your project.
- `yarn lint`: Run ESLint for all TypeScript and JavaScript files.
- `yarn format`: Run Prettier to format all your code.

## Husky Setup

To set up Husky for Git hooks, run:

```bash
yarn husky install
```

## Contributing

Contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
