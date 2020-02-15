# &#10025; Summary

The base type for `ISyntheticView` and `ICustomElementController`.
Both of those types can:
- Have `bindings` and `controllers` which are populated during rendering (hence, 'Renderable').
- Have physical DOM nodes that can be mounted.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IController](/runtime/interface/lifecycle/icontroller.md)&lt;T, C&gt; |

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
| ✘ | ViewModelKind.customElement &#124; ViewModelKind.synthetic |

&nbsp;&nbsp; **&#10148; nextMount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; nextUnmount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; prevMount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; prevUnmount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderableController](/runtime/interface/lifecycle/irenderablecontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; bindings**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly [IBinding](/runtime/interface/lifecycle/ibinding.md)[] &#124; undefined |

&nbsp;&nbsp; **&#10148; controllers**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly IHydratedController&lt;T&gt;[] &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; mount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; unmount**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getTargetAccessor**

| Return Type                       |
|-----------------------------------|
| [IBindingTargetAccessor](/runtime/interface/observation/ibindingtargetaccessor.md)&lt;any, string &#124; number &#124; symbol, unknown&gt; &#124; undefined |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; propertyName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; addBinding**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; binding**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; addController**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; controller**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |