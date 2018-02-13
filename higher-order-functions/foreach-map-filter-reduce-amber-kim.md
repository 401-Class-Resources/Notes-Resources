# Quick notes from class (amber kim)

```
const double = () => {return 2 * n}

function forEach(arr, callback) {
    for (let i = 0; i < arr.length; i++) {
        let result = callback(arr[i]);
    }
    return undefined; // for each function always returns undefined.
}

function map(arr, callback) {
    let result = [];
    for (let i = 0; i < arr.length; i++) {
        let element = arr[i];
        let result = callback(element);
        let results.push(result);
    }
    return results;
}

function myFilter(arr, callback) {
    let result = [];
    for (let i = 0; i < arr.length; i++) {
        let element = arr[i];
        let result = callback(element);
        if (result === true) {
            results.push(result);
        } 
    }
    return results;
}

function reduce(arr, callback, initalValue) {
    let result = initialValue;
    for (let i = 0; i < arr.length; i++) {
        result = callback(result, arr[i])
    }
    return results;
}
```