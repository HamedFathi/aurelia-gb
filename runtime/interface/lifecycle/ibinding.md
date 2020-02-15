| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; interceptor**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | this |

&nbsp;&nbsp; **&#10148; locator**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IServiceLocator](/kernel/interface/di/iservicelocator.md) |

&nbsp;&nbsp; **&#10148; $scope**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IScope](/runtime/interface/observation/iscope.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; part**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

The name of the `replace-part` template that this binding was declared inside of (if any, otherwise this property is `undefined`).
This property is passed through the AST during evaluation, which allows the scope traversal to go up to the scope of the `replace-part` if a property does not exist inside the `replaceable`.

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

&nbsp;&nbsp; **&#10148; $state**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [State](/runtime/enum/flags/state.md) |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; $bind**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; part**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; $unbind**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |