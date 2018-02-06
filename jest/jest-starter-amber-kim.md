# Amber Kim Notes on Jest

## TESTING WITH JEST
```javascript
// in the app
module.exports = {};
module.exports.containsVowel = containsVowels; //attaching the function to the object.
// in the test
const containsVowels = require(‘./word.js’); //pulls in the whole thing. vs…
const containsVowels = require(‘./word.js’).containsVowels; // just pulling in the method.

// test. nesting describes is ok.
describe("containsVowels function", () => {  //describe what you’re testing
    let expected = false;
    it("it should return false for an empty string" () => {
        let str = ‘’;
        let result = containsVowels(str);
        expect(result).toBe(expected);
    })

    it("it should return true for ‘a’ " () => {
    })

    it("it should return true for ’taxi’ " () => {
    })
})
```

## Command line
```
jest —watch
```
will keep watching and run the test again if you make a change to the file.