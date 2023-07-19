# 🚀 Basic Webpack Configuration with Typescript / Sass / TailwindCSS

This project is a basic setup for starting a Webpack project with Typescript, Sass, and TailwindCSS. It provides a basic structure and the necessary configuration files to quickly start development. It also support multiple index files.

## ⚙️ Prerequisites

Make sure you have the following prerequisites installed on your machine:

-  Node.js (version 18 or upper)

## 🏁 Getting Started

1. Clone the repository:

```shell
git clone https://github.com/MKlblangenois/webpack-typescript-tailwindcss-sass/tree/main
```

2. Install the dependencies:

```shell
yarn
```

3. Build the project:

```shell
yarn build
```

4. Start the development server:

```shell
yarn watch
```

## 📦 Project structure

```markdown
-  dist/
   -  index.min.js
   -  index.min.css
-  src/
   -  assets/
      -  scripts/
         -  editor.ts
         -  index.ts
      -  styles/
         -  app.scss
-  postcss.config.js
-  tailwind.config.js
-  tsconfig.json
-  webpack.config.js
```

-  dist/: The output directory for the bundled files.
-  src/: The source code directory.
-  index.ts: The entry point of your application.
-  styles/: The directory for your Sass stylesheets.
-  postcss.config.js: The PostCSS configuration file.
-  tailwind.config.js: The TailwindCSS configuration file.
-  tsconfig.json: The TypeScript configuration file.
-  webpack.config.js: The Webpack configuration file.

## 🛠️ Scripts

-  `yarn build`: Build the application for production.
-  `yarn build:dev`: Build the application for development.
-  `yarn watch`: Start the development server.

## 📄 License

This project is licensed under the MIT License.
Feel free to customize the content and instructions based on your specific project requirements.

## 👥 Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Make sure to follow the existing code style and guidelines. For major changes, it's recommended to discuss them first by creating an issue to communicate and coordinate with the project maintainers.

Please ensure that you provide a detailed description of your changes and any necessary steps to test them. Also, make sure that your contributions align with the project's goals and scope.

We appreciate your support and involvement in making this project better!
