# Financial Dashboard

## Overview

This project is a financial dashboard application built with **Next.js**. It allows users to manage invoices through a secure and user-friendly interface. The application includes a public home page, a login page, and protected dashboard pages where authenticated users can create, view, update, and delete invoices.

The project is designed to demonstrate modern Next.js development practices, including routing, database integration, authentication, data fetching, form validation, and performance optimization.

## Features

-   **Public Home Page:** A welcoming landing page that introduces the application and its purpose.
-   **User Authentication:** A login page that allows users to sign in securely.
-   **Protected Dashboard:** Dashboard pages that are accessible only to authenticated users.
-   **Invoice Management:** Users can add new invoices, edit existing invoices, and delete invoices.
-   **Database Integration:** PostgreSQL database integration for storing and retrieving application data.
-   **Search and Pagination:** Search invoices and navigate through paginated results.
-   **Form Validation:** Server-side validation to ensure submitted data is accurate and complete.
-   **Error Handling:** Proper handling of application errors and missing pages.
-   **Responsive Design:** A user-friendly interface designed to work across different screen sizes.
-   **SEO and Metadata:** Page metadata to improve search engine visibility and support social sharing.

## Learning Objectives

This project explores several important concepts in modern Next.js development.

### 1\. Styling

Learn different ways to style a Next.js application and create a consistent, attractive user interface.

### 2\. Optimizations

Explore how to optimize images, links, and fonts to improve application performance and user experience.

### 3\. Routing and Layouts

Understand Next.js file-system routing, nested routes, and shared layouts to organize application pages effectively.

### 4\. Data Fetching

Learn how to connect a PostgreSQL database hosted on Vercel, retrieve data efficiently, and use streaming to improve perceived loading performance.

### 5\. Search and Pagination

Implement invoice search and pagination using URL search parameters, making results easier to navigate and share.

### 6\. Data Mutations

Use React Server Actions to create, update, and delete invoice records. Learn how to revalidate the Next.js cache so that updated data is reflected in the interface.

### 7\. Error Handling

Implement error handling for unexpected application failures and create appropriate 404 pages for routes or resources that cannot be found.

### 8\. Form Validation and Accessibility

Validate form data on the server, display meaningful error messages, and apply accessibility best practices to make forms easier for everyone to use.

### 9\. Authentication and Authorization

Implement user authentication with NextAuth.js and Proxy to help secure protected dashboard routes and control access to authenticated features.

### 10\. Metadata and Social Sharing

Configure page titles, descriptions, and other metadata to improve SEO and ensure pages display useful information when shared on social media.

## Tech Stack

The application uses the following technologies and tools:

-   **Next.js** — React framework for building full-stack web applications.
-   **React** — Library for building interactive user interfaces.
-   **TypeScript** — Adds static typing to JavaScript.
-   **PostgreSQL** — Relational database for storing invoices and related application data.
-   **Vercel** — Platform for hosting the application and database integration.
-   **NextAuth.js** — Authentication solution for managing user sign-in and sessions.
-   **CSS / Tailwind CSS** — Styling tools for creating a responsive interface.
-   **React Server Actions** — Handling server-side data mutations.

*Note: The technologies listed above should reflect the dependencies and services actually configured in the project.*

## Getting Started

### Prerequisites

Before running the project, ensure you have installed:

-   Node.js
-   npm, pnpm, yarn, or another supported package manager
-   Access to a PostgreSQL database
-   The required environment variables for database access and authentication

### Installation

1.  Clone the repository:

    ```
    git clone <repository-url>
    ```

2.  Navigate to the project directory:

    ```
    cd <project-directory>
    ```

3.  Install the dependencies:

    ```
    npm install
    ```

4.  Configure your environment variables in a `.env` or `.env.local` file, according to your project setup.
5.  Start the development server:

    ```
    npm run dev
    ```

6.  Open http://localhost:3000 in your browser.

## Project Goals

The main goal of this project is to build a practical financial dashboard while developing a deeper understanding of Next.js and full-stack web development.

By completing the project, you will gain experience in building secure applications, working with databases, managing application state through URL parameters, validating user input, and creating accessible, performant web interfaces.

## License

This project is intended for learning and educational purposes. Add a license file if you plan to distribute or publish the project.