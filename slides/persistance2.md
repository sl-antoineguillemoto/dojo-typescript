## Persistance des données 2/2

Objet geopoint
```typescript
firebase.firestore.GeoPoint
```


Ajouter données
```typescript
  collection.add
```

Récupérer données
```typescript
  collection.get // promise data
  collection.onSnapshot(listener) // listener watch changes
```