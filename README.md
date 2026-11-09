# Shopwise: E-Commerce Store with Admin Panel

React + Vite + Tailwind CSS v4 + React Router. Data and authentication come from the free DummyJSON API.

## Run Locally

```bash
npm install
npm run dev
```

## Demo

[Click here to view the live application](https://react-js-ecommerce-application.vercel.app/)

## Deployment

Vercel/Netlify: Import the repository (or drag the project folder).

- Build command: `npm run build`
- Output directory: `dist`

SPA redirects are already configured.

## Demo Logins

- **Admin:** `emilys` / `emilyspass`
- **Customer:** `michaelw` / `michaelwpass`

## Features

- Login with JWT authentication
- Protected and role-based routes
- Shopping cart using useReducer and localStorage
- Product search
- Category filtering
- Product sorting
- Pagination
- Form validation
- Loading skeletons
- Error handling with retry
- Responsive UI
- Admin product add/delete functionality