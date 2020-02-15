| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IHydrateInstruction](/runtime/interface/definitions/ihydrateinstruction.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; type**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | TargetedInstructionType.hydrateTemplateController |

&nbsp;&nbsp; **&#10148; res**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; instructions**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ITargetedInstruction](/runtime/variable/definitions/itargetedinstruction.md)[] |

&nbsp;&nbsp; **&#10148; def**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; |

&nbsp;&nbsp; **&#10148; link**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

&nbsp;&nbsp; **&#10148; parts**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; &#124; undefined |