# Frontend Project README

This project is a frontend web application developed with **React**, **TypeScript**, and **Vite**. Its main purpose is to manage **user registration** and **login**, interacting with a backend service for authentication and other operations.


## 🚀 Link Production

https://68a69934c2778511a4eda598--rococo-profiterole-5ce870.netlify.app

## Getting Started

To run the project in your local development environment, follow these steps:

### 1. Environment Variables

This project connects to a backend. The backend host URL is configured via an environment variable. Create a `.env` file in the root of your project with the following format:

```dotenv
VITE_BACKEND_HOST=[https://back-github.arturoverbel.com](https://back-github.arturoverbel.com)
```

Make sure to replace https://back-github.arturoverbel.com with the actual URL of your backend API.

### 2. Install Dependencies
Navigate to the project's root directory and install all necessary dependencies:

```bash
npm install
```

### 3. Run the Project
Once the dependencies are installed, you can start the development server:

```bash
npm run dev
```
This will start the application in development mode, usually accessible at http://localhost:5173.

## ⚙️ Deployment
This project is configured for manual deployment using Netlify.

To deploy a new version:

1. Generate the production build:

```bash
npm run build
```
This command will create a dist/ folder with optimized files for production.

2. Manual deployment to Netlify:
Access your project's Netlify dashboard. Drag and drop the contents of the dist/ folder into the deployments section to update your site.

## 🛠️ Technologies Used
- React: JavaScript library for building user interfaces.
- TypeScript: A superset of JavaScript that adds static typing.
- Vite: Next-generation frontend build tool.

Thank you for checking out the project!