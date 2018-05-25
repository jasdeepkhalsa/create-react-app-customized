# Create React App with a Customized `webpack`

Create react app output supporting themes in dev and production

## Pre-requisites

* node
* yarn

## Installation

```bash
$ yarn
```

## Usage

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

You can use the URL aliases to navigate to the specific theme:

* '/cat1' - For the category1 theme (default)
* '/cat2' - For the category2 theme

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder with the themes specified in `config/paths.js`.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](#deployment) for more information.

## Supported Browsers

By default, the generated project uses the latest version of React.

You can refer [to the React documentation](https://reactjs.org/docs/react-dom.html#browser-support) for more information about supported browsers.

## Acknowledgements

* This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app)

## TODO

* Instead of having done a `npm run eject`, instead this repo could be re-designed as a customized fork of `react-scripts` as per: https://auth0.com/blog/how-to-configure-create-react-app/
