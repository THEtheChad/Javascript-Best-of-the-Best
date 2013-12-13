### Type Agnostic Number Test

This test can determine the numeric quality of an object no matter its type (Number, String, or Float). NaN and Infinity are not considered numbers.
[[source]](http://stackoverflow.com/questions/18082/validate-numbers-in-javascript-isnumeric)

```
function isNumber(n){
  return !isNaN( parseFloat(n) ) && isFinite(n);
}
```