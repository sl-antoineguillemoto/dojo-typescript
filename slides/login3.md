## Login 3/4

Initialisation ui
```typescript
import * as firebaseui from "firebaseui";

...

new firebaseui.auth.AuthUI(auth).start("htmlTag", {
      signInOptions: [auth.GoogleAuthProvider.PROVIDER_ID],
      signInSuccessUrl: "/",
    });;
```