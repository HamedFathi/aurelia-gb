| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; ISanitizer**

| Type                        |
|-----------------------------|
| InterfaceSymbol&lt;[ISanitizer](/runtime/resources/value-converters/interface/sanitize/isanitizer.md)&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<ISanitizer>('ISanitizer').withDefault(x => x.singleton(class {
  public sanitize(input: string): string {
    return input.replace(SCRIPT_REGEX, '');
  }
}))
```