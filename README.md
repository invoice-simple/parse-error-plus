This module adds the stack trace to Parse.Error objects and makes it an instance of native Error as well.
Tested on NodeJs

For more information: http://parseplatform.org/Parse-SDK-JS/api/classes/Parse.Error.html

## Install
`npm i @invoice-simple/parse-error-plus --save`

## Usage
### ES6 or Typescript

```ts
import { setupParseError } from '@invoice-simple/parse-error-plus'
setupParseError(Parse)
```

### Old way

```js
require('@invoice-simple/parse-error-plus').setupParseError(Parse)
```

`Parse` must be defined before calling it.
blablabla https://app.asana.com/0/170271111949733/623237959656805
