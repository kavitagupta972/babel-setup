
Referred https://www.javascripttutorial.net/es6/setting-es6-project-using-babel/ link for setting up babel.
Included app.js file in index.html to run the code of app.js

> npm install --save-dev babel-cli
"scripts": {
    "build": "babel src -d dist"
}
> npm install babel-preset-latest --save-dev

created file .babelrc and add below script :
{
  "presets": ["latest"]
}
