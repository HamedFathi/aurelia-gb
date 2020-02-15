| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ResourceType&lt;T, [ICustomAttributeViewModel](/runtime/interface/lifecycle/icustomattributeviewmodel.md)&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; readonly noMultiBindings?: boolean &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

# &#10025; Initializer

```ts
ResourceType<T, ICustomAttributeViewModel, PartialCustomAttributeDefinition>
```