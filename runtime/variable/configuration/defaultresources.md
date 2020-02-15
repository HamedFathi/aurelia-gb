# &#9733; Summary

Default resources:
- Template controllers (`if`/`else`, `repeat`, `replaceable`, `with`)
- Value Converters (`sanitize`)
- Binding Behaviors (`oneTime`, `toView`, `fromView`, `twoWay`, `signal`, `debounce`, `throttle`)

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
  FrequentMutationsRegistration,
  InfrequentMutationsRegistration,
  ObserveShallowRegistration,
  IfRegistration,
  ElseRegistration,
  RepeatRegistration,
  ReplaceableRegistration,
  WithRegistration,
  SanitizeValueConverterRegistration,
  ViewValueConverterRegistration,
  DebounceBindingBehaviorRegistration,
  OneTimeBindingBehaviorRegistration,
  ToViewBindingBehaviorRegistration,
  FromViewBindingBehaviorRegistration,
  SignalBindingBehaviorRegistration,
  ThrottleBindingBehaviorRegistration,
  TwoWayBindingBehaviorRegistration
]
```