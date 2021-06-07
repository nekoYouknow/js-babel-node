# Using Babel ... step by step

- yarn init -y
- yarn add @babel/core 
- yarn add @babel/cli 
- yarn add @babel/preset-env 
- yarn add @babel/node 
- package.json .. 
```
"babel": {
    "presets": ["@babel/env"]
}, 
"scripts": {
    "start": "babel-node index.js" 
}
```
- index.js (es6)
- yarn start




## others

- npx babel index.js | node 
