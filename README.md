### Universal Numeric Test

Numeric test that works on Numbers, Strings, and Floats. [Source](http://stackoverflow.com/questions/18082/validate-numbers-in-javascript-isnumeric)

```
function isNumber(n) {
  return !isNaN(parseFloat(n)) && isFinite(n);
}
```