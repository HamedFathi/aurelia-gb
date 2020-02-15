| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | [RenderPlan](/runtime-html/class/create-element/renderplan.md)&lt;T&gt; | ✘ | ✘  | ✔ |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

| Type | Constraint              |
| ---- | ----------------------- |
| C    | Constructable&lt;{}&gt; |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; dom**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [IDOM](/runtime/variable/dom/idom.md)&lt;T&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; tagOrType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; C | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; props**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Record&lt;string, string &#124; IHydrateElementInstruction &#124; IHydrateTemplateController &#124; IHydrateLetElementInstruction &#124; IInterpolationInstruction &#124; IPropertyBindingInstruction &#124; IIteratorBindingInstruction &#124; ICallBindingInstruction &#124; IRefBindingInstruction &#124; ISetPropertyInstruction &#124; ILetBindingInstruction &#124; IHydrateAttributeInstruction &#124; ITextBindingInstruction &#124; IListenerBindingInstruction &#124; IAttributeBindingInstruction &#124; IStylePropertyBindingInstruction &#124; ISetAttributeInstruction &#124; ISetClassAttributeInstruction &#124; ISetStyleAttributeInstruction&gt; &#124; undefined | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; children**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | ArrayLike&lt;unknown&gt; &#124; undefined | ✔  | ✘ | ✘ |