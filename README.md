# Real Estate Hub

A team-built real estate web app where users can browse properties for sale or rent, search and filter listings, view property details, and sign up or sign in.

![Real Estate Hub preview](https://raw.githubusercontent.com/SaharMahmoudDev/SaharMahmoudDev.github.io/main/images/real-estate-hub-light.jpg)

**Live demo:** https://realestatehubteam.pages.dev/

## Features
- Buy and Rent listings fetched with TanStack Query
- Search and filters by location, price, type, bedrooms, bathrooms, and area
- Sorting by price, area, and date
- Page-based pagination on large screens, infinite scroll on mobile
- Property details page
- Sign up, sign in (including Google sign-in), and reset password
- Responsive layout for mobile, tablet, and desktop

## Tech Stack
React · Vite · TanStack Query · Zustand · Tailwind CSS · Material UI · Axios · Zod · React Router · json-server (mock API)

## My Role
- Owned the **Buy & Rent** pages: listing display, search, filters, and sorting
- Built responsive pagination with infinite scroll on mobile (`useLoadMore`)
- Managed filter state with **Zustand**
- Built the **auth pages**: sign up, sign in, reset password, and Google sign-in
- Built the AI chat page
- Used mock APIs ahead of backend integration

## Project Structure
```
src/
├── features/
│   ├── browser/   # Buy & Rent: components, hooks, api, store
│   ├── auth/      # Sign up, sign in, reset password
│   └── chatbot/
├── pages/
├── Components/
├── router/
└── hooks/
```

## Getting Started
```bash
npm install
npm run start:api   # mock API on port 5175
npm run dev
```
Create a `.env` file with `VITE_API_BASE_URL` and `VITE_GOOGLE_CLIENT_ID` (see `.env.example`).

## What I Learned
- Working in a team with branches, forks, and pull requests
- Server-state caching with TanStack Query and client state with Zustand
- Designing pagination that changes between desktop and mobile
