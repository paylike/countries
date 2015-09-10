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
	"paylike-currencies": "paylike/currencies#v1.x"
}
```

This will keep you on the `1.x` branch which will not have breaking changes
merged.

```js
var countries = require('paylike-countries');

countries;
/*
[
	'Austria',
	'Belgium',
	...
]
*/
```
