# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
# ICGI — AI-Powered Patient Management System

ICGI is a full-stack patient management application designed to help users
view patient information and interact with an AI assistant for
patient-specific medical information and research.

## Features

- Patient management and patient profile viewing
- Role-based interface
- AI-powered chat assistant
- Patient-context-aware responses
- Medical information search using DuckDuckGo
- MongoDB database integration
- REST APIs using Express.js
- React-based frontend
- Responsive user interface

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Groq SDK
- DuckDuckGo Search

## Project Structure

```text
icgi-patient-management/
├── src/
│   ├── components/
│   ├── config/
│   ├── data/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── models/
├── routes/
├── scripts/
├── public/
├── server.js
├── package.json
└── vite.config.js
