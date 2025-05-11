# 🛠 Project Structure Setup

This project uses a structured folder layout inside the `src` directory for better modularity and maintainability.

## 📁 Windows CMD Setup

Run the following commands in Command Prompt to create the necessary folders and starter files:

```cmd
mkdir api\src\auth
mkdir api\src\config
mkdir api\src\constants
mkdir api\src\controller
mkdir api\src\middleware
mkdir api\src\services
mkdir api\src\models
mkdir api\src\routes
mkdir api\src\utils
type nul > api\src\app.js
type nul > api\src\index.js
```

## 📂 Directory Structure

```
src/
├── auth/         → Authentication strategies and logic
├── config/       → Configuration files (e.g., DB, env, server)
├── constants/    → Reusable constants (e.g., messages, status codes)
├── controller/   → Route controllers (business logic entry point)
├── middleware/   → Express middlewares (e.g., error handling, auth)
├── services/     → Service layer (logic shared across controllers)
├── models/       → Database models/schemas (e.g., Mongoose/Sequelize)
├── routes/       → API route definitions
├── utils/        → Utility functions and helpers
├── app.js        → Express app configuration
└── index.js      → Entry point to start the server

```

> You can now begin building your application within this organized structure.
