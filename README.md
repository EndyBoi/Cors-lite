# CORS Lite

Just a basic CORS proxy, nothing to see here, direct URL may be found here: <https://cors-lite-proxy.herokuapp.com/>.
This is hosted freely for my own personal use so you may want to just host your own, milage may vary.

## Useage

JS example:

```js
fetch('https://cors-lite-proxy.herokuapp.com/', {
	headers: {
		'Target-URL': 'URL_TO_API',
	},
})
	.then((response) => response.json())
	.then((foxData) => console.log(foxData))
	.catch((error) => console.error(error))
```
