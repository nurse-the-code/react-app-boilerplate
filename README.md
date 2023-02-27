# Getting Started with nurse-the-code's Material-UI Create React App

This boilerplate was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Install and Setup

1. Install [Node.js](https://nodejs.org/en/download/).
2. Install [Yarn](https://classic.yarnpkg.com/en/docs/install/).
3. Clone the repository.
4. Run `yarn setup` to install dependencies and set up Git hooks.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### `yarn lint`

Lints all JavaScript and TypeScript files in the project, ignoring the files specified in .gitignore. Uses ESLint to check for linting errors.

### `yarn format`

Formats all JavaScript, TypeScript, JSON, and Markdown files in the project using Prettier, and overwrites the existing files with the formatted ones. Ignores the files specified in .gitignore.

### `yarn prepare`

Runs husky install to install the Git hooks defined in .husky to enable linting, formatting, and testing on every commit and push.

### `yarn nuke`

Deletes the node_modules folder, package-lock.json, and yarn.lock files, and then reinstalls all dependencies using yarn install. This command can be used to fix issues related to dependencies.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
