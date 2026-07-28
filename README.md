# Money Guard - React Financial Tracker

Money Guard is a financial management web application built with React, Redux Toolkit, and Vite.

## Architecture & Responsibilities

- **`dev-Duygu`**: Authentication (Register, Login, Token Refresh), Private & Public Routes, Navigation, Header, Balance & Currency components.
- **`dev-Kayra`**: Transactions Management (Add, Edit, Delete), Financial Statistics & Category Charts, Transaction Modals.

## Features & Modules

### Transactions & Statistics (`dev-Kayra`)
- **Add & Edit Modals**: Formik / React Hook Form validation with Yup schemas for transaction management.
- **Category Doughnut Chart**: Visual summary breakdown powered by `Chart.js` and `react-chartjs-2`.
- **Transaction History**: Real-time sorted table view with formatted currency and dates.

## Tech Stack
- **Frontend**: React 18, Vite, React Router v6
- **State Management**: Redux Toolkit, Redux Persist
- **Styling**: CSS Modules, Modern Normalize
- **Form & Validation**: React Hook Form, Yup
- **Charts & UI**: Chart.js, React ChartJS 2, React Datepicker, React Icons
