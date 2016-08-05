# eslint-config-simonrelet

> My ESLint shareable config for JavaScript style guide.

## Install

```
$ npm install --save-dev eslint eslint-config-simonrelet
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"scripts": {
		"lint": "eslint ."
	},
	"devDependencies": {
		"eslint": "^3.2.2",
		"eslint-config-simonrelet": "^0.1.0"
	},
	"eslintConfig": {
		"extends": "simonrelet"
	}
}
```

Then lint with `$ npm run lint`.


## License

MIT
