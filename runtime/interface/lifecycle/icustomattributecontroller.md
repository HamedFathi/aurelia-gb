| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IComponentController](/runtime/interface/lifecycle/icomponentcontroller.md)&lt;T, C&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

| Type | Constraint                                                                                      |
| ---- | ----------------------------------------------------------------------------------------------- |
| C    | [ICustomAttributeViewModel](/runtime/interface/lifecycle/icustomattributeviewmodel.md)&lt;T&gt; |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; vmKind**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.customAttribute |

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

&nbsp;&nbsp; **&#10148; scope**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The scope that belongs to this custom attribute. This property will always be defined when the `state` property of this view indicates that the view is currently bound.
The `scope` will be set during `bind()` and unset during `unbind()`.
The scope's `bindingContext` will be the same instance as this controller's `bindingContext` property.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/runtime/observation/class/binding-context/scope.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; controllers**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

&nbsp;&nbsp; **&#10148; bindings**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |