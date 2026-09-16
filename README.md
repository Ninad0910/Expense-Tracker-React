# Expense Tracker React

A React expense tracking application built to practice core React concepts including state management, routing, reusable components and persistent browser storage.

## Live Demo

https://expense-tracker-react-fundamentals.netlify.app/

## GitHub

https://github.com/Ninad0910/Expense-Tracker-React

## Features

- Add income and expenses
- Edit existing transactions
- Delete transactions
- Delete confirmation modal
- Category-based filtering
- Amount-range filtering
- Sorting
- Expense and income summaries
- Statistics dashboard
- Summary bar
- Dark mode
- Persistent data using localStorage
- Custom localStorage hook
- React Router navigation
- Lazy-loaded routes with Suspense
- React Portals for modal rendering
- Responsive interface

## Tech Stack

- React
- React Router
- Context API
- Tailwind CSS
- JavaScript
- localStorage

## Project Structure

The application is divided into reusable React components and uses React Context for shared expense-related state.

Routing is handled using React Router, while browser localStorage is used to persist application data between sessions.

## State Management

The application uses the React Context API to share expense-related data across components without passing the same state through multiple levels of props.

A custom localStorage hook is used to save and restore application data from the browser.

## Run Locally

Install dependencies:

```bash
npm install
