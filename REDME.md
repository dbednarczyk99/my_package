# @d.bednarczyk/random-id-generator

A lightweight JavaScript utility for generating random IDs consisting of **numbers**, **lowercase letters**, and **uppercase letters**. 

-----------------------------------------------------------------------------------------------------
## 📦 Installation

```bash
npm install @d.bednarczyk/random-id-generator
```

or using **yarn**:
```bash
yarn add @d.bednarczyk/random-id-generator
```

-----------------------------------------------------------------------------------------------------
## 🚀 Usage

```javascript
// CommonJS
const randomID = require('@d.bednarczyk/random-id-generator');

// ES Modules
import randomID from '@d.bednarczyk/random-id-generator';

// Generate a random ID with length of 10 characters
const id = randomID(10);
console.log(id); // Example output: "aZ8mK92BcP"

-----------------------------------------------------------------------------------------------------
## 📖 API

### `randomID(length)`

**Parameters:**
- `length` *(number)* – The desired length of the generated ID.

**Returns:**
- *(string)* – A randomly generated ID containing digits, lowercase, and uppercase letters.

-----------------------------------------------------------------------------------------------------
## 🛠 Example Outputs

randomID(5);  // "A1b9X"
randomID(8);  // "zP4kB7xM"
randomID(12); // "H8xP0bQwA2zL"
```

-----------------------------------------------------------------------------------------------------
## 📜 License
MIT License – feel free to use in personal and commercial projects.

-----------------------------------------------------------------------------------------------------
## 🧾 Versions
1.0.1 - Fix export bug
1.0.2 - Fix syntax error
1.0.3 - Add README.md