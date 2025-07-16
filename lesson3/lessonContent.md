# Understanding package.json

## Overview

An insight into the structure of package.json file which holds various metadata relevant to the project.

## Learning Objectives

- Understand package.json structure

## Topics Covered

- package.json structure
- Metadata in package.json

## Status

complete

## Assignment

Creating and Customizing package.json

### Objective

Understand and create a package.json file for a project with specified configurations.

### Expected Capabilities

- Initialize a package.json
- Edit and add scripts to package.json

### Instructions

#### Part 1

**Initialize package.json**

Use npm init to create a basic package.json file.

```
$ npm init
```

**Add Custom Scripts**

Edit the package.json file to add custom scripts for running the server.

```
{
  "scripts": {
    "start": "node server.js",
    "test": "echo 'TODO: add tests'"
  }
}
```

### Tasks

#### Task 1: Create and customize a package.json

Create the package.json and add configuration details.

```
{
  "name": "custom-app",
  "version": "1.0.0",
  "main": "app.js",
  "scripts": {
    "dev": "nodemon app.js"
  }
}
```

### Submission Instructions

Submit the customized package.json file and screenshots of the scripts being run.

### Checklist

- [ ] Initialized package.json
- [ ] Added custom scripts
- [ ] Verified scripts by running them

### Check for Understanding

**What does the 'dev' script typically do?**

- Starts service in production mode
- Watches for changes and restarts the server
- Compiles CSS files

**Answer:** Watches for changes and restarts the server

**What happens if you change the 'main' field in package.json?**

- It changes the starting script
- It changes the project's name
- It changes the entry point file

**Answer:** It changes the entry point file

## Subsections

### Introduction to package.json

The package.json file is a fundamental part of Node.js project configurations. It holds various metadata relevant to the project and is essential for defining project properties, dependencies, and scripts.

**Video URL:** http://video.com/introToPackageJson

**Code Examples:**

```
{
  "name": "my-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "test": "mocha test.js"
  }
}
```

**External Links:**

- [https://docs.npmjs.com/files/package.json](https://docs.npmjs.com/files/package.json)

**Quizzes:**

**What is a key use of the package.json file?**

- Defining database schemas
- Defining project properties and dependencies
- Storing user data

**Answer:** Defining project properties and dependencies

### Key Elements of the package.json

A package.json file generally contains the following elements:
- **Name and Version**: Uniquely identifies your package, e.g., `"name": "my-app"`.
- **Main**: Entry point of the application, usually `index.js`.
- **Scripts**: Useful for specifying scripts to run, e.g., `"start": "node index.js"`.
- **Dependencies**: Specifies project dependencies per environment.

**Video URL:** http://video.com/packageJsonElements

**Code Examples:**

```
{
  "name": "sample-app",
  "version": "0.1.0",
  "main": "server.js",
  "scripts": {
    "dev": "nodemon server.js",
    "build": "webpack --config webpack.config.js"
  }
}
```

**External Links:**

- [https://docs.npmjs.com/cli/v7/configuring-npm/package-json](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)

**Quizzes:**

**Which field in package.json specifies the entry point?**

- name
- main
- scripts

**Answer:** main

### Creating a package.json

To create a package.json file, use `npm init` command. It will guide you through the creation process, step by step, asking for information about your project like name, version, and main file.

**Video URL:** http://video.com/creatingPackageJson

**Code Examples:**

```
$ npm init
{
  "name": "example-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  }
}
```

**External Links:**

No external links available

**Quizzes:**

**Which command initializes a new package.json file?**

- npm start
- npm install
- npm init

**Answer:** npm init

## Supplemental Videos

- [http://video.com/packageJsonTutorial](http://video.com/packageJsonTutorial)

## References

- [https://docs.npmjs.com/files/package.json](https://docs.npmjs.com/files/package.json)
- [https://nodejs.org/en/knowledge/getting-started/npm/what-is-the-file-package.json/](https://nodejs.org/en/knowledge/getting-started/npm/what-is-the-file-package.json/)

## Podcast URL

No podcast available