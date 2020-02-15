| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ISpy&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint  |
| ---- | ----------- |
| T    | AnyFunction |

# &#10025; Initializer

```ts
T & {
  readonly calls: (readonly unknown[])[];
  restore(): void;
  reset(): void;
}
```