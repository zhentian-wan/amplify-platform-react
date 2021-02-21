# Getting Started with Create React App with Amplify

```bash
amplify add Stroage
amplify pull
amplify push
```


## Authentication

`withAuthenticator` is a `HOC`, wrap the main app main to open a login UI.

```js
import { withAuthenticator } from '@aws-amplify/ui-react';

...

export default withAuthenticator(App)
```
