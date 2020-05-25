## About

This repo demonstrates how to import and customize bootstrap using node-sass. It uses an opinionated structure so you don't have to version control bootstrap directly. This is accomplished by hotfixing the `sass` imports straight from the `node_modules` folder. So anyone working on the folder knows that the bootstrap files were not modified at all, except for the `variables` declaration setting

Check out the [guide](https://www.vincentntang.com/customize-bootstrap-with-react/) for the reasoning behind setting the repo this way

## Quick start

This uses the standard `create-react-app` setup

```
npm install
npm start
```

Navigate to `localhost:3000`

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
