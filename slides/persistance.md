## Persistance des données 1/2

Import
```typescript
import "firebase/firestore";

...

export const champsCollection = db.collection(
  "champs"
) as firebase.firestore.CollectionReference<Champs>;
```