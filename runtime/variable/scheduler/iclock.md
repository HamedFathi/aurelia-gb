| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; IClock**

| Type                        |
|-----------------------------|
| InterfaceSymbol&lt;[IClock](/runtime/variable/scheduler/iclock.md)&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<IClock>('IClock').withDefault(x => x.instance(globalClock))
```