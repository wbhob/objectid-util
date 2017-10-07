# objectid-util
Using MongoDB types in your frontend Angular app is tricky. At Canal, we are using submodules to manage typings between projects, so having this utility is helpful in our internal typings.

### Usage
```sh
$ npm install -D objectid-util
```

```ts
import { ObjectID } from 'objectid-util'; // and use as a type
```

*It is important to remember that ObjectID is simply a type, not an actual instantiable class.*
