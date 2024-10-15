# Webpack Project

This is a simple Webpack project that uses TypeScript and Sass for building a modular frontend. The project is set up to compile TypeScript into JavaScript and Sass into CSS.

## Project Setup

### Prerequisites

Ensure you have Node.js and npm installed on your machine.

1. [Install Node.js](https://nodejs.org/)

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/webpack-project.git
    cd webpack-project
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

### ⚙️ Development

To start the development server, run:

```bash
npm run serve
```

### 📦 Build

To Build the project, run:

```bash
npm run build
```

### 📂 Project Structure

```bash
webpack-project/
├── src/
│   ├── index.ts          # Main TypeScript entry file
│   ├── styles.scss       # Sass styles file
├── public/
│   ├── bundle.js         # Compiled JavaScript output
│   ├── app.css           # Compiled CSS output
├── webpack.config.js     # Webpack configuration file
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation
```

# 🔧 Webpack Configuration

The project uses Webpack to bundle TypeScript and Sass files. The configuration includes:

- **MiniCssExtractPlugin**: Extracts CSS from the JavaScript bundle and outputs it as a separate file.
- **ts-loader**: Loads and compiles TypeScript files.
- **sass-loader**: Compiles Sass to CSS.
- **css-loader**: Converts CSS into CommonJS modules for bundling.
