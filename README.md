# Random Codes Generator

Random Codes Generator

**THIS LIBRARY IS IN EARLY STAGES - EXPECT BEAKING CHANGES**

***

## Description:

This library generates random codes alternating consonants and vowels.

***

### Installation:

```sh
npm install rcgenerator
```

***

### Usage:

```js
const RandomCodesGenerator = require("rcgenerator");

const RCG = new RandomCodesGenerator();

console.log(RCG.generateCode(-1)); // Defaults to 8 - YIFEJUMA
console.log(RCG.generateCode(0));  // Defaults to 8 - HOVUDETO
console.log(RCG.generateCode());   // Defaults to 8 - MUWAXIDE
console.log(RCG.generateCode(1));  // H
console.log(RCG.generateCode(4));  // SANA
console.log(RCG.generateCode(7));  // HOKUDET
console.log(RCG.generateCode(12)); // NOWUKUZEDEWI
```

Set a default length by passing an object with `defaultLength` on it. (More options to come in future versions)

```js
const RCG = new RandomCodesGenerator({ defaultLength: 6 });
```

Using import syntax:

```js
import RandomCodesGenerator from "rcgenerator";
```

***

### Notes

At this stage the library will always generate a code that alternates consonants with vowels starting always with a consonant. This is just a way to make the codes somewhat readables.

***

### **TODO** and **Future Features**

* User defined arrays of vowels and consonants
* User defined starting letter (vowel/consonant)
* Hability to control UpperCase and LowerCase letters

***

### Feedback

All feedback is welcome just write an [issue](https://github.com/MrAmericanMike/rcgenerator/issues).

***

![License MIT](https://img.shields.io/badge/license-MIT-blue)
