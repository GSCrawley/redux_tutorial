
# What problem does Redux solve?
## So, state is everywhere in web application. From now on I'll talk about state and logic in the context of a typical React application, but consider these concept applicable to any frontend architecture, regardless of the specific library. The thing is, can you imagine how much state a web application application has?

## Even an innocent single page app could grow out of control without clear boundaries between every layer of the application. This holds particularly true in React.

## Yeah, you can get by with keeping the state within a parent React component (or in context) as long as the application remains small. Then things will become tricky especially when you add more behaviours to the app. At some point you may want to reach for a consistent way to keep track of state changes. Not only, I’d say that frontend components shouldn’t know about the business logic. Ever.

## Unfortunately a ton of logic gets stuffed into frontend components these days. Is there an alternative to this agony?

## Redux can solve exactly those issues. It might not be clear in the beginning, but Redux helps giving each frontend component the exact piece of state it needs.

## Even better, Redux can hold business logic inside its own layer (middleware), alongside with the code for fetching data. The benefits of this approach are manifold.

# The Store:
## holds all of the application's state

## The most important concept to understand here is that the state in Redux comes from reducers. Let’s repeat: reducers produce the state of your application.

## What’s a reducer? A Redux reducer is just a JavaScript function. It takes two parameters: the current state and action

## The type property drives how the state should change and it's always required by Redux. The payload property instead describes what should change, and might be omitted if you don't have new data to save in the store.

## You might be surprised to know that Redux itself is a small library (2KB) and the most important methods are just three:b -getState- for reading the current state of the application, -dispatch- for dispatching an action, -subscribe- for listening to state changes

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
# redux_tutorial
