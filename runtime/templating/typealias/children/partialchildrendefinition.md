| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | PartialChildrenDefinition&lt;TNode&gt; |

# &#10025; Type Parameter(s)

| Type  | Constraint                               |
| ----- | ---------------------------------------- |
| TNode | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Initializer

```ts
{
  callback?: string;
  property?: string;
  options?: MutationObserverInit;
  query?: (projector: IElementProjector<TNode>) => ArrayLike<TNode>;
    filter?: (node: TNode, controller?: ICustomElementController<TNode>, viewModel?: ICustomElementViewModel<TNode>) => boolean;
      map?: (node: TNode, controller?: ICustomElementController<TNode>, viewModel?: ICustomElementViewModel<TNode>) => any;
        }
```