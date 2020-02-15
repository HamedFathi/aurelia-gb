# &#10025; Summary

A compiled `IRenderContext` that is ready to be used for creating component instances, and rendering them.

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICompiledRenderContext](/runtime/templating/interface/render-context/icompiledrendercontext.md)&lt;T&gt;, [IDisposable](/kernel/interface/interfaces/idisposable.md) |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; createComponent**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Creates a new component instance based on the provided `resourceKey`.
It is only safe to override the generic type argument if you know / own the component type associated with the name.

**Parameter(s)**

| Name        | Description                                                     |
| ----------- | --------------------------------------------------------------- |
| resourceKey |  The (full) resource key as returned from the `keyFrom` helper. |

**Returns**

A new instance of the requested component. Will throw an error if the registration does not exist.

**Example**

```ts
// Create a new instance of the 'au-compose' custom element
const elementInstance = factory.createComponent<Compose>(CustomElement.keyFrom('au-compose'));
  // Create a new instance of the 'if' template controller
  const attributeInstance = factory.createComponent<If>(CustomAttribute.keyFrom('if'));
    // Dynamically create a new instance of a custom element
    const attributeInstance = factory.createComponent(CustomElement.keyFrom(name));
```

| Return Type                       |
|-----------------------------------|
| TViewModel |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Type Parameter(s)**

| Type       | Constraint |
| ---------- | ---------- |
| TViewModel | -          |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; resourceKey**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; dispose**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Release any resources that were stored by `getComponentFactory()`.

| Return Type                       |
|-----------------------------------|
| void |