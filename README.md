# ATM React App Exercise

## Overview

This is a simple React app that presents the user with an ATM-like interface, with options to deposit or withdraw money, as well as display the current account balance. The goals of this exercise include:

1. Implement user-friendly UI and React components
2. Manage state of various UI elements
3. Validate form content in conjunction with state of other components

This was created to submit for an assignment in Module 15 of the MIT xPRO Full Stack Development course (Fall 2022).

## Details & Improvements

The exercise included the following details, which are implemented in the app:

- Adding validation so users can’t withdraw more money than the account balance
- Modifying the user interface to require users to select deposit or withdraw before an input field is visible

I styled the app using basic CSS in order to give it a cleaner interface.

I attempted to implement dropdown menus and buttons using Bootstrap, but was unsuccessful at the time of submission. I plan to go back and complete the UI improvements.

## How to Run

[Click this link](https://zikman23.github.io/atm-react-app/) to view the app live on GitHub.

This React app has been deployed to GitHub Pages using `gh-pages` by following the information provided [here](https://github.com/gitname/react-gh-pages).

It is viewable on the web without having to download and run it locally. However, the source code is also provided if you choose to do so. More information is below.

## React Toolchains

I converted this exercise to a React app by using `create-react-app`. Information can be found here: [**Create React App**](https://reactjs.org/docs/create-a-new-react-app.html).
You can learn more in the **Create React App documentation** [here](https://facebook.github.io/create-react-app/docs/getting-started) or [here](https://github.com/facebook/create-react-app).

### Available Scripts

<details>
<summary>In the project directory, you can run:</summary>

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

</details>
