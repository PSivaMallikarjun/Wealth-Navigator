# Finance Management Dashboard with AI-Powered Insights

This project is a comprehensive finance management dashboard built with Next.js, integrated with Firebase for backend services, Genkit AI for intelligent insights, and utilizing shadcn/ui for a modern and accessible user interface.

## Project Purpose

The primary goal of this project is to provide users with a robust platform for managing their finances, offering not just tracking and reporting capabilities but also leveraging AI to provide actionable insights. This includes predictions on inflation and recommendations for financial reserves based on user data.

## Technologies Used

*   **Next.js:** A React framework for building server-side rendered and static web applications.
*   **Firebase:** A platform for building web and mobile applications, providing services like authentication, database (Firestore), cloud functions, and hosting.
*   **Genkit AI:** A framework for building AI-powered applications, used here for creating and deploying AI flows for financial predictions and recommendations.
*   **shadcn/ui:** A collection of re-usable components built with Radix UI and Tailwind CSS, providing a consistent and accessible design system.

## Key Features

*   User authentication with Firebase.
*   Dashboard for overview of financial data.
*   Admin panel for managing users (if applicable).
*   AI-powered inflation prediction.
*   AI-powered recommendations for financial reserves.
*   Responsive and accessible user interface.

## File Structure

The project follows a standard Next.js file structure with additional directories for Firebase and Genkit AI integrations:

*   `/`: Project root. Contains configuration files like `package.json`, `next.config.ts`, and `tsconfig.json`.
*   `/.idx`: Configuration files for the development environment.
*   `/.vscode`: Visual Studio Code settings.
*   `/docs`: Project documentation, including the blueprint.
*   `/public`: Static assets like images and favicons.
*   `/src`: Source code directory.
    *   `/src/ai`: Contains Genkit AI related files, including flows and configurations.
    *   `/src/app`: Next.js application routes and pages.
        *   `/src/app/admin`: Admin panel pages and components.
        *   `/src/app/dashboard`: User dashboard pages and components.
    *   `/src/components`: Reusable React components, including those from shadcn/ui.
        *   `/src/components/layout`: Layout components like headers and footers.
        *   `/src/components/ui`: shadcn/ui components.
    *   `/src/hooks`: Custom React hooks.
    *   `/src/lib`: Utility functions and libraries.

## Setup

1. Clone the repository.
2. Install dependencies:




https://github.com/user-attachments/assets/5c919225-8e41-4a9e-82a4-3a9b32ec968c

