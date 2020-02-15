| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | BindingBehaviorInstance&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | {}         |

# &#10025; Initializer

```ts
{
  bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: T[]): void;
  unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: T[]): void;
} & T
```