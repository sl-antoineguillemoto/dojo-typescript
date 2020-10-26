## Login 2/4

route privée
```typescript
const PrivateRoute = ({
  component: Component,
  ...rest
}: {
  component: ElementType;
} & RouteProps) => {
  const user = useUserContext();
  return (
    <Route
      {...rest}
      render={(props) =>
        user ? <Component {...props} /> : <Redirect to="/login" />
      }
    />
  );
};
```