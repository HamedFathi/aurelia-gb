# &#10025; Summary

An observer that tracks collection mutations and notifies subscribers (either directly or in batches)

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICollectionChangeTracker](/runtime/interface/observation/icollectionchangetracker.md)&lt;CollectionKindToType&lt;T&gt;&gt;, [ICollectionSubscriberCollection](/runtime/interface/observation/icollectionsubscribercollection.md), [IBatchable](/runtime/interface/observation/ibatchable.md) |

# &#10025; Type Parameter(s)

| Type | Constraint                                                    |
| ---- | ------------------------------------------------------------- |
| T    | [CollectionKind](/runtime/enum/observation/collectionkind.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; inBatch**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; lifecycle**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILifecycle](/runtime/interface/lifecycle/ilifecycle.md) |

&nbsp;&nbsp; **&#10148; persistentFlags**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md) |

&nbsp;&nbsp; **&#10148; collection**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ObservedCollectionKindToType&lt;T&gt; |

&nbsp;&nbsp; **&#10148; lengthObserver**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T extends CollectionKind.array ? [ICollectionLengthObserver](/runtime/interface/observation/icollectionlengthobserver.md) : [ICollectionSizeObserver](/runtime/interface/observation/icollectionsizeobserver.md) |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; getLengthObserver**

| Return Type                       |
|-----------------------------------|
| T extends CollectionKind.array ? [ICollectionLengthObserver](/runtime/interface/observation/icollectionlengthobserver.md) : [ICollectionSizeObserver](/runtime/interface/observation/icollectionsizeobserver.md) |

&nbsp;&nbsp; **&#10148; getIndexObserver**

| Return Type                       |
|-----------------------------------|
| [ICollectionIndexObserver](/runtime/interface/observation/icollectionindexobserver.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; index**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; notify**

| Return Type                       |
|-----------------------------------|
| void |