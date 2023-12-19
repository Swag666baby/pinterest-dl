# pinterest-dl 
[![NPM Version](https://img.shields.io/npm/v/pinterest-dl.svg?maxAge=10)](https://www.npmjs.com/package/pinterest-dl)
[![Npm package yearly downloads](https://badgen.net/npm/dy/pinterest-dl)](https://npmjs.com/package/pinterest-dl)

pinterest-dl is a library that allows you to search and download images from pinterest without any registration or key. 

# installation 
```
npm install pinterest-dl
```

# example
```javascript 
const {search} = require("pinterest-dl");

async function main(){
	const data = await search("dog");
	console.log(data);
}
main()
```
