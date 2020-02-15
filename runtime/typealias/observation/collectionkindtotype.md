| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CollectionKindToType&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#10025; Initializer

```ts
T extends CollectionKind.array ? unknown[] :
T extends CollectionKind.indexed ? unknown[] :
T extends CollectionKind.map ? Map<unknown, unknown> :
  T extends CollectionKind.set ? Set<unknown> :
    T extends CollectionKind.keyed ? Set<unknown> | Map<unknown, unknown> :
      never
```