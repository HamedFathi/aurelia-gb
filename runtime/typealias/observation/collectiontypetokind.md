| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CollectionTypeToKind&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#10025; Initializer

```ts
T extends unknown[] ? CollectionKind.array | CollectionKind.indexed :
T extends Set<unknown> ? CollectionKind.set | CollectionKind.keyed :
  T extends Map<unknown, unknown> ? CollectionKind.map | CollectionKind.keyed :
    never
```