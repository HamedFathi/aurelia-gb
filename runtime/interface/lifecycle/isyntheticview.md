# &#10025; Summary

The controller for a synthetic view, that is, a controller created by an `IViewFactory`.
A synthetic view, typically created when rendering a template controller (`if`, `repeat`, etc), is a renderable component with mountable DOM nodes that has no user view model.
It has either its own synthetic binding context or is locked to some externally sourced scope (in the case of `au-compose`)

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;T, IViewModel&lt;T&gt;&gt; |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; vmKind**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.synthetic |

&nbsp;&nbsp; **&#10148; viewModel**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

&nbsp;&nbsp; **&#10148; bindingContext**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

&nbsp;&nbsp; **&#10148; scope**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The scope that belongs to this view. This property will always be defined when the `state` property of this view indicates that the view is currently bound.
The `scope` may be set during `bind()` and unset during `unbind()`, or it may be statically set during rendering with `lockScope()`.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/runtime/observation/class/binding-context/scope.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; context**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The compiled render context used for rendering this view. Compilation was done by the `IViewFactory` prior to creating this view.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ICompiledRenderContext](/runtime/templating/interface/render-context/icompiledrendercontext.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; scopeParts**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The names of the `replace` parts that were declared in the same scope as this view's template.
The `replaceable` template controllers with those names will use this view's scope as the outer scope for properties that don't exist on the inner scope.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] |

&nbsp;&nbsp; **&#10148; isStrictBinding**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; nodes**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The physical DOM nodes that will be appended during the `mount()` operation.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [INodeSequence](/runtime/interface/dom/inodesequence.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; location**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The DOM node that this view will be mounted to.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderLocation](/runtime/variable/dom/irenderlocation.md)&lt;T&gt; &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; lockScope**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Lock this view's scope to the provided `IScope`. The scope, which is normally set during `bind()`, will then not change anymore.
This is used by `au-compose` to set the binding context of a view to a particular component instance.

**Parameter(s)**

| Name  | Description                      |
| ----- | -------------------------------- |
| scope |  The scope to lock this view to. |

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; hold**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Set the DOM node that this view will be mounted to, as well as the mounting mechanism that will be used.

**Parameter(s)**

| Name          | Description                                               |
| ------------- | --------------------------------------------------------- |
| location      |  The `IRenderLocation` that this view will be mounted to. |
| mountStrategy |  The method that will be used during mounting.            |

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; location**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; mountStrategy**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; release**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Mark this view as not-in-use, so that it can either be dereferenced and garbage-collected, or returned to cache if caching was enabled for this view.
If this view is not attached when this method is called, it will immediately be unmounted (if it was still mounted) and returned to cache (if it could be cached).

**Parameter(s)**

| Name  | Description                                              |
| ----- | -------------------------------------------------------- |
| flags |  The flags to pass to the synchronous unmount operation. |

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |