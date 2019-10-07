# arrayReverse
```
const forEachRight = (arr, callback) =>
  arr
    .slice(0)
    .reverse()
    .forEach(callback);
```
**Usage:**
```
forEachRight([1, 2, 3, 4], val => console.log(val)); // '4', '3', '2', '1'
```
