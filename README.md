### Type Agnostic Number Test

This test can determine the numeric quality of an object no matter it's type (Number, String, or Float). NaN and Infinity are not considered numbers.
__[Source](http://stackoverflow.com/questions/18082/validate-numbers-in-javascript-isnumeric)__

```
function isNumber(n) {
  return !isNaN(parseFloat(n)) && isFinite(n);
}
```