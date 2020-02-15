| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IElementProjector](/runtime/resources/interface/custom-element/ielementprojector.md)&lt;INode&gt; |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; $controller**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ICustomElementController](/runtime/interface/lifecycle/icustomelementcontroller.md)&lt;[AuNode](/testing/class/au-dom/aunode.md), ICustomElementViewModel&lt;AuNode&gt;&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; host**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| CustomElementHost&lt;[AuNode](/testing/class/au-dom/aunode.md)&gt; | ✘  | ✘ | ✘ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; host**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | CustomElementHost&lt;[AuNode](/testing/class/au-dom/aunode.md)&gt; |

# &#10025; Get Accessor(s)

&nbsp;&nbsp; **&#10148; children**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | ArrayLike&lt;CustomElementHost&lt;[IRenderLocation](/runtime/variable/dom/irenderlocation.md)&lt;[AuNode](/testing/class/au-dom/aunode.md)&gt; & AuNode&gt;&gt; |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; subscribeToChildrenChange**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | () =&gt; void | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; provideEncapsulationSource**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [AuNode](/testing/class/au-dom/aunode.md) |

&nbsp;&nbsp; **&#10148; project**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nodes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [INodeSequence](/runtime/interface/dom/inodesequence.md)&lt;INode&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; take**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nodes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [INodeSequence](/runtime/interface/dom/inodesequence.md)&lt;INode&gt; | ✘  | ✘ | ✘ |