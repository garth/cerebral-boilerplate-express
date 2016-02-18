# Cerebral Boilerplate Express

## Install
`git clone https://github.com/cerebral/cerebral-boilerplate-express.git` (and delete .git folder)

or **ZIP it** :-)

## Requirements
You need **NPM v3** and **NODE v5**.

## Run
1. `npm install`
2. `npm start`

## Build client for production
`npm run build`

Creates a dist folder with the bundle

## Overview

### React by default
The project runs with React by default and hot replacement of changes to the modules

### CSS Modules
CSS files loaded into components are locally scoped and you can point to class names with javascript. You can also compose classes together, also from other files. These are also hot loaded. Read more about them [here](http://glenmaddern.com/articles/css-modules).

### Hot reloading on server
You do not need to restart the server when doing changes. Try by removing colors in `server/index.js` and hitting the random color button.
