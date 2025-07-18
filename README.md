# @sameercbeyond/privatepackage

[![npm version](https://badge.fury.io/js/%40sameercbeyond%2Fprivatepackage.svg)](https://badge.fury.io/js/%40sameercbeyond%2Fprivatepackage)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

A private package that exports a single function to validate a string.

## Installation

To install this package, you'll need to have Node.js and npm installed. Then, run the following command in your terminal:

```bash
npm install @sameercbeyond/privatepackage
```

## Usage

To use this package in your project, import it and call the exported function:

```javascript
const isValid = require('@sameercbeyond/privatepackage');

const result1 = isValid('Welcome');
console.log(result1); // true

const result2 = isValid('Hello');
console.log(result2); // false
```

## API

### isValid(string)

Checks if the input string is strictly equal to 'Welcome'.

*   **string**: The string to validate. (Type: `String`)
*   **Returns**: `true` if the string is 'Welcome', otherwise `false`. (Type: `Boolean`)

## Contributing

Contributions, issues, and feature requests are welcome! Please check the [issues page](https://github.com/sameercbeyond/privatepackage/issues).

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.
