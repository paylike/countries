# Countries

Countries supported by Paylike. Sorted alphabetically.

Notice that this has nothing to do with accepting cards. Cards from all over
the world are accepted.

You will need a registered company or citizenship from one of these countries:

- Denmark
- Norway
- Sweden

## Usage

Pin the dependency to the current version branch to ensure future installs of
your application will work. Like so:

```json
"dependencies": {
	"@paylike/countries": "*"
}
```

```js
var countries = require('@paylike/countries');

countries;
/*
[
	{ code: 'DK', currency: 'DKK', name: 'Denmark' },
	{ code: 'NO', currency: 'NOK', name: 'Norway' },
	{ code: 'SE', currency: 'SEK', name: 'Sweden' },
]
*/

countries.find(c => c.code === 'DK');
// { code: 'DK', currency: 'DKK', name: 'Denmark' }

```
