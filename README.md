# Random Codes

Random Codes Generator

**THIS LIBRARY IS IN EARLY STAGES - EXPECT BEAKING CHANGES**

***

Installation:

```sh
npm install random-codes
```

***

Usage:

```js
const RandomCodes = require("random-codes");

const RC = new RandomCodes();

console.log(RC.generateCode(-1)); // Defaults to 8 - YIFEJUMA
console.log(RC.generateCode(0));  // Defaults to 8 - HOVUDETO
console.log(RC.generateCode());   // Defaults to 8 - MUWAXIDE
console.log(RC.generateCode(1));  // H
console.log(RC.generateCode(4));  // SANA
console.log(RC.generateCode(7));  // HOKUDET
console.log(RC.generateCode(12)); // NOWUKUZEDEWI
```

Set a default length by passing an object with `defaultLength` on it. (More options to come in future versions)

```js
const RC = new RandomCodes({ defaultLength: 6 });
```

***

## Notes

At this stage the library will always generate a code that alternates consonants with vowels starting always with a consonant. This is just a way to make the codes somewhat readables.

***

## **TODO** and **Future Features**

* User defined arrays of vowels and consonants
* User defined starting letter (vowel/consonant)
* Hability to control UpperCase and LowerCase letters

***

### Feedback

All feedback is welcome just write an issue.

***

![License MIT](https://img.shields.io/badge/license-MIT-blue)
