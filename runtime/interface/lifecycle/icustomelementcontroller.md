# &#10025; Summary

A fully hydrated custom element controller.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICompiledCustomElementController](/runtime/interface/lifecycle/icompiledcustomelementcontroller.md)&lt;T, C&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

| Type | Constraint                                                                                  |
| ---- | ------------------------------------------------------------------------------------------- |
| C    | [ICustomElementViewModel](/runtime/interface/lifecycle/icustomelementviewmodel.md)&lt;T&gt; |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; viewModel**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

**Inheritdoc**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C |

&nbsp;&nbsp; **&#10148; bindingContext**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

**Inheritdoc**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C & { [x: string]: unknown; [x: number]: unknown; } |