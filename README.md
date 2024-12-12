# Centsable

## Project Overview
Centsable is a full-stack web application that allows users to track, categorize, and analyze their expenses. The goal is to provide a user-friendly interface for managing personal finances, including features for adding transactions, categorizing them, generating reports, and visualizing spending patterns.

## Features

### Core Features (MVP)

**User Authentication**  
- Users can sign up, log in, and manage their accounts securely.  
- Authentication implemented with JSON Web Tokens (JWT) for session management.

**Expense Management**  
- Add, edit, and delete expenses.  
- Each expense includes:  
  - Date  
  - Amount  
  - Category (e.g., Food, Transportation, Entertainment)  

**Expense Categories**  
- Default categories provided (e.g., Food, Transportation).  
- Users can create custom categories.

**Dashboard**  
- Displays an overview of spending for the current month:  
  - Total spent  
  - Breakdown by category  
  - Recent transactions

**Reports & Visualization**  
- Pie chart showing percentage spent by category.  
- Bar chart of monthly expenses over time.

### Additional Features (Post-MVP)

**Recurring Expenses**  
- Mark expenses as recurring and set a frequency (e.g., monthly, weekly).

**Export Data**  
- Download all expenses as a CSV file.

**Mobile-Friendly Design**  
- Responsive UI for mobile and tablet devices.

**Dark Mode**  
- Toggle between light and dark themes.

## Tech Stack

**Frontend**  
- React with TypeScript  
- Styled Components or TailwindCSS for styling

**Backend**  
- Node.js with Express or NestJS  
- JSON Web Tokens (JWT) for authentication

**Database**  
- PostgreSQL for relational data storage  
- Prisma ORM for schema management

**Infrastructure**  
- Docker for containerization  
- Deployment to AWS (e.g., EC2 or Cloud Run)

**Testing**  
- Jest for unit testing  
- Playwright for end-to-end testing

## User Flow

1. **Sign Up / Log In**:  
   Users create an account or log in with existing credentials.

2. **Dashboard**:  
   Displays monthly spending overview, visualizations, and shortcuts to add expenses.

3. **Add Expense**:  
   Users enter details for a new expense and save it.

4. **View and Manage Expenses**:  
   Users can list all expenses, filter by date or category, and edit/delete as needed.

5. **Analyze Spending**:  
   Users view graphs and download data to understand their spending patterns.