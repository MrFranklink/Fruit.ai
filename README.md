# Fruit.ai Frontend

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [Frontend Routes](#frontend-routes)
- [Responsive Design](#responsive-design)

## Overview

The frontend of the Fruit.ai project is built using React.js. It provides an interactive user interface for interacting with the FAQ system. Users can log in, view FAQs, use translation features, and more.

## Features

- **Login Page:** Users can log in using dummy credentials.
- **Homepage:** Provides navigation to various sections of the application.
- **Chat Button:** Redirects to the ChatApp page after a splash screen.
- **Translate Button:** Leads to a translation page.
- **FAQs Button:** Displays a list of FAQs retrieved from the backend.
- **About Button:** Shows information about the application.

## Requirements

- Node.js (v14 or higher)
- npm (v6 or higher) or Yarn (optional)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/MrFranklink/Fruit.ai.git
    ```

2. Navigate to the `frontend` directory:

    ```bash
    cd Fruit.ai/frontend
    ```

3. Install the required dependencies:

    Using npm:
    ```bash
    npm install
    ```

    Or using Yarn:
    ```bash
    yarn install
    ```

4. Create a `.env` file in the `frontend` directory and add the following environment variable:

    ```bash
    REACT_APP_API_URL=http://localhost:8000/api
    ```

## Running the Application

To start the frontend development server:

1. Run the following command:

    Using npm:
    ```bash
    npm start
    ```

    Or using Yarn:
    ```bash
    yarn start
    ```

2. The application will be available at `http://localhost:3000` by default.

## Frontend Routes

Here is an overview of the routes configured in the frontend application:

- **/**: Login Page
- **/home**: Homepage after login
- **/translate**: Translation page
- **/splash**: Brief splash screen before loading ChatApp
- **/chatapp**: Main chat application page
- **/about**: About page
- **/faq**: FAQ page

## Responsive Design

The frontend application is designed to be responsive and works well on various device resolutions, including:

- iPhone 14 Pro Max (430x932)
- iPhone XR (414x896)
- iPhone SE (375x667)
- Google Pixel 7 (412x915)
- Samsung Galaxy S20 (412x915)
