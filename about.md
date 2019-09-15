# Something about me..

Blumblum

```javascript
 const sleep = (msec) => {
  return new Promise(resolve => setTimeout(resolve, msec))
}
	let x = 5; 
callMe = async (x) => {
	console.log(`${x/1000} sec`);
	await sleep(x)
	callMe(x+x);
}

callMe(x)
```