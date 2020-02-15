| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICollectionSubscribable](/runtime/interface/observation/icollectionsubscribable.md) |

# &#10025; Indexer(s)

| Return Type                      |
|----------------------------------|
| [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md) |

| Key Name                                 | Key Type                       |
|------------------------------------------|--------------------------------|
| key | number |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; &#95;collectionSubscriberFlags**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [SubscriberFlags](/runtime/enum/observation/subscriberflags.md) |

&nbsp;&nbsp; **&#10148; &#95;collectionSubscriber0**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ICollectionSubscriber](/runtime/interface/observation/icollectionsubscriber.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;collectionSubscriber1**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ICollectionSubscriber](/runtime/interface/observation/icollectionsubscriber.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;collectionSubscriber2**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ICollectionSubscriber](/runtime/interface/observation/icollectionsubscriber.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;collectionSubscribersRest**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

@internal

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ICollectionSubscriber](/runtime/interface/observation/icollectionsubscriber.md)[] &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; callCollectionSubscribers**

| Return Type                       |
|-----------------------------------|
| void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; indexMap**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; hasCollectionSubscribers**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp; **&#10148; hasCollectionSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; removeCollectionSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; addCollectionSubscriber**

| Return Type                       |
|-----------------------------------|
| boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |