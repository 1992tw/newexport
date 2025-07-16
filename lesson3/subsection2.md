# Key Elements of the package.json

## Content

A package.json file generally contains the following elements:
- **Name and Version**: Uniquely identifies your package, e.g., `"name": "my-app"`.
- **Main**: Entry point of the application, usually `index.js`.
- **Scripts**: Useful for specifying scripts to run, e.g., `"start": "node index.js"`.
- **Dependencies**: Specifies project dependencies per environment.

## Video URL

http://video.com/packageJsonElements

## Code Examples

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

## External Links

- [https://docs.npmjs.com/cli/v7/configuring-npm/package-json](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)

## Quizzes

### Which field in package.json specifies the entry point?

- name
- main
- scripts

**Answer:** main