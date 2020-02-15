# &#10025; Summary

A representation of `IController` specific to a custom element whose `create` hook is about to be invoked (if present).
It is not yet hydrated (hence 'dry') with any rendering-specific information.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IComponentController](/runtime/interface/lifecycle/icomponentcontroller.md)&lt;T, C&gt;, [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;T, C&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

| Type | Constraint                                                        |
| ---- | ----------------------------------------------------------------- |
| C    | [IViewModel](/runtime/interface/lifecycle/iviewmodel.md)&lt;T&gt; |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; vmKind**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.customElement |

&nbsp;&nbsp; **&#10148; scope**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The scope that belongs to this custom element. This property is set immediately after the controller is created and is always guaranteed to be available.
It may be overwritten by end user during the `create()` hook.
By default, the scope's `bindingContext` will be the same instance as this controller's `bindingContext` property.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/runtime/observation/class/binding-context/scope.md) |

&nbsp;&nbsp; **&#10148; host**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The physical DOM node that this controller's `nodes` will be mounted to.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |