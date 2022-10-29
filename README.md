# Bright Money Budget App - React.js, Redux, Saga, Chart.js

## Problem Statement:

Adithya owns a car wash business and needs help to manage various bills from his vendors.
Build an application to help Adithya manage his monthly bills.
The application must be written in React with Redux, using appropriate middleware.
The bill manager shows a bill dashboard (list of bills) with the total monthly billed amount.
LEVEL-1:
• The user must be able to manually add, edit and remove bills. (update the state locally)
• The user must be able to filter bills by category. (category filter dropdown)
• Draw a time-series chart of the monthly billing cycle.
LEVEL-2:
Adithya wants to be able to see a minimum number of bills that should be paid (n), such that their
total value does not exceed the monthly budget value while meeting the condition that no more bills
can be added from the remaining bills.. Highlight all the bills that should be paid.

## The app uses following libraries/packages for development, build and deployment:

- **[React.js]** - An open-source JavaScript library for building user interfaces & single-page or mobile applications.
- **[Redux.js]** - A Predictable State Container for JS Apps
- **[Redux-Saga]** - A Redux Middleware library to handle Asynchronous Actions such as fetching data more easily & effciently
- **[React-Router]** - A package that provides the core routing functionality for React Router
- **[Chart.js]** - an open-source JavaScript library to draw different types of charts by using the HTML5 canvas element

## Screens:

1. **Overview Page** - Shows monthly bills in a graph

2. **Create/Edit Bill Screen** - Create![Create/Edit Bill] or edit bills on this screen using a simple form

3. **List all Bills Screen** - Create or edit bills on this screen using a simple form

## LocalStorage Data Storage

We are storing the data in localstorage to persist data in case of page refresh.

One bill object looks like following:

```
{
"id": 1,
"description": "Dominoes",
"category": "FoodNDining",
"amount": "430",
"date": "01-02-2020"
}
```

### `npm install`

Installs the important libraries to build and run the app.<br />

In case of any issue while building the app, delete the `node_modules` folder in the root directory and run this command again.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
