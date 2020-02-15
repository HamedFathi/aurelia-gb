# &#9733; Summary

Default router resources:
- Custom Elements: `au-viewport`, `au-nav`
- Custom Attributes: `goto`, `href`

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; DefaultResources**

| Type                        |
|-----------------------------|
| [IRegistry](/kernel/interface/di/iregistry.md)[] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
[
  ViewportCustomElement as unknown as IRegistry,
  ViewportScopeCustomElement as unknown as IRegistry,
  NavCustomElement as unknown as IRegistry,
  GotoCustomAttribute as unknown as IRegistry,
  HrefCustomAttribute as unknown as IRegistry,
]
```