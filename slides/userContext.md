## userContext

```typescript
const UserContext = React.createContext<firebase.User | undefined>(undefined);
export const useUserContext = () => useContext(UserContext);

....

<UserContext.Provider value={currentUser}>
...
</UserContext>
```
