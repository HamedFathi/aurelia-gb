# &#9733; Summary

Default HTML-specfic (but environment-agnostic) renderers for:
- Listener Bindings: `trigger`, `capture`, `delegate`
- SetAttribute
- StyleProperty: `style`, `css`
- TextBinding: `${}`

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; DefaultRenderers**

| Type                        |
|-----------------------------|
| [IRegistry](/kernel/interface/di/iregistry.md)[] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
[
  ListenerBindingRendererRegistration,
  AttributeBindingRendererRegistration,
  SetAttributeRendererRegistration,
  SetClassAttributeRendererRegistration,
  SetStyleAttributeRendererRegistration,
  StylePropertyBindingRendererRegistration,
  TextBindingRendererRegistration
]
```