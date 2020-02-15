| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Indexer(s)

| Return Type                      |
|----------------------------------|
| any |

| Key Name                                 | Key Type                       |
|------------------------------------------|--------------------------------|
| key | string |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; $synthetic**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | true &#124; undefined |

&nbsp;&nbsp; **&#10148; $observers**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | IIndexable&lt;{ getOrCreate(lifecycle: ILifecycle, flags: LifecycleFlags, obj: IBindingContext &#124; IOverrideContext, key: string): PropertyObserver; }, PropertyObserver, string &#124; number &#124; symbol&gt; &#124; undefined |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; getObservers**

| Return Type                       |
|-----------------------------------|
| IIndexable&lt;{ getOrCreate(lifecycle: ILifecycle, flags: [LifecycleFlags](/runtime/enum/flags/lifecycleflags.md), obj: IBindingContext &#124; IOverrideContext, key: string): PropertyObserver; }, PropertyObserver, string &#124; number &#124; symbol&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |