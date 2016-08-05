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
		"eslint": "^2.10.2",
		"eslint-config-simonrelet": "^0.0.3"
	},
	"eslintConfig": {
		"extends": "simonrelet"
	}
}
```

Then lint with `$ npm run lint`.


## License

MIT
