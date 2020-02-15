| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly [ITargetedInstruction](/runtime/variable/definitions/itargetedinstruction.md)[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: [BindingStrategy](/runtime/enum/flags/bindingstrategy.md) &#124; undefined; readonly hooks?: Readonly&lt;[HooksDefinition](/runtime/class/definitions/hooksdefinition.md)&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; |

# &#10025; Initializer

```ts
PartialResourceDefinition<{
  readonly cache?: '*' | number;
  readonly template?: unknown;
  readonly instructions?: readonly (readonly ITargetedInstruction[])[];
  readonly dependencies?: readonly Key[];
  readonly injectable?: InjectableToken | null;
  readonly needsCompile?: boolean;
  readonly surrogates?: readonly ITargetedInstruction[];
  readonly bindables?: Record<string, PartialBindableDefinition> | readonly string[];
    readonly childrenObservers?: Record<string, PartialChildrenDefinition>;
      readonly containerless?: boolean;
      readonly isStrictBinding?: boolean;
      readonly shadowOptions?: { mode: 'open' | 'closed' } | null;
      readonly hasSlots?: boolean;
      readonly strategy?: BindingStrategy;
      readonly hooks?: Readonly<HooksDefinition>;
        readonly scopeParts?: readonly string[];
        }>
```