


<br>
<br>
# Dynamic Menu App with ReactJS and Hooks

This is a simple web application built using ReactJS and hooks that displays a dynamic menu with categories such as breakfast, lunch, dinner, and sweets. The menu data is fetched from a custom API that provides the necessary information for each menu item.

![Alt text](https://raw.githubusercontent.com/actron-git/menucard/main/freshfast--menucard-full-page-preview.png)



## Features

- Display menu items in different categories: breakfast, lunch, dinner, and sweets.
- Dynamic navbar that updates based on the available menu categories.
- Fetches menu data from a custom API for flexibility and easy updates.

## Prerequisites

- Node.js and npm must be installed on your machine.

## Getting Started

1. Clone this repository:

   ```bash
   git clone <repository_url>
   cd dynamic-menu-app

Install the dependencies:

### 'npm install'

Start the development server:

### 'npm start'


dynamic-menu-app/<br>
│<br>
├── src/<br>
│   ├── components/<br>
│   │   ├── Navbar.js<br>
│   │   ├── MenuList.js<br>
│   │   └── ...<br>
│   │<br>
│   ├── hooks/<br>
│   │   ├── useMenuData.js<br>
│   │   └── ...<br>
│   │<br>
│   ├── services/<br>
│   │   ├── menuApi.js<br>
│   │   └── ...<br>
│   │<br>
│   ├── App.js<br>
│   ├── index.js<br>
│   └── ...<br>
│<br>
├── public/<br>
├── package.json<br>
├── README.md<br>
└── ...<br>
<br>

Components
Navbar.js: Displays the dynamic navigation bar based on available menu categories.
MenuList.js: Renders the list of menu items within a specific category.
...
Hooks
useMenuData.js: Custom hook for fetching menu data from the API.
...
Services
menuApi.js: Module for interacting with the custom API to fetch menu data.
Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.


Thank You


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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
