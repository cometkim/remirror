<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [multishift](./multishift.md) &gt; [MultishiftChangeHandlerProps](./multishift.multishiftchangehandlerprops.md) &gt; [onStateChange](./multishift.multishiftchangehandlerprops.onstatechange.md)

## MultishiftChangeHandlerProps.onStateChange property

This function is called anytime the internal state changes. This can be useful if you're using multishift as a "controlled" component, where you manage some or all of the state (e.g. isOpen, selectedItems, highlightedIndexes, etc) and then pass it as props, rather than letting multishift control all its state itself.

The parameters both take the shape of internal state (<!-- -->{<!-- -->highlightedIndex: number, inputValue: string, isOpen: boolean, selectedItem: any<!-- -->}<!-- -->) but differ slightly.

<b>Signature:</b>

```typescript
onStateChange?: (changes: MultishiftStateProps<GItem>, state: MultishiftState<GItem>) => void;
```
