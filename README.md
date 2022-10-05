# React Custom Setup

![GitHub package.json version](https://img.shields.io/github/package-json/v/matejb6/react-custom-setup)
![GitHub Release Date](https://img.shields.io/github/release-date/matejb6/react-custom-setup)
![GitHub last commit](https://img.shields.io/github/last-commit/matejb6/react-custom-setup)

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/matejb6/react-custom-setup/CI)
![GitHub repo size](https://img.shields.io/github/repo-size/matejb6/react-custom-setup)
![GitHub](https://img.shields.io/github/license/matejb6/react-custom-setup)

## About
Default React app extended with additional libraries and setup to help develop better apps.
Main idea is to present a React app with additional setup so developers can have it as a reference.
Includes GitHub Actions workflows, code formatting, code linting, pre commit hooks, etc.
Each component is covered with tests too.

## Content
The app consists of one view which is in works.

## App creation
The app was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Additional packages
* `ESLint` added with: `ng add @angular-eslint/schematics`
* `Prettier` added with: `npm install prettier --save-dev`
* `Husky` added with: `npm install husky --save-dev`
* `MUI` added with: `npm install @mui/material @emotion/react @emotion/styled`
* `Roboto Font` added with: `npm install @fontsource/roboto`
* `Icons` added with: `npm install @mui/icons-material`

## About package
### Scripts
* `start`: Starts React app in the development mode
* `build`: Builds React app
* `test`: Tests React app in the interactive watch mode
* `eject`: Ejects React app
* `prettier:check`: Checks code formatting with Prettier
* `prettier:write`: Formats code with Prettier
* `lint`: Lints code with ESLint
* `prepare`: Prepare script to install Husky

## GitHub Actions
Defined workflows:
* `CI` as a general CI workflow
* `Version` for creating new versions

For more details see `.github/workflows/`.

## Commit hooks
Pre commit hooks are used to check code with `Prettier` and `ESLint`.
Before each commit, staged files are checked with defined scripts and committing of unchecked code will be prevented.
To commit code successfully, check `Prettier` and `Lint` paragraphs of this file.

## Requirements
* node.js v14.0 and higher
* npm v6.0 and higher

## Setup
* In project root run `npm install` to install dependencies
* Script `prepare` should run with `npm install` to install husky, if not, run `npm run prepare`

## Start
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Test
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## Build
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Eject
**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Prettier
* In project root run `npm run prettier:check` to check if files are formatted
* In project root run `npm run prettier:write` to format files

## Lint
* In project root run `npm run lint` to lint the project

## New version
* Go to GitHub repo
* Click on `Actions`
* Click on `Version` workflow
* Click `Run workflow`
* Select branch and enter next version (eg. major, minor, patch)
* New version is created, commit and tag are pushed to repo

## New release
* Go to GitHub repo
* Click on `Releases`
* Click on `Create a new release`
* Select a tag
* Enter release title
* Add release description from changelog notes

## Learn More
You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## Developer
**Matej Buljan**
