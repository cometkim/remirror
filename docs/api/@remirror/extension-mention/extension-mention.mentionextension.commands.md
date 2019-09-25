<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/extension-mention](./extension-mention.md) &gt; [MentionExtension](./extension-mention.mentionextension.md) &gt; [commands](./extension-mention.mentionextension.commands.md)

## MentionExtension.commands() method

<b>Signature:</b>

```typescript
commands({ type, getState }: CommandMarkTypeParams): {
        createMention: (config?: Record<string, unknown> | undefined) => import("@remirror/core").CommandFunction<any>;
        updateMention: (config?: Record<string, unknown> | undefined) => import("@remirror/core").CommandFunction<any>;
        removeMention: ({ range }?: Partial<RangeParams<never>>) => import("@remirror/core").CommandFunction<any>;
    };
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  { type, getState } | <code>CommandMarkTypeParams</code> |  |

<b>Returns:</b>

`{
        createMention: (config?: Record<string, unknown> | undefined) => import("@remirror/core").CommandFunction<any>;
        updateMention: (config?: Record<string, unknown> | undefined) => import("@remirror/core").CommandFunction<any>;
        removeMention: ({ range }?: Partial<RangeParams<never>>) => import("@remirror/core").CommandFunction<any>;
    }`
