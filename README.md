# pluralizer
A Node.js module that returns the plural form of any noun
## Installation 
```sh
npm install pluralizer --save
```
## Usage
### Javascript
```javascript
var pluralise = require('pluralizer');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'pluralizer';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('pluralizer');
});
```
## Test 
```sh
npm run test
```