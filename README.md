# React-redux scaffold
A react scaffold that has set up React, Redux, Webpack, Babel, Eslint, Jest, Enzyme and Docker.


Running the docker image will serve the website on 8080 port via `nginx`.

## Prerequisite
Make sure you have `nodejs`, `npm` and `yarn` installed.

## Supported platforms
Windows, Mac, Linux

## Running this project locally

### Use yarn
Under the project root directory

* Firstly run `yarn install`
* Then run `yarn start`

The project will start on port 8080.

### Use docker
Under the project root directory

* Firstly run `make build` (sudo permission required)
* Then run `make serve` (sudo permission required)

The project will start on port 8080.

## Available scripts

### `yarn lint`

Runs eslint on all the js files

### `yarn lint-fix`

Runs eslint on fix linting issues within the js files

### `yarn test`

Runs jest and enzyme tests.

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

### `yarn build`

Builds the app for production to the `dist` folder.<br>

### `make build`

Builds the docker image

### `make serve`
Runs the docker image
