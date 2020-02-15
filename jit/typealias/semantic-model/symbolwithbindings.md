| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | SymbolWithBindings&lt;TText, TElement, TMarker&gt; |

# &#10025; Type Parameter(s)

| Type  | Constraint                               |
| ----- | ---------------------------------------- |
| TText | [INode](/runtime/interface/dom/inode.md) |

| Type     | Constraint                               |
| -------- | ---------------------------------------- |
| TElement | [INode](/runtime/interface/dom/inode.md) |

| Type    | Constraint                               |
| ------- | ---------------------------------------- |
| TMarker | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Initializer

```ts
(
  CustomAttributeSymbol |
  CustomElementSymbol<TText, TElement, TMarker> |
    LetElementSymbol<TElement, TMarker> |
      TemplateControllerSymbol<TText, TElement, TMarker>
        )
```