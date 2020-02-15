# &#10025; Summary

Represents a DocumentFragment

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Type Parameter(s)

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; isMounted**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; isLinked**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; next**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [INodeSequence](/runtime/interface/dom/inodesequence.md)&lt;T&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; childNodes**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The nodes of this sequence.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ArrayLike&lt;T&gt; |

&nbsp;&nbsp; **&#10148; firstChild**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |

&nbsp;&nbsp; **&#10148; lastChild**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; findTargets**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Find all instruction targets in this sequence.

| Return Type                       |
|-----------------------------------|
| ArrayLike&lt;T&gt; |

&nbsp;&nbsp; **&#10148; insertBefore**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Insert this sequence as a sibling before refNode

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; refNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; appendTo**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Append this sequence as a child to parent

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; parent**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; remove**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Remove this sequence from the DOM.

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp; **&#10148; addToLinked**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp; **&#10148; unlink**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp; **&#10148; link**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; next**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |