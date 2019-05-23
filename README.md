# Bootstrap 4 boilerplate with sass and gulp 4
A Bootstrap 4.1.3 boilerplate with font-awesome, sass, gulp 4 tasks, browserSync (with hot-reloading). 
You can override bootstrap sass variables by placing those variables in 
`bootstrap4-starter/assets/scss/_bootstrap_variable_overrides.scss`

## Pre-requisite
- Node.js - https://nodejs.org/en/download/ 
- NPM - Comes with Node.js
- Gulp https://gulpjs.com/

## Getting started
1. Install Gulp Globally with npm package manager
`$ npm -g install gulp`

2. Clone repository:
`git clone https://github.com/chitru/bootstrap4-starter.git`

3. Change directory:
`cd bootstrap4-starter`
    
4. Install all dependencies and libraries:
`npm install`

5. Run Gulp Task:
  - `gulp`      - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

  - `gulp dev`  - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).
   
