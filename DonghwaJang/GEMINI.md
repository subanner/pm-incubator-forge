# GEMINI Project Context

This file provides essential context about the `DonghwaJang` repository for the Gemini CLI.

## Project Overview

This repository is a collection of educational web development projects created by DonghwaJang. It serves as a personal incubator and learning space (`pm-incubator-forge`). The structure is a multi-project repository, with each sub-directory containing a distinct, standalone application.

The core technologies used across the projects are **React**, **Vite**, and **TypeScript**.

### Key Directories

*   `html5_css3/html-css-app`: A project focusing on fundamental HTML5 and CSS3 concepts, implemented within a React application.
*   `javascript/javascript-app`: A project dedicated to exploring core JavaScript concepts and data structures, demonstrated through various React components.
*   `next/frontend`: A project that appears to be a starting point for a Next.js or a more advanced frontend application, currently set up as a standard Vite + React app.

## Development Workflow

Each project is independent. To work on a specific project, you must first navigate to its directory.

**Example: Running the JavaScript project**

1.  **Navigate to the project directory:**
    ```bash
    cd javascript/javascript-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```

4.  **Build for production:**
    ```bash
    npm run build
    ```

5.  **Lint the code:**
    ```bash
    npm run lint
    ```

This workflow applies to all projects within this repository (`html-css-app`, `javascript-app`, `frontend`).

## Development Conventions

*   **Framework:** React is the UI library of choice.
*   **Build Tool:** Vite provides the development and build environment.
*   **Language:** TypeScript is used for type safety.
*   **Linting:** ESLint is configured for code quality and consistency. All code should pass the linting checks.
*   **Styling:** Standard CSS is used, with separate `.css` files for components.
