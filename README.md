# image-effects

## Description

### Steps
- cargo init --lib
- install webpack to create a development server, compile our rust code, and bundle our javascript
    - install webpack-cli to run webpack commands
    - install webpack-dev-server to run a development server
- configure webpack to compile our code
    - create a webpack.config.js file in the root directory
    - configure webpack to compile our rust code
    - configure webpack to bundle our javascript
    - configure webpack to serve our application


## Setup
- intialize npm
    ```npm init -y```
    creates a package file to keep track of our dependencies
- install webpack
```npm install -D webpack webpack-cli webpack-dev-server```
    -D flag means we are installing webpack as a development dependency
    - webpack is a module bundler for javascript applications
    - webpack-cli is a command line interface for webpack
    - webpack-dev-server is a development server that serves our application and automatically reloads the page when we make changes
- configure webpack to compile our code i.e. webpack needs entry point and an output for bundle (where to upload the bundle)
    - project code -> webpack -> bundle
    - create a webpack.config.js file in the root directory
    - configure webpack to compile our rust code, bundle javascript, html, and serve our application

- Note: We won't be writing tests in this project - learn more about writing test in rust [here](https://doc.rust-lang.org/book/ch11-00-testing.html)
