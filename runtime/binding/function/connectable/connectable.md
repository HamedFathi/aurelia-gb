| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | typeof connectableDecorator &#124; Class&lt;TProto & IConnectableBinding, TClass&gt; | ✘ | ✘  | ✔ |

# &#10025; Type Parameter(s)

| Type   | Constraint |
| ------ | ---------- |
| TProto | -          |

| Type   | Constraint |
| ------ | ---------- |
| TClass | -          |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Class&lt;TProto & Partial&lt;IConnectableBinding&gt; & IPartialConnectableBinding, TClass&gt; &#124; undefined | ✔  | ✘ | ✘ |