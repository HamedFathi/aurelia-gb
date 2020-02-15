| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; IActivator**

| Type                        |
|-----------------------------|
| InterfaceSymbol&lt;[IActivator](/runtime/interface/activator/iactivator.md)&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<IActivator>('IActivator').withDefault(x => x.singleton(Activator))
```