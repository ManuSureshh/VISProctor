# Proctor: Full Stack Application
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
# FrontEnd
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


# BackEnd

# MonitorApplication
2 TABLES
ipPort entities ip_address , portno
userDetails entities email , tokenid, ip_port_id(one to one) mapped with ipPort TABLE ,
HENCE SAME IPADDRESS AND PORT NO IS ADDED IN BOTH TABLES WITH SAME ID

Scheduler = 1 sec

JSON BODY 
Eg: /adddetails

{
  "token_id": "abcdefghijk1234567",
  "email": "meganitish@gmail.com",
  "ipPort": {
  "ipAddress": "172.16.3.250" ,
    "port": 6969
  }
}


# Project Title

Frontend Web Application for DevOps Project

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This is the frontend web application for the DevOps project, developed using ReactJS and Material-UI. The application provides a user-friendly interface to interact with the backend services and perform various DevOps-related tasks.

## Features

- User authentication and authorization
- Dashboard with real-time data visualization
- Responsive design for different screen sizes
- Integration with backend APIs
- Theme customization with Material-UI

## Tech Stack

- **ReactJS**: A JavaScript library for building user interfaces
- **Material-UI**: A popular React UI framework for designing components with Material Design
- **Axios**: A promise-based HTTP client for making API requests
- **Redux**: A state management library (if applicable)
- **React Router**: For routing and navigation

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine
- Git installed on your machine
- A code editor like VSCode

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Navigate to the project directory:

    ```sh
    cd your-repo-name
    ```

3. Install the dependencies:

    ```sh
    npm install
    ```

## Usage

1. Start the development server:

    ```sh
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`

3. To build the project for production:

    ```sh
    npm run build
    ```

## Project Structure




