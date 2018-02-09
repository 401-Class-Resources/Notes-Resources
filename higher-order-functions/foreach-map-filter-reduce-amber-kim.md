# Quick notes from class (amber kim)

```
const double = () => {return 2 * n}

function myMap(arr, callback) {
    let result = [];
    for (let i = 0; i < arr.length; i++) {
        let element = arr[i];
        let result = cb(element);
        let results.push(result);
    }
    return results;
}

function myFilter(arr, callback) {
    let result = [];
    for (let i = 0; i < arr.length; i++) {
        let element = arr[i];
        let result = cb(element);
        if (result === true) {
            results.push(result);
        } 
    }
    return results;
}

function myFilter(arr, callback) {
    let result = initialValue;
    for (let i = 0; i < arr.length; i++) {
        result = callback(result, arr[i])
    }
    return results;
}
```