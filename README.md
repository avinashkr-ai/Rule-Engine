## Rule Engine ⚙️
A flexible rule engine enabling dynamic decision-making through a user-friendly interface and API.

[![JSON](https://img.shields.io/badge/JSON-504KB-yellow)](https://www.json.org/json-en.html)
[![TypeScript](https://img.shields.io/badge/TypeScript-4KB-blue)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-5KB-yellow)](https://www.javascript.com/)
[![HTML](https://img.shields.io/badge/HTML-19KB-red)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-0KB-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Angular](https://img.shields.io/badge/Angular-Framework-red)](https://angular.io/)
[![Express.js](https://img.shields.io/badge/Express.js-Framework-brightgreen)](https://expressjs.com/)

This project implements a rule engine with both a user interface built using Angular and a backend API built with Express.js. It provides functionalities for creating, combining, and evaluating rules based on defined conditions. The architecture includes API endpoints for managing rules and a frontend for user interaction.

## 📋 Summary

This Rule Engine project allows users to define and evaluate rules dynamically. The key capabilities include defining rules, combining them, and evaluating them against given data. It's designed for scenarios where decision-making needs to be flexible and easily configurable.

The project uses a combination of technologies. The front end is built with Angular, providing a rich user interface. The backend uses Express.js for handling API requests. It also incorporates technologies such as Kubernetes, React, Vue.js, and NumPy for various aspects of the system.

## ✨ Features

- 📝 **Rule Creation**: Allows users to define new rules with specific conditions.
- 🔀 **Rule Combination**: Enables combining existing rules to create more complex logic.
- ✅ **Rule Evaluation**: Evaluates rules against provided data to determine outcomes.
- 🖥️ **User Interface**: Provides an intuitive interface for managing and interacting with rules.
- ⚙️ **API Endpoints**: Offers API endpoints for programmatic access to rule engine functionalities.

## 🛠️ Tech Stack

**Languages & Frameworks:**
- **JSON** - 8 files (504KB)
- **TypeScript** - 8 files (4KB)
- **JavaScript** - 8 files (5KB)
- **HTML** - 2 files (19KB)
- **CSS** - 2 files (0KB)

**Key Technologies:**
- **Frameworks**: Angular, Express.js, Kubernetes, React, Vue.js, NumPy
- **Build Tools**: 
- **Databases**: PostgreSQL, SQLite, Oracle, MySQL
- **Testing**: None detected

**Dependencies** (53 total):
- `@angular/animations`
- `@angular/common`
- `@angular/compiler`
- `@angular/core`
- `@angular/forms`
- `@angular/platform-browser`
- `@angular/platform-browser-dynamic`
- `@angular/platform-server`
- `@angular/router`
- `@angular/ssr`
- `express`
- `rxjs`
- `tslib`
- `zone.js`
- `@angular-devkit/build-angular`

## 🚀 Project Setup

**Prerequisites:**
- Node.js
- npm (Node Package Manager)
- Angular CLI

**Installation:**
```bash
# Install dependencies for the UI
cd RuleEngineUI
npm install

# Install dependencies for the API
cd ../RuleEngineAPI
npm install
```

**Configuration:**
The application uses the following environment variables:
- `protocol`
- `originalUrl`
- `port`
- `PORT`

These variables can be configured in your environment or within the application's configuration files.

**Available Scripts:**
```bash
# In RuleEngineUI directory
ng serve
ng build
ng build --watch --configuration development
node dist/rule-engine-ui/server/server.mjs
```

The following npm scripts are available:
- `ng`: ng
- `start`: ng serve
- `build`: ng build
- `watch`: ng build --watch --configuration development
- `test`: echo "Error: no test specified" && exit 1
- `serve:ssr:RuleEngineUI`: node dist/rule-engine-ui/server/server.mjs

## 📁 Project Structure

```text
📁 Rule-Engine/
├── 📁 RuleEngineAPI/
│   ├── 📁 config/
│   │   ├── 🟨 config.js
│   │   └── 🟨 database.js
│   ├── 📁 controllers/
│   │   └── 🟨 ruleController.js
│   ├── 📁 models/
│   │   └── 🟨 ruleModel.js
│   ├── 📁 routes/
│   │   └── 🟨 ruleRoutes.js
│   ├── 📁 services/
│   │   └── 🟨 ruleService.js
│   ├── 📁 utils/
│   │   └── 🟨 astParser.js
│   ├── 🚫 .gitignore
│   ├── 🟨 app.js
│   ├── 📦 package.json
│   └── 📊 package-lock.json
├── 📁 RuleEngineUI/
│   ├── 📁 src/
│   │   ├── 📁 app/
│   │   │   ├── 🎨 app.component.css
│   │   │   ├── 🌐 app.component.html
│   │   │   ├── 🔷 app.component.spec.ts
│   │   │   ├── 🔷 app.component.ts
│   │   │   ├── 🔷 app.config.server.ts
│   │   │   ├── 🔷 app.config.ts
│   │   │   └── 🔷 app.routes.ts
│   │   ├── 📄 favicon.ico
│   │   ├── 🌐 index.html
│   │   ├── 🔷 main.server.ts
│   │   ├── 🔷 main.ts
│   │   └── 🎨 styles.css
│   ├── 🚫 .gitignore
│   ├── 📦 package.json
│   ├── 📊 angular.json
│   ├── 📊 package-lock.json
│   ├── 🔷 server.ts
│   ├── 📊 tsconfig.app.json
│   ├── 📊 tsconfig.json
│   └── 📊 tsconfig.spec.json
└── 📁 Task/
    └── 📄 Zeotap Intern Assignment.pdf
```

**Key Directories:**
- `RuleEngineAPI`: Contains the backend API built with Express.js.
    - `config`: Database and application configuration files.
    - `controllers`: Handles request logic.
    - `models`: Defines data models.
    - `routes`: Defines API routes.
    - `services`: Contains business logic.
    - `utils`: Utility functions, including an AST parser.
    - `app.js`: Main application entry point.
- `RuleEngineUI`: Contains the frontend application built with Angular.
    - `src/app`: Angular components, services, and modules.
    - `src/index.html`: Main HTML file.
    - `src/main.ts`: Main TypeScript file for the application.
    - `server.ts`: Server-side rendering configuration.
    - `angular.json`: Angular CLI configuration file.
    - `tsconfig.json`: TypeScript configuration file.

## 👥 Author and Support

**Author Information:**
- Repository owner: **avinashkr-ai**
- Project: **Rule-Engine**
- GitHub: [https://github.com/avinashkr-ai](https://github.com/avinashkr-ai)

**Contributing:**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear, descriptive messages.
4. Submit a pull request.

**Support:**
For any issues or questions, please open an issue on the GitHub repository.

**License:**
License: Not specified. All rights reserved.