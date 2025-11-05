# Animated React App

A modern React application built to practice **Framer Motion**, **React Router**, and **Context API**.  
The app provides a clean interface for exploring and managing challenges with smooth page transitions and animated interactions.

---

## Features

- Multi-page navigation using **React Router**
- Scroll and page animations powered by **Framer Motion**
- Global state management with **Context API**
- Filter challenges by status: _Active_, _Completed_, _Failed_
- Responsive and minimal UI

---

## Tech Stack

- **React (Vite)**
- **Framer Motion**
- **React Router DOM**
- **Context API**
- **CSS Modules**

---

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## How It Works

The Welcome Page features parallax scroll animations using useScroll and useTransform.

Navigation to the Challenges Page happens via React Router.

The Challenges Page uses Context API for managing challenge data and Framer Motion for entry/exit animations.

Users can switch between tabs (Active / Completed / Failed) with smooth animated transitions.
