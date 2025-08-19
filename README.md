# **Next.js With GraphQL Character App**


This is a simple **Next.js** application that fetches and displays data from a **GraphQL API** (Rick and Morty API) using **Apollo Client**.  
It demonstrates how to integrate GraphQL queries inside a Next.js project with server-side rendering (SSR) and style the UI with **Tailwind CSS**.



**Endpoint**

The GraphQL endpoint for this API is: <https://rickandmortyapi.com/graphql>




##  Features
- **Next.js** for fast, server-rendered React pages
- **Apollo Client** for GraphQL queries
- **Tailwind CSS** for modern, responsive UI
- Server-side rendering with `getServerSideProps`
- Fetches a specific character by `id`


# **Error Handling and Monitoring in Next.js**

## Overview
This project demonstrates how to implement robust error handling in a Next.js application using **Error Boundaries** and **Sentry** integration. It ensures that runtime errors are gracefully caught, logged, and displayed with a user-friendly fallback UI.

## Features
- **Error Boundary**  
  - Implemented as a TypeScript class component.  
  - Wraps the main application to catch runtime errors in the React tree.  
- **Fallback UI**  
  - Provides a custom UI when an error occurs.  
  - Includes a recovery option for users to retry.  
- **Test Component**  
  - A sample component that intentionally throws errors for testing error handling.  
- **Sentry Integration**  
  - Monitors and logs application errors in real time.  
  - Provides visibility into error details for debugging.  

##  Implementation Details
1. **Created `ErrorBoundary` Component**
   - A class component with TypeScript interfaces (`ErrorBoundaryProps`, `ErrorBoundaryState`).
   - Implements `componentDidCatch` and `getDerivedStateFromError`.

2. **Wrapped Application with ErrorBoundary**
   - Ensures all child components are protected against runtime crashes.

3. **Developed Test Component**
   - A component purposely designed to throw errors to validate ErrorBoundary functionality.

4. **Sentry Integration**
   - Configured Sentry SDK for error monitoring.
   - Captures frontend errors and reports them to the Sentry dashboard.

5. **Fallback UI**
   - Displays a friendly error message.
   - Offers a "Try Again" button to reset the application state.




Author: Mashudu Molema

