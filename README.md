# Shwe
shwe personal development

## Backbone js
- Get familiar with build system
- Get familiar with quality guideliness
- Get familiar with marionette and backbone
- Get familiar with ES6
- Get familiar with unit testing

## Build System
- Use grunt for building
- Build system should support ES6 to ES5 transpiling
- Should run tests
- Should support watching for files and auto reload during dev
- Prod build should uglify and minify sources

## Development
- JS libs: Backbone and marionette
- CSS: bootstrap
- Syntax: ES6
- Dependency management: standard ES6 module imports

## Quality 
- ESLint for static code analysis and formatting
- Editor config for IDE config
- Chai, mocha and phantomjs for testing

# Requirements
Aims at implementing authentication workflow. App should have 4 routes. 
- welcome: #welcome
- login: #login
- signup: #signup
- hello: #hello

If user is not logged in user should be shown welcome screen. It should have simple styling along with links to sign up and login.
Sign up screen should take name, email, password, dob. Email id without mail extension should be used to fetch gravatar image. If gravatar image fails default profile should be shown upon login.

Login page should login using email and password

Hello page should show user avatar (gravatar if available or default) and shows user age and days left before next birthday.

Aesthetic styling with bootstrap is expected

Localstorage can be used as db for storing user info or anything as your choice.

*Can also use backbone localstorage plugin for syncing model with localstorage*


