### README.md

# Chrome Extension Boilerplate

A modern boilerplate for developing Chrome extensions using **React**, **TypeScript**, and **Material-UI (MUI)**. This project provides a strong foundation for building powerful and user-friendly Chrome extensions.

## Features

- **React** for building interactive UIs.
- **TypeScript** for type safety and better developer experience.
- **Material-UI (MUI)** for consistent and customizable UI components.
- **Hot Reloading** for a seamless development experience.
- **Optimized Build** for efficient production deployment.
- **Manifest V3** compatibility.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Beydox/react-ts-mui-ext-boilerplate.git
   

2. Navigate to the project directory:
   ```bash
   cd react-ts-mui-ext-boilerplate
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Development

Start the development server with hot reloading:

```bash
npm run dev
# or
yarn dev
```

### Build

To create a production build of your extension:

```bash
npm run build
# or
yarn build
```

The build will be located in the `dist` folder.

### Load the Extension in Chrome

1. Open Chrome and go to `chrome://extensions/`.
2. Enable "Developer mode" in the top right corner.
3. Click "Load unpacked" and select the `dist` folder.

## Project Structure

```
chrome-extension-boilerplate/
├── src/              # Source code
│   ├── background/   # Folder with background.ts
│   ├── contentScript/# Folder with contentScript.ts
│   ├── options/      # All files related to the options page
│   ├── popup/        # All files related to the popup window
│   ├── static/       # Static files (e.g., icons, manifest.json)
├── dist/             # Production build
├── package.json      # Project configuration
├── package.json      # Project configuration
├── package.json      # Project configuration
├── webpack.common.js # Webpack configuration file for shared settings
├── webpack.dev.js    # Webpack configuration file for development-specific settings
├── webpack.prod.js   # Webpack configuration file for production-specific settings
└── tsconfig.json     # TypeScript configuration

```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the extension for production.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you encounter any problems or have suggestions for improvements.

## License

This project is licensed under the [MIT License](./LICENSE).


---

Happy coding! 🚀
```

