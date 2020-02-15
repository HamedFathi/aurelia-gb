| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ObservedCollectionKindToType&lt;T&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#10025; Initializer

```ts
T extends CollectionKind.array ? IObservedArray :
T extends CollectionKind.indexed ? IObservedArray :
T extends CollectionKind.map ? IObservedMap :
T extends CollectionKind.set ? IObservedSet :
T extends CollectionKind.keyed ? IObservedSet | IObservedMap :
never
```