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

## About this project

**Description:**

A restaurant chain has reached out to your team to build a reservation
system.

**Here are the details:**

-   Two categories of users / customers: guest user or registered user.

-   Users should be able to search for a table and reserve.

    -   User doesn't need to login to the system to reserve a table. If
        registered users, they can login.

    -   User enters name, phone, email, date and time (date picker), and
        \# of guests for dining and system presents available tables.

    -   Tables have maximum capacity limit i.e., 2, 4, 6, or 8.

    -   Different combinations are allowed, and owner accommodates the
        seating, for example: someone requests 8 guests and table for 8
        is not available but 2 + 6, or 4+4 is available. System should
        combine the tables and notify owner they need to combine tables.
        In this case System reserves both tables.

-   If a guest user i.e., not a registered user, system should prompt
    user to register (Optional) before finalizing the reservation.

-   Registered users will have these fields:

    -   Name, mailing address, billing address (checkbox if same as
        mailing address), Preferred Diner \# (system generated), Earned
        points (based on \$ spent i.e., \$1 is 1 point), preferred
        payment method (cash, credit, check).
