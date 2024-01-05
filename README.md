# Personal Finance Management App - Project Architecture

## Introduction

Welcome to the comprehensive project architecture of the Personal Finance Management App, leveraging Python Flask for the backend and PostgreSQL as the database. This document delves into the technologies, architectural decisions, and the overall structure that forms the backbone of the application.

## Purpose

The Personal Finance Management App is designed to empower users in effectively managing their finances. Key features include:

1. **Expense Tracking:** Users can record and organize financial transactions, gaining insights into spending patterns.
2. **Budget Setting:** Establish monetary limits for different categories, facilitating better control over expenditures.
3. **Investment Management:** Users can monitor and analyze their investments, obtaining a holistic view of their financial portfolio.
4. **Data Visualization:** Utilizes Chart.js for visually representing financial data, offering users an intuitive and transparent overview.

## Technologies Used

### Frontend
- **React with Tailwind CSS:** Ensures a dynamic and responsive user interface.
- **Material-UI (MUI):** Enhances UI design and maintains a consistent user experience.
- **Chart.js:** Enables interactive and visually compelling data visualization.

### Backend
- **Python Flask:** A lightweight and efficient web framework, handling server-side logic and API endpoints.

### Database
- **PostgreSQL:** Chosen as the relational database to store and manage application data securely.

### Authentication
- **User Authentication:** Implements secure user authentication to protect sensitive financial information.

### Frontend-Backend Communication
- **RESTful API:** Establishes standardized and efficient data exchange between the frontend and backend.

### Testing
- **Testing Frameworks:** Jest for React and Pytest for Flask, ensuring reliability through unit and integration tests.

## Decision-Making Process

### Architecture
The project follows a modular architecture to enhance maintainability and scalability. The frontend and backend are organized into distinct directories (/frontend, /backend), promoting clarity and ease of development.

### Technology Choices
- **React and Tailwind CSS:** Chosen for a modern and customizable frontend.
- **Flask:** Selected as the backend framework for its lightweight and efficient nature.
- **PostgreSQL:** Opted for its reliability and scalability as a robust relational database.

### Testing Approach
A rigorous testing strategy, including unit and integration testing, is employed to ensure the reliability and robustness of the application. Testing frameworks were chosen based on compatibility and effectiveness in their respective environments.

## Project Structure

- **/frontend:** Contains all frontend-related code, including React components, styles, and assets.
- **/backend:** Houses the Flask application, API routes, and backend logic.
- **/tests:** Encompasses all unit and integration tests for thorough validation.

## Running the Application

To run the Personal Finance Management App locally, follow these steps:

1. **Frontend:**
   - Navigate to `/frontend`.
   - Run `npm install` to install dependencies.
   - Execute `npm start` to launch the frontend development server.

2. **Backend:**
   - Navigate to `/backend`.
   - Set up a virtual environment and activate it.
   - Run `pip install -r requirements.txt` to install backend dependencies.
   - Execute `python app.py` to start the Flask backend server.

3. **Database:**
   - Set up and configure PostgreSQL according to specific instructions.

4. **Access the App:**
   - Open your preferred web browser and visit `http://localhost:3000` to explore the app.

## Conclusion

This project architecture provides a comprehensive view of the Personal Finance Management App, emphasizing the use of Python Flask for the backend and PostgreSQL as the chosen database. Feel free to explore the `/frontend` and `/backend` directories for an in-depth understanding. Adapt and extend the application based on evolving requirements. Happy coding!
