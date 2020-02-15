# &#10025; Summary

* Contains interfaces and types that aren't strongly connected
* to component(s) or that are considered an essential part
* of the API.

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | RouteableComponentType&lt;C&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| C    | Constructable&lt;{}&gt; |

# &#10025; Initializer

```ts
CustomElementType<C> & {
  parameters?: string[];
}
```