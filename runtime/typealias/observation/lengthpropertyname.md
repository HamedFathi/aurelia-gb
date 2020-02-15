| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | LengthPropertyName&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#10025; Initializer

```ts
T extends unknown[] ? 'length' :
T extends Set<unknown> ? 'size' :
  T extends Map<unknown, unknown> ? 'size' :
    never
```