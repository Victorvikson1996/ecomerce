# React E-Commerce Course Using Fake Store API

Welcome to the React E-Commerce Course where you'll build an e-commerce web application using React. This course will guide you through using React, Redux Toolkit/React Query for state management, Firebase/Supabase for authentication, and Paystack for payment processing. This hands-on project will help you learn and apply your skills in real-world web application development.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Technologies Used](#technologies-used)
- [Setting Up](#setting-up)
- [Building the Application](#building-the-application)
  - [Product Display](#product-display)
  - [Shopping Cart](#shopping-cart)
  - [User Authentication](#user-authentication)
  - [Checkout Process](#checkout-process)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)

## Prerequisites

Before you start, make sure you have the following installed:

- Node.js and npm
- A code editor like Visual Studio Code

## Technologies Used

- [React](https://reactjs.org/docs/getting-started.html)
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started) / [React Query](https://react-query.tanstack.com/overview)
- [Firebase](https://firebase.google.com/docs/web/setup) / [Supabase](https://supabase.io/docs)
- [Paystack](https://paystack.com/docs/payments/accept-payments)
- [React Router](https://reactrouter.com/web/guides/quick-start)
- [Tailwind CSS](https://tailwindcss.com/docs)

## Setting Up

Start by setting up your project environment:

```bash
npx create-react-app my-ecommerce-app
cd my-ecommerce-app
npm install @reduxjs/toolkit react-redux firebase supabase-js @supabase/supabase-js react-router-dom @tailwindcss/postcss7-compat tailwindcss@npm:@tailwindcss/postcss7-compat autoprefixer@^9
```

# React E-Commerce Application Using Fake Store API

This project guide covers the development of a React-based e-commerce application, leveraging technologies such as Redux Toolkit/React Query for state management, Firebase/Supabase for user authentication, Paystack for payment processing, and Tailwind CSS for styling.

## Building the Application

### Product Display

**Objective**: Create components to display products fetched from the Fake Store API. Display product details such as name, price, and category in a clean and interactive format.

- **React Components**: Utilize functional components to display product information.
- **API Integration**: Fetch data using custom hooks or Redux Toolkit slices.

### Shopping Cart

**Objective**: Implement a shopping cart where users can add and remove products, managing the cart's state efficiently across the application.

- **State Management**: Use Redux Toolkit or React Query to manage the shopping cart state.
- **Interactive Features**: Add interactive buttons for adding and removing items from the cart.

### User Authentication

**Objective**: Set up user authentication to allow users to sign up, log in, and log out using Firebase or Supabase.

- **Authentication Service**: Integrate Firebase or Supabase to handle user authentication processes.
- **Secure Routes**: Ensure that certain parts of the application are accessible only to authenticated users.

### Checkout Process

**Objective**: Integrate Paystack to process payments securely. Build a checkout form that collects payment information and confirms orders.

- **Payment Integration**: Use Paystack's APIs to integrate payment functionalities.
- **Form Handling**: Create forms to collect user payment details and validate them before submission.

## Additional Resources

- **React**: [React Documentation](https://reactjs.org/docs/getting-started.html)
- **Redux Toolkit**: [Redux Toolkit Documentation](https://redux-toolkit.js.org/introduction/getting-started)
- **React Query**: [React Query Documentation](https://react-query.tanstack.com/overview)
- **Firebase**: [Firebase Documentation](https://firebase.google.com/docs/web/setup)
- **Supabase**: [Supabase Documentation](https://supabase.io/docs/guides/auth)
- **Paystack**: [Paystack Documentation](https://paystack.com/docs/payments/accept-payments)
- **React Router**: [React Router Documentation](https://reactrouter.com/web/guides/quick-start)
- **Tailwind CSS**: [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests. You can also open issues to discuss potential changes or report bugs.
