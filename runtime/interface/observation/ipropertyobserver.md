# &#10025; Summary

Describes a complete property observer with an accessor, change tracking fields, normal and batched subscribers

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IAccessor](/runtime/interface/observation/iaccessor.md)&lt;TObj[TProp]&gt;, [IPropertyChangeTracker](/runtime/interface/observation/ipropertychangetracker.md)&lt;TObj, TProp, unknown&gt;, [ISubscriberCollection](/runtime/interface/observation/isubscribercollection.md), [IBatchable](/runtime/interface/observation/ibatchable.md) |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| TObj | object     |

| Type  | Constraint |
| ----- | ---------- |
| TProp | keyof TObj |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; inBatch**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; observing**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

&nbsp;&nbsp; **&#10148; persistentFlags**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md) |