# Introduction to npm Scripts

## Content

npm scripts are one of the most powerful tools included with npm. They allow you to automate repetitive tasks. An npm script is essentially a pre-defined command that is executed when you run `npm run [script-name]`.

## Video URL

http://video.com/npmScripts

## Code Examples

```
{
  "scripts": {
    "start": "node server.js",
    "build": "webpack --mode production"
  }
}
```

## External Links

- [https://docs.npmjs.com/misc/scripts](https://docs.npmjs.com/misc/scripts)

## Quizzes

### What command is used to run an npm script named 'build'?

- npm run build
- npm start build
- node build.js

**Answer:** npm run build