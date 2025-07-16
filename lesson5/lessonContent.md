# Scripts, Build Processes and Running Servers

## Overview

Introduction on how to set up scripts to automate build processes and run servers using NPM scripts.

## Learning Objectives

- Understand scripts, build processes, and running servers

## Topics Covered

- NPM scripts
- Automating builds
- Running servers

## Status

pending

## Assignment

Automate Tasks with npm Scripts and Run a Server

### Objective

Create and manage npm scripts to automate tasks and use them to run a development server.

### Expected Capabilities

- Define and run npm scripts
- Setup a development environment
- Build a production version of an application

### Instructions

#### Part 1

**Define Custom Scripts**

Add 'start', 'build', and 'dev' scripts in package.json.

```
"scripts": { "start": "node server.js", "build": "webpack --mode production", "dev": "nodemon server.js" }
```

#### Part 2

**Run Development Server**

Use npm scripts to start a development server that auto-reloads on changes.

```
npm run dev
```

#### Part 3

**Automate the Build Process**

Create scripts that automate the build process using webpack.

```
npm run build
```

### Tasks

#### Task 1: Setup Development Server

Configure npm scripts to automatically restart the development server on changes.

```
"scripts": { "dev": "nodemon server.js" }
```

### Submission Instructions

Submit the updated package.json file and a short video demonstrating your server handling live reloading.

### Checklist

- [ ] Scripts defined in package.json
- [ ] Development server starts with nodemon
- [ ] Build process executes successfully

### Check for Understanding

**What is the purpose of npm 'scripts'?**

- Manage dependencies
- Automate tasks
- Compile code

**Answer:** Automate tasks

**Why use a development server like nodemon?**

- Increases server security
- Automatically restarts server on changes
- Improves CSS styling

**Answer:** Automatically restarts server on changes

**What is a common task to automate in a build process?**

- Transpiling ES6 code
- Updating database
- Improving SQL queries

**Answer:** Transpiling ES6 code

## Subsections

### Introduction to npm Scripts

npm scripts are one of the most powerful tools included with npm. They allow you to automate repetitive tasks. An npm script is essentially a pre-defined command that is executed when you run `npm run [script-name]`.

**Video URL:** http://video.com/npmScripts

**Code Examples:**

```
{
  "scripts": {
    "start": "node server.js",
    "build": "webpack --mode production"
  }
}
```

**External Links:**

- [https://docs.npmjs.com/misc/scripts](https://docs.npmjs.com/misc/scripts)

**Quizzes:**

**What command is used to run an npm script named 'build'?**

- npm run build
- npm start build
- node build.js

**Answer:** npm run build

### Creating and Managing npm Scripts

You can define custom scripts in the `scripts` section of your `package.json`. This could be anything from starting the server to automating tests and build tasks.

**Video URL:** http://video.com/creatingNpmScripts

**Code Examples:**

```
{
  "scripts": {
    "clean": "rm -rf dist",
    "test": "jest"
  }
}
```

**External Links:**

- [https://www.sitepoint.com/guide-basic-npm-run-commands/](https://www.sitepoint.com/guide-basic-npm-run-commands/)

**Quizzes:**

**Where do you define npm scripts within a project?**

- In package.json under "dependencies"
- In package.json under "scripts"
- In server.js file

**Answer:** In package.json under "scripts"

### Understanding the Build Process

The build process refers to converting source code into a production-ready application. This can include tasks such as transpiling, bundling, minifying, and cleaning of code.

**Video URL:** http://video.com/buildProcess

**Code Examples:**

```
// Example of build script
{
  "scripts": {
    "build": "babel src -d dist"
  }
}
```

**External Links:**

- [https://webpack.js.org/concepts/](https://webpack.js.org/concepts/)

**Quizzes:**

**Which tool is commonly used for bundling JavaScript files?**

- Babel
- Webpack
- Git

**Answer:** Webpack

### Setting Up and Running a Development Server

Running a local development server is crucial for testing changes quickly. npm can run scripts to start a server using packages like express or nodemon. This server can auto-reload on changes for efficiency.

**Video URL:** http://video.com/runningDevServer

**Code Examples:**

```
{
  "scripts": {
    "dev": "nodemon server.js"
  }
}
```

**External Links:**

- [https://expressjs.com/](https://expressjs.com/)
- [https://nodemon.io/](https://nodemon.io/)

**Quizzes:**

**Which npm package can automatically restart a Node.js application?**

- nodemon
- express
- pm2

**Answer:** nodemon

## Supplemental Videos

- [http://video.com/npmAdvancedUsage](http://video.com/npmAdvancedUsage)
- [http://video.com/buildWithWebpack](http://video.com/buildWithWebpack)

## References

- [https://docs.npmjs.com/cli/v7/commands/npm-run-script](https://docs.npmjs.com/cli/v7/commands/npm-run-script)
- [https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)

## Podcast URL

No podcast available