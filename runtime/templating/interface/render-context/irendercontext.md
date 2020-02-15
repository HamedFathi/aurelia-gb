# &#10025; Summary

A render context that wraps an `IContainer` and must be compiled before it can be used for rendering.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IContainer](/kernel/interface/di/icontainer.md) |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; dom**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IDOM](/runtime/variable/dom/idom.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; parts**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; definition**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The `CustomElementDefinition` that this `IRenderContext` was created with.
If a `PartialCustomElementDefinition` was used to create this context, then this property will be the return value of `CustomElementDefinition.getOrCreate`.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [CustomElementDefinition](/runtime/resources/class/custom-element/customelementdefinition.md)&lt;Constructable&lt;{}&gt;&gt; |

&nbsp;&nbsp; **&#10148; parentContainer**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The `IContainer` (which may be, but is not guaranteed to be, an `IRenderContext`) that this `IRenderContext` was created with.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IContainer](/kernel/interface/di/icontainer.md) |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; beginChildComponentOperation**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Prepare this factory for creating child controllers. Only applicable for custom elements.

**Parameter(s)**

| Name     | Description                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------- |
| instance |  The component instance to make available to child components if this context's definition has `injectable` set to `true`. |

| Return Type                       |
|-----------------------------------|
| [IRenderContext](/runtime/templating/interface/render-context/irendercontext.md)&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; instance**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; compile**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Compiles the backing `CustomElementDefinition` (if needed) and returns the compiled `IRenderContext` that exposes the compiled `CustomElementDefinition` as well as rendering operations.
This operation is idempotent.

**Returns**

The compiled `IRenderContext`.

| Return Type                       |
|-----------------------------------|
| [ICompiledRenderContext](/runtime/templating/interface/render-context/icompiledrendercontext.md)&lt;T&gt; |

&nbsp;&nbsp; **&#10148; getViewFactory**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Creates an (or returns the cached) `IViewFactory` that can be used to create synthetic view controllers.

**Parameter(s)**

| Name | Description                                                                                                                                                                        |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| name |  Optional. The `name` that will be used by `replaceable` part lookups or the `| view` value converter. Defaults to the `name` property of the passed-in `CustomElementDefinition`. |

**Returns**

Either a new `IViewFactory` (if this is the first call), or a cached one.

| Return Type                       |
|-----------------------------------|
| [IViewFactory](/runtime/interface/lifecycle/iviewfactory.md)&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |