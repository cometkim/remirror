<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/core](./core.md) &gt; [MapHelpers](./core.maphelpers.md)

## MapHelpers type

A utility type which maps the passed in extension helpers to a method called with `manager.data.helpers.helperName()`<!-- -->.

<b>Signature:</b>

```typescript
export declare type MapHelpers<GHelpers extends Record<string, AnyFunction>> = {
    [P in Key<GHelpers>]: GHelpers[P];
};
```
