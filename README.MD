---
### Testing an object to see if it's a number (works for Strings, Numbers, and Floats)

__Source: http://stackoverflow.com/questions/18082/validate-numbers-in-javascript-isnumeric__

function isNumber(n) {
  return !isNaN(parseFloat(n)) && isFinite(n);
}