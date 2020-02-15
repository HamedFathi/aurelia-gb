| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ISubscribable](/runtime/interface/observation/isubscribable.md) |

# &#10025; Indexer(s)

| Return Type                      |
|----------------------------------|
| [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md) |

| Key Name                                 | Key Type                       |
|------------------------------------------|--------------------------------|
| key | number |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; &#95;subscriberFlags**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [SubscriberFlags](/runtime/enum/observation/subscriberflags.md) |

&nbsp;&nbsp; **&#10148; &#95;subscriber0**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ISubscriber](/runtime/interface/observation/isubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;subscriber1**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ISubscriber](/runtime/interface/observation/isubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;subscriber2**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ISubscriber](/runtime/interface/observation/isubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;subscribersRest**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ISubscriber](/runtime/interface/observation/isubscriber.md)&lt;unknown&gt;[] &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; callSubscribers**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; newValue**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; oldValue**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; hasSubscribers**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp; **&#10148; hasSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; removeSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; addSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |