---
layout: post
title:  "Babel Transpilation"
date:   2017-09-13
tags:
  - javascript
  - babel
description: "Follow these steps to transpile ES6+ JavaScript code to ES5 in order to improve browser compatibility."
excerpt_separator:  <!--more-->
---
Follow these steps to transpile ES6+ JavaScript code to ES5 in order to improve browser compatibility.


1. Use `npm init` to create a **package.json** file in the root directory and give it a name and description.

2. Install the Babel command line npm package and add it to the `devDependencies` property:
  `npm install babel-cli -D`

3. Install the Babel preset environment npm package:
  `npm install babel-preset-env -D`

4. Add a .babelrc file to the project folder:
  `touch .babelrc`

5. In **.babelrc**, preset your local project's config to `"env"`.
```
    {
      "presets": ["env"]
    }
```
6. In **package.json**, add the script `"build": "babel src -d lib"`.
  Don't forget to add a comma after the "test" script.

7. Use `npm run build` to transpile the code in **src** and write it to **lib**.

To check browser compatibility use [caniuse.com](http://caniuse.com/)