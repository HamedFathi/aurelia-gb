| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IProxySubscribable](/runtime/interface/observation/iproxysubscribable.md) |

# &#10025; Indexer(s)

| Return Type                      |
|----------------------------------|
| [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md) |

| Key Name                                 | Key Type                       |
|------------------------------------------|--------------------------------|
| key | number |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; &#95;proxySubscriberFlags**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [SubscriberFlags](/runtime/enum/observation/subscriberflags.md) |

&nbsp;&nbsp; **&#10148; &#95;proxySubscriber0**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IProxySubscriber](/runtime/interface/observation/iproxysubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;proxySubscriber1**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IProxySubscriber](/runtime/interface/observation/iproxysubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;proxySubscriber2**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IProxySubscriber](/runtime/interface/observation/iproxysubscriber.md)&lt;unknown&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;proxySubscribersRest**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IProxySubscriber](/runtime/interface/observation/iproxysubscriber.md)&lt;unknown&gt;[] &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; callProxySubscribers**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; key**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; newValue**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; previousValue**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; hasProxySubscribers**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp; **&#10148; hasProxySubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; removeProxySubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; addProxySubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |