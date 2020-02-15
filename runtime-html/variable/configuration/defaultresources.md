# &#9733; Summary

Default HTML-specific (but environment-agnostic) resources:
- Binding Behaviors: `attr`, `self`, `updateTrigger`
- Custom Elements: `au-compose`
- Custom Attributes: `blur`, `focus`, `portal`

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
  AttrBindingBehaviorRegistration,
  SelfBindingBehaviorRegistration,
  UpdateTriggerBindingBehaviorRegistration,
  ComposeRegistration,
  PortalRegistration,
  FocusRegistration,
  BlurRegistration
]
```