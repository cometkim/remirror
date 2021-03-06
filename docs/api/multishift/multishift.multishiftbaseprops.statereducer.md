<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [multishift](./multishift.md) &gt; [MultishiftBaseProps](./multishift.multishiftbaseprops.md) &gt; [stateReducer](./multishift.multishiftbaseprops.statereducer.md)

## MultishiftBaseProps.stateReducer property

This function will be called each time multishift sets its internal state (or calls the onStateChange handler for controlled props). It allows you to modify the state change that will take place which can give you fine grained control over how the component interacts with user updates without having to use controlled Props. It gives you the current state and the state that will be set, and you return the state that you want to set.

<b>Signature:</b>

```typescript
stateReducer?: (changesAndState: MultishiftStateChangeset<GItem>, action: MultishiftRootActions<GItem>, props: MultishiftProps<GItem>) => MultishiftState<GItem>;
```
