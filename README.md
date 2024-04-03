# Utibu Health App

The Utibu Health App is designed to modernize the way patients at Utibu Health manage their medication needs. This solution comprises a mobile application for patients to make medication orders remotely and a backend system that integrates seamlessly with Utibu Health's existing SQL Server database and legacy Delphi application. The goal is to improve patient care and pharmacy operations by providing a convenient, secure, and efficient way for stable patients with chronic conditions like HIV, diabetes, and hypertension to refill their prescriptions.

## Features

- **Mobile App** (React Native)
  - User Registration and Login
  - Medication Browsing and Ordering
  - Order Status Checking
  - Account Statement Viewing

- **Backend System** (Node.js/Express)
  - RESTful API for Mobile App Interaction
  - Integration with Existing SQL Server Database
  - Authentication and Authorization
  - Order Processing and Inventory Management

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Node.js and npm
- React Native CLI
- PostgreSQL (If you're simulating the existing SQL Server environment locally)
- Android Studio or Xcode (for mobile app development and testing)

### Installing

A step by step series of examples that tell you how to get a development environment running.

#### Setting Up the Backend

1. Clone the repository to your local machine.
2. Navigate to the `server` directory.
3. Copy the `.env.example` file to `.env` and fill in your environment variables.
4. Install dependencies with npm:

   ```sh
   npm install
