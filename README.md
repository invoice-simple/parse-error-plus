This module adds the stack trace to Parse.Error objects and makes it an instance of native Error as well.
Tested on NodeJs

For more information: http://parseplatform.org/Parse-SDK-JS/api/classes/Parse.Error.html

## Install
`npm i is-parse-error --save`

## Usage
### ES6 or Typescript

```ts
import { setupParseError } from 'is-parse-error'
setupParseError(Parse)
```

### Old way

```js
require('is-parse-error').setupParseError(Parse)
```

`Parse` must be defined before calling it.
