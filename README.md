### AS3 JSON Formatter
Simple function that allows you to format serialized JSON.

```actionscript3
const source : Object = {person:{name: "Ilya Malanin", age: 26, married: true}, location: {country: "Russia", city: "Tomsk"}};
var result : String = formatJSON(stringifyJSON.encode(source));
```

Result:
```
{
  "person": {
		"name": "Ilya Malanin",
		"age": 26,
		"married": true
	},
	"location": {
		"country": "Russia",
		"city": "Tomsk"
	}
}
```
