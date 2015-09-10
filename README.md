# Countries

Countries supported by Paylike.

Notice that this has nothing to do with accepting cards. Cards from all over
the world is accepted.

You will need a registered company or citizenship from one of these countries:

- Austria
- Belgium
- Bulgaria
- Croatia
- Cyprus
- Czech Republic
- Denmark
- Estonia
- Finland
- France
- Germany
- Greece
- Hungary
- Iceland
- Ireland
- Italy
- Latvia
- Lichtenstein
- Lithuania
- Luxembourg
- Malta
- Netherlands
- Norway
- Poland
- Portugal
- Romania
- Slovakia
- Slovenia
- Spain
- Sweden
- United Kingdom

## Usage

Pin the dependency to the current version branch to ensure future installs of
your application will work. Like so:

```json
"dependencies": {
	"paylike-currencies": "paylike/currencies#v2.x"
}
```

This will keep you on the `2.x` branch which will not have breaking changes
merged.

```js
var countries = require('paylike-countries');

countries;
/*
[
	{ code: 'AT', currency: 'EUR', name: 'Austria' },
	{ code: 'BE', currency: 'EUR', name: 'Belgium' },
	...
]
*/
```
