<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/react](./react.md) &gt; [BaseListenerParams](./react.baselistenerparams.md)

## BaseListenerParams interface

<b>Signature:</b>

```typescript
export interface BaseListenerParams<GExtension extends AnyExtension = any> extends EditorViewParams<SchemaFromExtensions<GExtension>>, RemirrorGetterParams 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [internalUpdate](./react.baselistenerparams.internalupdate.md) | <code>boolean</code> | A shorthand way of checking whether the update was triggered by editor usage (internal) or overwriting the state.<!-- -->- <code>true</code> The update was triggered by a change in the prosemirror doc or an update to the selection. In these cases <code>tr</code> will have a value. - <code>false</code> The update was caused by a call to <code>setContent</code> or <code>resetContent</code> |
|  [tr](./react.baselistenerparams.tr.md) | <code>Transaction&lt;SchemaFromExtensions&lt;GExtension&gt;&gt;</code> | The original transaction which caused this state update.<!-- -->This allows for inspecting the reason behind the state change. When undefined this means that the state was updated externally.<!-- -->If available: - Metadata on the transaction can be inspected. <code>tr.getMeta</code> - Was the change caused by added / removed content? <code>tr.docChanged</code> - Was ths change caused by an updated selection? <code>tr.selectionSet</code> - <code>tr.steps</code> can be inspected for further granularity. |

