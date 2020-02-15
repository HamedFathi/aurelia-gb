| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | HTMLInputElement |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; model**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | unknown |

&nbsp;&nbsp; **&#10148; $observers**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ({ [x: string]: PropertyObserver; [x: number]: PropertyObserver; } & { getOrCreate(lifecycle: ILifecycle, flags: LifecycleFlags, obj: IBindingContext &#124; IOverrideContext, key: string): PropertyObserver; } & { model?: [SetterObserver](/runtime/observation/interface/setter-observer/setterobserver.md) &#124; undefined; value?: [ValueAttributeObserver](/runtime-html/observation/interface/value-attribute-observer/valueattributeobserver.md) &#124; undefined; }) &#124; undefined |

&nbsp;&nbsp; **&#10148; matcher**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | typeof defaultMatcher &#124; undefined |