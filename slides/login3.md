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

```html
<link
    type="text/css"
    rel="stylesheet"
    href="https://www.gstatic.com/firebasejs/ui/4.6.1/firebase-ui-auth.css"
/>
```