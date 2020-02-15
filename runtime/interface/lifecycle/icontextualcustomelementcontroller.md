# &#10025; Summary

A representation of `IController` specific to a custom element whose `beforeCompile` hook is about to be invoked (if present).
It has the same properties as `IDryCustomElementController`, as well as a render context (hence 'contextual').

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IDryCustomElementController](/runtime/interface/lifecycle/idrycustomelementcontroller.md)&lt;T, C&gt; |

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

The non-compiled render context used for compiling this component's `CustomElementDefinition`.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderContext](/runtime/templating/interface/render-context/irendercontext.md)&lt;T&gt; |