# Webpack 

## Create a node project using npm
```
create a npm project : npm init
```

## Install WebPack
```
npm install --save-dev webpack@2.2.0-rc.0
```


## Basic syntax:
In the project root directory maintain a file for **webpack** call as **webpack.config**
```javascript
// Basic webpack config file

const path = require('path');
 
 
 
const config = {
	 entry : './src/index.js',
	 output : {
		path :  path.resolve(__dirname, 'build'),
		filename : 'bundle.js'
	 }
	 
};

module.exports = config;
```
