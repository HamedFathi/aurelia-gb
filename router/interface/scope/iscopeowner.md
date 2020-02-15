| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; connectedScope**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/router/class/scope/scope.md) |

&nbsp;&nbsp; **&#10148; scope**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/router/class/scope/scope.md) |

&nbsp;&nbsp; **&#10148; owningScope**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](/router/class/scope/scope.md) |

&nbsp;&nbsp; **&#10148; enabled**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; path**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; null |

&nbsp;&nbsp; **&#10148; options**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IScopeOwnerOptions](/router/interface/scope/iscopeowneroptions.md) |

&nbsp;&nbsp; **&#10148; isViewport**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; isViewportScope**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; isEmpty**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; setNextContent**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; content**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; canLeave**

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

&nbsp;&nbsp; **&#10148; canEnter**

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean &#124; [ViewportInstruction](/router/class/viewport-instruction/viewportinstruction.md)[]&gt; |

&nbsp;&nbsp; **&#10148; enter**

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

&nbsp;&nbsp; **&#10148; loadContent**

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

&nbsp;&nbsp; **&#10148; finalizeContentChange**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp; **&#10148; abortContentChange**

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

&nbsp;&nbsp; **&#10148; getRoutes**

| Return Type                       |
|-----------------------------------|
| [IRoute](/router/interface/interfaces/iroute.md)[] &#124; null |