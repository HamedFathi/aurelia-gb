# &#10025; Summary

A representation of `IController` specific to a custom element whose `afterCompile` hook is about to be invoked (if present).
It has the same properties as `IContextualCustomElementController`, except the context is now compiled (hence 'compiled'), as well as the nodes, and projector.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IContextualCustomElementController](/runtime/interface/lifecycle/icontextualcustomelementcontroller.md)&lt;T, C&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

| Type | Constraint                                                        |
| ---- | ----------------------------------------------------------------- |
| C    | [IViewModel](/runtime/interface/lifecycle/iviewmodel.md)&lt;T&gt; |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; context**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The compiled render context used for hydrating this controller.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ICompiledRenderContext](/runtime/templating/interface/render-context/icompiledrendercontext.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; scopeParts**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The names of the `replace` parts that were declared in the same scope as this component's template.
The `replaceable` template controllers with those names will use this components's scope as the outer scope for properties that don't exist on the inner scope.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] |

&nbsp;&nbsp; **&#10148; isStrictBinding**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; projector**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The projector used for mounting the `nodes` of this controller. Typically this will be one of:
- `HostProjector` (the host is a normal DOM node)
- `ShadowDOMProjector` (the host is a shadow root)
- `ContainerlessProjector` (the host is a comment node)

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IElementProjector](/runtime/resources/interface/custom-element/ielementprojector.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; nodes**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The physical DOM nodes that will be appended during the `mount()` operation.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [INodeSequence](/runtime/interface/dom/inodesequence.md)&lt;T&gt; |